<script>
    import Stacks from "../components/Stacks.svelte";
</script>

<div class="flex flex-col gap-4">
    <!--    <h1 class="m-4 text-rose-400 underline">Here is some of my open source projects</h1>-->
    <!--    <PersonalProject/>-->
    <p>Portfolio :
        <a class="text-blue-600 hover:text-blue-800 hover:underline" href="https://rb.gy/uy8nj0"
           target="_blank">
            https://rb.gy/uy8nj0
        </a>
    </p>

    <h1>Personal Blog</h1>
    <ol class="list-disc list-inside">
        <li>
            <a class="text-blue-600 hover:underline hover:text-blue-800" href="https://nuxt-blog-gamma.vercel.app/"
               target="_blank">
                frontend nuxtjs ssr
            </a>
        </li>
        <li>
            <a class="text-blue-600 hover:underline hover:text-blue-800" href="https://vue-blog-gules.vercel.app/"
               target="_blank">
                frontend vuejs spa
            </a>
        </li>
        <li>
            <a class="text-blue-600 hover:underline hover:text-blue-800" href="https://api-blog.labkita.my.id"
               target="_blank">
                backend golang restapi
            </a> source data: database postgres
        </li>
        <li>
            <a class="text-blue-600 hover:underline hover:text-blue-800" href="https://fajar.labkita.my.id/"
               target="_blank">
                monolith laravel livewire filament
            </a> source data: database postgres
        </li>
        <li>
            <a class="text-blue-600 hover:underline hover:text-blue-800" href="https://blog.labkita.my.id/"
               target="_blank">
                monolith laravel livewire
            </a> source data: file markdown
        </li>
        <li>
            <a class="text-blue-600 hover:underline hover:text-blue-800" href="https://tutorial.labkita.my.id/"
               target="_blank">
                monolith sveltekit
            </a> source data: file markdown
        </li>
    </ol>

    <h1 class="text-2xl font-semibold">Mobile App</h1>
    <div class="flex flex-col gap-2">
        <a class="text-blue-600 hover:text-blue-800 hover:underline"
           href="https://play.google.com/store/apps/details?id=com.labkita.baca_alquran"
           target="_blank">
            Alquran dan Terjemahan
        </a>
        <img alt="alquran dan terjemahan" class="h-3/4 w-3/4 bg-cover rounded-md" src="quran.png">
    </div>


    <Stacks/>
</div>
