
<section id="projects" class="mt-13 px-4 w-full max-w-7xl mx-auto  border border-neutral-900 rounded-xl p-8 flex flex-col-reverse lg:flex-row items-center justify-between gap-10">
    <div class="max-w-7xl mx-auto">
      <h2 class="text-4xl font-bold text-white mb-12 text-left">Projects</h2>
  
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
        {#each [
          {
            title: "Barage",
            desc: "TCP framework has a special side for server and client.",
            link: "https://github.com/ewriq/barage"
          },
          {
            title: "Blog",
            desc: "My Markdown supported, Svelte-based personal blogging system.",
            link: "https://github.com/ewriq/blog-svelte-gofiber"
          },
          {
            title: "Score Table",
            desc: "A leaderboard site specially made for anime, like imdb.",
            link: "https://github.com/ewriq/anime-score"
          },
         {
            title: "Pouch",
            desc: "A control Docker Conteiners.",
            link: "https://github.com/ewriq/pouch"
          },
         {
            title: "Assaultrifle",
            desc: "Aws Lightsail Clone",
            link: "https://github.com/ewriq/assaultrifle"
          },
    {
            title: "Kanban",
            desc: "Trello Clone.",
            link: "https://github.com/ewriq/kanban"
          },

    {
            title: "Deepsearh",
            desc: "Get data easily, perfect for research.",
            link: "https://github.com/ewriq/awesome-golang"
          },


        ] as project}
          <div class="bg-neutral-800 border border-neutral-700 rounded-xl shadow-lg p-6 transition hover:border-blue-500">
            <h3 class="text-2xl font-semibold text-white mb-3">{project.title}</h3>
            <p class="text-gray-300 mb-4 leading-relaxed">{project.desc}</p>
            <a href={project.link} class="text-blue-400 hover:underline font-medium" target="_blank" rel="noopener noreferrer">
              Github →
            </a>
          </div>
        {/each}
      </div>
    </div>
  </section>
  
  
