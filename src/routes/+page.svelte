<script>
    export let stacks = [
        {
            name: "Nodejs",
            asset: "img/logos/node.png",
        },
        {
            name: "Docker",
            asset: "img/logos/docker-container-100.png",
        },
        {
            name: "Golang",
            asset: "img/logos/go.png",
        },
        {
            name: "PHP",
            asset: "img/logos/php.png",
        },
        {
            name: "Laravel",
            asset: "img/logos/laravel-100.png",
        },
        {
            name: "HTML",
            asset: "img/logos/html-5-96.png",
        },
        {
            name: "CSS",
            asset: "img/logos/css3-96.png",
        },
        {
            name: "Javascript",
            asset: "img/logos/javascript-96.png",
        },
        {
            name: "Svelte",
            asset: "img/logos/svelte-96.png",
        },
        {
            name: "Vuejs",
            asset: "img/logos/vue.png",
        },
        {
            name: "Alpinejs",
            asset: "img/logos/alpine.png",
        },
        {
            name: "Kotlin",
            asset: "img/logos/kotlin-96.png",
        },
        {
            name: "Flutter",
            asset: "img/logos/flutter-96.png",
        },
        {
            name: "AWS",
            asset: "img/logos/aws-96.png",
        },
        {
            name: "GCP",
            asset: "img/logos/google-150.png",
        },
        {
            name: "Digital Ocean",
            asset: "img/logos/digitalocean-100.png",
        },
        {
            name: "Linode",
            asset: "img/logos/linode.png",
        },
    ];
</script>

<div>
    <p class="mt-10 text-center text-slate-600 text-2xl">Stacks</p>

    {#each stacks as stack}
        <div class="border-2 border-slate-400 inline-block shadow-md mr-2 p-2 rounded mb-2">
            <img src="{stack.asset}" alt="" class="max-h-20" />
            <h5
                class="mb-2 text-xl font-bold tracking-tight text-slate-400 dark:text-white"
            >
                {stack.name}
            </h5>
        </div>
    {/each}
</div>
