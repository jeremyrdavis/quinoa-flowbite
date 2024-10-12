<script>
    import "../app.css";
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>
<Navbar>
  <NavBrand href="/">
    <img src="quarkus-logo-halloween.webp" class="me-3 h-6 sm:h-9" alt="Quarkus Happy AI Halloween" />
    <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Happy AI Halloween</span>
  </NavBrand>
  <NavHamburger  />
  <NavUl >
    <NavLi href="/">Home</NavLi>
    <NavLi href="/about">About</NavLi>
    <NavLi href="/docs/components/navbar">Navbar</NavLi>
    <NavLi href="/pricing">Pricing</NavLi>
    <NavLi href="/contact">Contact</NavLi>
  </NavUl>
</Navbar>
<div class="grid grid-cols-3 gap-4">
  <div>
    <!-- col 1 -->
    01
  </div>

  <div>
    <!-- col 2 -->
    <slot></slot>
  </div>

  <div>
    <!-- col 3 -->
    03
  </div>
</div>
