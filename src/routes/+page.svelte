<script>
  import { hello } from "$lib";
  import { hello2 } from "@custom-alias";
</script>

<button on:click={hello}>call hello</button>
<button on:click={hello2}>call hello2</button>
