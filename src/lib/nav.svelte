<script>
  import viteLogo from '/home/rocky/svelte-template/pix2proto/src/assets/svgviewer.svg'
  import { Nav, NavItem,NavLink,colorMode, useColorMode} from '@sveltestrap/sveltestrap'
useColorMode("dark") ;
</script>



<Nav tabs>
  <NavItem>
    <img src={viteLogo} class="logo" alt="Vite Logo" />
  </NavItem>
  
  <NavItem>
    <NavLink style="color: white;"href="#">Home</NavLink>
  </NavItem>
  <NavItem>
    <NavLink style="color: white;"href="#">Artists</NavLink>
  </NavItem>
  
  <NavItem>
    <NavLink style="color: white;" href="#">Schedule</NavLink>
  </NavItem>
  <NavItem>
    <NavLink style="color: white;"href="#">Label</NavLink>
  </NavItem>
  <NavItem>
    <NavLink style="color: white;"href="#">Shops</NavLink>
  </NavItem>
  <NavItem>
    <NavLink style="color: white;"href="#">Channels</NavLink>
  </NavItem>
  <NavItem>
    <NavLink style="color: white;" href="#">Search</NavLink>
  </NavItem>
  
</Nav>

<style>



</style>