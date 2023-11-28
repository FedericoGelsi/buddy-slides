<script>
  import Slide from "../lib/Slide.svelte";
  import Background from "../assets/Slide-3-bg.png";
  import DataCard from "../lib/DataCard.svelte";
  import SlideTitleLight from "../lib/SlideTitleLight.svelte";
  import BuddyLogoLight from "../lib/BuddyLogoLight.svelte";
  import SlideImage from "../assets/Questions-pana 1.png";
  import Questions from "../lib/Questions.svelte";
  import Stairs from "../lib/Stairs.svelte";
</script>

<Slide bgImage={Background}>
  <div class="flex flex-col justify-between h-[80vh]">
    <div class="flex justify-between items-start">
      <SlideTitleLight
        title={"Nuestros próximos pasos"}
        subtitle={"Un compromiso a futuro"}
      />
      <BuddyLogoLight />
    </div>
    <div class="flex justify-between">
      <div class="flex flex-col justify-start gap-16">
        <div class="flex items-center gap-4">
          <div class="rounded-full w-4 h-4 bg-[#0C969D]"></div>
          <h1 class="text-[#2C2C2E] text-[2rem] text-left">
            Nuevos escenarios y actividades
          </h1>
        </div>
        <div class="flex items-center gap-4">
          <div class="rounded-full w-4 h-4 bg-[#0C969D]"></div>
          <h1 class="text-[#2C2C2E] text-[2rem] text-left">
            Nuevos escenarios y actividades
          </h1>
        </div>
        <div class="flex items-center gap-4">
          <div class="rounded-full w-4 h-4 bg-[#0C969D]"></div>
          <h1 class="text-[#2C2C2E] text-[2rem] text-left">
            Nuevos escenarios y actividades
          </h1>
        </div>
      </div>
      <div class="items-self-end">
        <Stairs />
      </div>
    </div>
  </div>
</Slide>
