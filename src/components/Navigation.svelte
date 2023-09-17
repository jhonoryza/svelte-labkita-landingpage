<script>
    import {
        Navbar,
        NavBrand,
        NavLi,
        NavUl,
        NavHamburger,
        // Dropdown,
        // DropdownItem,
        // DropdownDivider,
        // Chevron,
    } from "flowbite-svelte";
</script>

<Navbar
    navClass="px-2 sm:px-4 py-2.5 w-full z-20 top-0 left-0 border-b shadow-lg"
    let:hidden
    let:toggle
>
    <NavBrand href="/">
        <span
            class="self-center whitespace-nowrap text-xl font-semibold dark:text-white"
            >Labkita</span
        >
    </NavBrand>
    <NavHamburger on:click={toggle} />
    <NavUl {hidden}>
        <NavLi href="/">Home</NavLi>
        <!-- <NavLi target="_blank" href="https://blog.labkita.my.id"
            >Laravel Blog</NavLi
        >
        <NavLi target="_blank" href="https://tutorial.labkita.my.id"
            >Svelte Blog</NavLi
        > -->
        <NavLi href="/contact">Contact</NavLi>

        <!-- contoh dropdown implementation -->
        <!-- <NavLi id="nav-menu1" class="cursor-pointer"
                ><Chevron aligned>Social</Chevron>
                </NavLi>
            <Dropdown triggeredBy="#nav-menu1" class="w-44 z-20">
                <DropdownItem on:click={ () => window.open('https://github.com/jhonoryza') }>
                    <i class="fab fa-github fa-2x" />
                </DropdownItem>
            </Dropdown> -->
    </NavUl>
</Navbar>
