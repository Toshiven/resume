<script>
    export let y;

    export let tabs = [
        {name: "about", link: "/about"},
        {name: "projects", link: "/projects"}
    ]
</script>

<header>
  <h1 class="font-medium">
    <b class="font-bold poppins">Andrew Kevin</b> <span class="">Abler</span>
  </h1>

  {#each tabs as tab}
  <a href={tab.link}>{tab.name}</a>
  {/each}

</header>