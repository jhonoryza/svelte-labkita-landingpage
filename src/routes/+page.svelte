<script>
    import Stacks from "../components/Stacks.svelte";
</script>

<div class="flex flex-col gap-4">
    <!--    <h1 class="m-4 text-rose-400 underline">Here is some of my open source projects</h1>-->
    <!--    <PersonalProject/>-->

    <div class="flex flex-col gap-2">
        <h1 class="text-xl font-semibold">Web App</h1>
        <a class="text-blue-600 hover:text-blue-800 hover:underline"
           href="https://temubisnis.id/"
           target="_blank">
            Temubisnis
        </a>
        <img alt="temubisnis" class="xl:h-1/2 xl:w-1/2 bg-cover rounded-md" src="https://minio.labkita.my.id/image/temubisnis.png">

        <a class="text-blue-600 hover:text-blue-800 hover:underline"
           href="https://ehhdev.com/"
           target="_blank">
            EHH
        </a>
        <img alt="ehh" class="xl:h-1/2 xl:w-1/2 bg-cover rounded-md" src="https://minio.labkita.my.id/image/ehh.png">
    </div>

    <div class="flex flex-col gap-2">
        <h1 class="text-xl font-semibold">Desktop App</h1>
        <a class="text-blue-600 hover:text-blue-800 hover:underline"
           href="https://dev.to/jhonoryza/tinkering-app-42f0"
           target="_blank">
            Tinkering App
        </a>
        <img alt="tinkering app" class="xl:h-1/2 xl:w-1/2 bg-cover rounded-md" src="https://minio.labkita.my.id/image/tinker/1.png">
    </div>

    <div class="flex flex-col gap-2">
        <h1 class="text-xl font-semibold">Mobile App</h1>
        <a class="text-blue-600 hover:text-blue-800 hover:underline"
           href="https://play.google.com/store/apps/details?id=com.labkita.baca_alquran"
           target="_blank">
            Alquran dan Terjemahan
        </a>
        <img alt="alquran dan terjemahan" class="xl:h-1/2 xl:w-1/2 bg-cover rounded-md" src="quran.png">
    </div>

    <div class="flex flex-col gap-2 text-sm">                
        <p> Blog :
            <a class="text-blue-600 hover:underline hover:text-blue-800" href="https://fajar.labkita.my.id"
                target="_blank">
                https://fajar.labkita.my.id
            </a>
        </p>
        <p> Portfolio :
            <a class="text-blue-600 hover:text-blue-800 hover:underline" href="https://rb.gy/uy8nj0"
               target="_blank">
                https://rb.gy/uy8nj0
            </a>
        </p>    
        <p> Github :
            <a class="text-blue-600 hover:text-blue-800 hover:underline" href="https://github.com/jhonoryza"
               target="_blank">
               https://github.com/jhonoryza
            </a>
        </p>    
        <p> Linkedin :
            <a class="text-blue-600 hover:text-blue-800 hover:underline" href="https://www.linkedin.com/in/fajar-sidik-priatna-8b31a788"
               target="_blank">
                https://www.linkedin.com/in/fajar-sidik-priatna-8b31a788
            </a>
        </p>
        <p> Tiktok :
            <a class="text-blue-600 hover:underline hover:text-blue-800" href="https://www.tiktok.com/@labkita.my.id"
                target="_blank">
                https://www.tiktok.com/@labkita.my.id
            </a>
        </p>
        <p> Threads :
            <a class="text-blue-600 hover:underline hover:text-blue-800" href="https://www.threads.net/@labkitadev"
                target="_blank">
                https://www.threads.net/@labkitadev
            </a>
        </p>
        <p> Dev.to :
            <a class="text-blue-600 hover:underline hover:text-blue-800" href="https://dev.to/jhonoryza"
                target="_blank">
                https://dev.to/jhonoryza
            </a>
        </p>
    </div>

<!-- 
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
    </ol> -->

    <Stacks/>
</div>
