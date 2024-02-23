<script lang="ts">
    import type {showcases} from "$lib/showcases"

    export let title = "";
    export let data: showcases[];
</script>
<section>
    <div class="my-2">
        <h1 class="text-center text-blue-400 font-bold text-xl">{title}</h1>
        <div class="grid md:grid-cols-3">
            {#each data as item}
                <div class="flex flex-col m-4">
                    <div class="flex justify-start">
                        <a href={item.repo} target="_blank"
                           class="hover:text-rose-500 cursor-pointer">
                              <span class="mr-2">
                                <i class="fi fi-brands-github"/>
                              </span>
                            {item.title}
                        </a>
                    </div>
                    <p class="text-xs">{item.description}</p>
                    <p class="text-xs cursor-pointer hover:text-blue-500"><a
                            href={item.link}>Demo: {item.link}</a></p>
                </div>
            {/each}
        </div>
    </div>
    <hr>
</section>