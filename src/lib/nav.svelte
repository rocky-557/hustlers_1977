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
    <NavLink href="#">Home</NavLink>
  </NavItem>
  <NavItem>
    <NavLink href="#">Artists</NavLink>
  </NavItem>
  
  <NavItem>
    <NavLink href="#">Schedule</NavLink>
  </NavItem>
  <NavItem>
    <NavLink href="#">Label</NavLink>
  </NavItem>
  <NavItem>
    <NavLink href="#">Shops</NavLink>
  </NavItem>
  <NavItem>
    <NavLink href="#">Channels</NavLink>
  </NavItem>
  <NavItem>
    <NavLink href="#">Search</NavLink>
  </NavItem>
  
</Nav>

<style>



</style>