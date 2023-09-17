<script>
  import { personalProjects } from "$lib/personal-projects";
</script>

<section>
  <div class="my-2">
    <h1 class="text-center font-bold text-2xl">Personal Project</h1>
    <div class="flex flex-row flex-wrap">
      {#each personalProjects as project}
        <!-- tech -->
        <!-- svelte-ignore a11y-click-events-have-key-events -->
        <!-- svelte-ignore a11y-no-static-element-interactions -->
        <div
          class="border border-slate-300 shadow-lg overflow-hidden rounded-lg w-1/8 hover:cursor-pointer m-2"
          on:click={() => {
            if (project.link != "#") {
              window.open(project.link, "_blank");
            }
          }}
        >
          <img src={project.image} alt="laravel" class="w-full max-h-64" />
          <div class="p-2">
            <p class="text-xl text-wrap">
              {project.title}
            </p>
            <a href={project.repo} target="_blank">
              <i class="fi fi-brands-github" />
            </a>
            <div class="text-sm">
              <p>{project.description}</p>
            </div>
          </div>
        </div>
        <!-- end tech -->
      {/each}
    </div>
  </div>
</section>
