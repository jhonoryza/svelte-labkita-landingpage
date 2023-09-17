<script>
  import { personalProjects } from "$lib/personal-projects";
</script>

<section>
  <div class="my-2">
    <h1 class="text-center font-bold text-2xl">Personal Project</h1>
    <div class="flex flex-row flex-wrap">
      {#each personalProjects as project}
        <!-- tech -->
        <div
          class="border border-slate-300 shadow-lg overflow-hidden rounded-lg w-1/8 m-2"
        >
          <!-- svelte-ignore a11y-click-events-have-key-events -->
          <!-- svelte-ignore a11y-no-noninteractive-element-interactions -->
          <img
            src={project.image}
            alt="laravel"
            class="w-full max-h-64 hover:cursor-pointer"
            on:click={() => {
              if (project.link != "#") {
                window.open(project.link, "_blank");
              }
            }}
          />
          <!-- svelte-ignore a11y-no-noninteractive-element-interactions -->
          <div class="p-2">
            <!-- svelte-ignore a11y-click-events-have-key-events -->
            <p
              class="text-xl text-wrap hover:cursor-pointer"
              on:click={() => {
                if (project.link != "#") {
                  window.open(project.link, "_blank");
                }
              }}
            >
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
