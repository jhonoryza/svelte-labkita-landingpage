<script lang="ts">
  import {stacks} from "$lib/stacks";
</script>

<section>
    <p class="mt-4 text-center text-blue-400 text-xl">Stacks</p>

    {#each stacks as stack}
        <div
                class="border-2 border-slate-400 inline-block shadow-md mr-2 p-2 rounded mb-2"
        >
            <img src={stack.asset} alt="" class="max-h-20"/>
            <h5
                    class="mb-2 text-xl font-bold tracking-tight text-slate-400 dark:text-white"
            >
                {stack.name}
            </h5>
        </div>
    {/each}
</section>
