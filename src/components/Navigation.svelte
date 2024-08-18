<script>
    import {Navbar, NavBrand, NavHamburger, NavLi, NavUl,} from "flowbite-svelte";
</script>

<Navbar
        let:hidden
        let:toggle
        navClass="px-2 sm:px-4 py-2.5 w-full z-20 top-0 left-0 max-w-7xl mx-auto"
>
    <NavBrand href="/">
        <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">
            Labkita
        </span>
    </NavBrand>
    <NavHamburger on:click={toggle}/>
    <NavUl {hidden}>
        <!--        <NavLi href="/">Home</NavLi>-->
        <!--        <NavLi href="https://fajar.labkita.my.id" target="_blank">Blog-->
        <!--        </NavLi>-->
        <NavLi href="https://github.com/jhonoryza" target="_blank">Github
        </NavLi>
        <!-- <NavLi target="_blank" href="https://tutorial.labkita.my.id"
            >Svelte Blog</NavLi
        > -->
        <!--        <NavLi href="/contact">Contact</NavLi>-->
        <NavLi href="https://www.linkedin.com/in/fajar-sidik-priatna-8b31a788/">Linkedin</NavLi>

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
