<script>
    import {personalProjects} from "../lib/personal-projects";
    import Showcase from "./Showcase.svelte";
    import {phplibs} from "../lib/phplibs";
    import {desktops} from "../lib/desktop";
    import {docs} from "../lib/docs";
    import {androids} from "../lib/android";
    import {devops} from "../lib/devops";
</script>

<Showcase
        data={personalProjects}
        title="Project app"
/>
<Showcase
        data={phplibs}
        title="PHP Library"
/>
<Showcase
        data={desktops}
        title="Desktop app"
/>
<Showcase
        data={androids}
        title="Android app"
/>
<Showcase
        data={devops}
        title="Devops"
/>
<Showcase
        data={docs}
        title="Docs library"
/>

