<script lang="ts">
  import { Icon } from "svelte-awesome";
  import {
    faSun,
    faMoon
  } from "@fortawesome/free-solid-svg-icons"

  let mode = "dark"
  
  const toggle = () => {
    mode = mode === "light" ? "dark" : "light"
    document.documentElement.classList.toggle("dark");
  }
</script>

<button on:click={toggle} class="p-1 fixed">
  {#if mode === "light"}
    <Icon data={faMoon}/>
  {:else}
    <Icon data={faSun}/>
  {/if}
</button>