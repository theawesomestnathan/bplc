<script lang="ts">
  import { Icon } from "svelte-awesome";
  import {
    faFacebook,
    faWhatsapp
  } from "@fortawesome/free-brands-svg-icons"
</script>

<div class="text-center pt-60">
  <h1 class="pt-28 text-5xl font-semibold w-[30rem] mx-auto">
    Socials
  </h1>
  
  <div class="flex space-x-5 pt-10 justify-center text-white pb-5">
    <div class="w-20 h-20 rounded-full bg-blue-500">
      <div class="pt-6">
        <a href="https://www.facebook.com/BPLCVet">
          <Icon data={faFacebook}/>
        </a>
      </div>
    </div>
    <div class="w-20 h-20 rounded-full bg-green-500">
      <div class="pt-6">
        <a href="https://wa.me/639977733188">
          <Icon data={faWhatsapp}/>
        </a>
      </div>
    </div>    
  </div>
</div>