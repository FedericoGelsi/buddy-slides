<script>
  import Slide from "../lib/Slide.svelte";
  import Background from "../assets/Slide-3-bg.png";
  import DataCard from "../lib/DataCard.svelte";
  import SlideTitleLight from "../lib/SlideTitleLight.svelte";
  import BuddyLogoLight from "../lib/BuddyLogoLight.svelte";
  import SlideImage from "../assets/Questions-pana 1.png";
  import Questions from "../lib/Questions.svelte";
</script>

<Slide bgImage={Background}>
  <div class="flex flex-col h-full py-16">
    <div class="flex justify-between items-start">
      <SlideTitleLight
        title={"Nuestra misión"}
        subtitle={"Concientizar, educar y prevenir"}
      />
      <BuddyLogoLight />
    </div>
    <div class="flex justify-between grow items-center">
      <div class="flex flex-col gap-4 grow">
        <h1 class="text-[#2C2C2E] text-[6rem] text-left">¿Por qué</h1>
        <h1 class="text-[#628A2C] text-[6rem] text-right">BUDDY?</h1>
      </div>
      <div class="">
        <Questions />
      </div>
    </div>
  </div>
</Slide>
