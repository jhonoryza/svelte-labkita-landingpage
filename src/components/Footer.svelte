<script>
    import {
        Footer,
        FooterCopyright,
        FooterLinkGroup,
        FooterLink,
    } from "flowbite-svelte";
    import "@flaticon/flaticon-uicons/css/all/all.css";
</script>

<Footer>
    <FooterCopyright href="/" by="Labkita" year={2023} />
    <FooterLinkGroup
        ulClass="flex flex-wrap items-center mt-3 text-sm text-gray-500 dark:text-gray-400 sm:mt-0"
    >
        <FooterLink href="/about">About</FooterLink>
        <FooterLink href="/contact">Contact</FooterLink>

        <FooterLink href="https://github.com/jhonoryza"
            ><i class="fi fi-brands-github" />
        </FooterLink>
        <FooterLink href="https://linkedin.com/in/fajar-sidik-priatna-8b31a788">
            <i class="fi fi-brands-linkedin" />
        </FooterLink>
        <FooterLink href="https://facebook.com/jardikoryza">
            <i class="fi fi-brands-facebook" />
        </FooterLink>
        <FooterLink href="https://instagram.com/jardik1990">
            <i class="fi fi-brands-instagram" />
        </FooterLink>
        <FooterLink href="https://twitter.com/jardik7">
            <i class="fi fi-brands-twitter" />
        </FooterLink>
    </FooterLinkGroup>
</Footer>
