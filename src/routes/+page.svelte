<script>
	export let stacks = [
		{
            'name': 'Nodejs', 
            'asset' : 'img/logos/node.png'
        },
		{
            'name': 'Docker', 
            'asset' : 'img/logos/docker-container-100.png'
        },
		{
            'name': 'Golang', 
            'asset' : 'img/logos/go.png'
        },
		{
            'name': 'PHP', 
            'asset' : 'img/logos/php.png'
        },
		{
            'name': 'Laravel', 
            'asset' : 'img/logos/laravel-100.png'
        },
		{
            'name': 'HTML', 
            'asset' : 'img/logos/html-5-96.png'
        },
		{
            'name': 'CSS', 
            'asset' : 'img/logos/css3-96.png'
        },
		{
            'name': 'Javascript', 
            'asset' : 'img/logos/javascript-96.png'
        },
		{
            'name': 'Svelte', 
            'asset' : 'img/logos/svelte-96.png'
        },
		{
            'name': 'Vuejs', 
            'asset' : 'img/logos/node.png'
        },
		{
            'name': 'Alpinejs', 
            'asset' : 'img/logos/node.png'
        },
		{
            'name': 'Kotlin', 
            'asset' : 'img/logos/kotlin-96.png'
        },
		{
            'name': 'Flutter', 
            'asset' : 'img/logos/flutter-96.png'
        },
		{
            'name': 'AWS', 
            'asset' : 'img/logos/aws-96.png'
        },
		{
            'name': 'GCP', 
            'asset' : 'img/logos/google-150.png'
        },
		{
            'name': 'Digital Ocean', 
            'asset': 'img/logos/digitalocean-100.png'
        },
		{
            'name': 'Linode', 
            'asset' : 'img/logos/node.png'
        }
    ]
</script>

<div class="container">
    <h2 class="md text-left my-2">Stacks</h2>

    <div class="row row-cols-1 row-cols-md-6 g-4">
            {#each stacks as stack}
            <div class="col text-center">
                <div class="card" style="height: max-content;">
                    <div class="card-img-top h-50">
                        <img src="{stack.asset}" alt="" />
                    </div>
                    <div class="card-body">
                        <h5 class="card-title">{stack.name}</h5>
                    </div>
                </div>
            </div>
            {/each}
    </div>
</div>
