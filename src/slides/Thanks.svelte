<script>
  import Slide from "../lib/Slide.svelte";
  import Background from "../assets/buddy-bg.png";
  import Logo from "../assets/buddy-logo.png";
</script>

<Slide bgImage={Background}>
  <div class="flex flex-col justify-start items-start gap-4 h-[80vh] my-32">
    <div class="h-32">
      <img src={Logo} alt="Buddy"/>
    </div>
    <h1 class="text-left text-[4rem]">¡Gracias!</h1>
    <h3 class="text-left text-[#8DC63F] text-[2rem]">Queremos escucharte</h3>
  </div>
</Slide>
