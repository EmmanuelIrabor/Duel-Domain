

<script lang="ts">

    export let link:string;
    export let image:string;
    export let duel_count:string;
    export let platform:string;
    export let title:string;
    export let tags :string;
</script>

<a href="{link}">

    <div class="platform-game-card w-ful">
      <div class="platform-game-card--img w-full h-40 px-2 " style="background-image: url('{image}');">

        <div class="flex flex-row items-center justify-start">

                        <div class="flex items-center gap-1 text-xs mt-2">

                            <i class="fa-solid fa-burst text-green"></i>
                            {duel_count} Duels

                        </div>

                    </div>
        
      </div> 
      
      <div class="px-3 py-7">
         <i class="{platform} text-xs"></i>
       <p class="text-md font-bold mt-2">{title}</p>
       <p class="text-xs pb-5 mt-1 text-gray">{tags}</p>
      </div>
    </div>
</a>