

<script lang="ts">
    import DashboardNavItem from "./ui/DashboardNavItem.svelte";
    // export let navitem:boolean;
</script>

<div>
    <ul class="list-style-none p-0 m-0">
          <li>
            <DashboardNavItem active={true} link={'../'} icon={'fa-solid fa-cubes'} name={'DashBoard'}/>
          </li>
          <li class="mt-2">
            <DashboardNavItem active={false} link={'../'} icon={'fa-solid fa-gamepad'} name={'Games'}/>
          </li>
          <li class="mt-2">
            <DashboardNavItem active={false} link={'../'} icon={'fa-solid fa-wallet'} name={'Stake'}/>
          </li>
          <li class="mt-2">
            <DashboardNavItem active={false} link={'../'} icon={'fa-solid fa-burst'} name={'Matches'}/>
          </li>
          <li class="mt-2">
            <DashboardNavItem active={false} link={'../'} icon={'fa-solid fa-ranking-star'} name={'Tournaments'}/>
          </li>
          <li class="mt-2">
            <DashboardNavItem active={false} link={'../'} icon={'fa-solid fa-circle-nodes'} name={'Challenges'}/>
          </li>
          <li class="mt-2">
            <DashboardNavItem active={false} link={'../'} icon={'fa-regular fa-chess-king'} name={'Rankings'}/>
          </li>
          <li class="mt-2">
            <DashboardNavItem active={false} link={'../'} icon={'fa-solid fa-timeline'} name={'History'}/>
          </li>
        </ul>
</div>