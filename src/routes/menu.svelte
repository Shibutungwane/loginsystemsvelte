<script>
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte'
  </script>
 <div  class="px-20 pr-0 mb-0">
  <Navbar let:hidden let:toggle rounded color="form">
    <NavBrand href="/">
      <img src="/cropped-logo-group.png" class="h-6 " alt=" Logo"/>
      <!-- <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Xpertek</span> -->
    </NavBrand>
    <NavHamburger on:click={toggle} class="outline-none"/>
    <NavUl {hidden}>
      <NavLi href="/" active={true}>Home</NavLi>
      <NavLi href="/about">About</NavLi>
      <NavLi href="/services">Services</NavLi>
      <NavLi href="/pricing">Pricing</NavLi>
      <NavLi href="/contact">Contact</NavLi>
    </NavUl>
  </Navbar>
</div>