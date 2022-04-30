<script>
  import { locale } from "svelte-i18n";
</script>

<img src="../../public/assets/turkeyflag.png" alt="Turkish Flag" title="Türkçe" on:click={() => locale.set("tr")} />
<img src="../../public/assets/ukflag.png" alt="English Flag" title="English" on:click={() => locale.set("en")} />

<style>
  img {
    cursor: pointer;
  }
</style>