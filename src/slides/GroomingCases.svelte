<script>
  import Slide from "../lib/Slide.svelte";
  import Background from "../assets/buddy-bg.png";
  import DataCard from "../lib/DataCard.svelte";
  import SlideTitleDark from "../lib/SlideTitleDark.svelte";
  import BuddyLogoDark from "../lib/BuddyLogoDark.svelte";
</script>

<Slide autoAnimate={true} bgImage={Background}>
  <div class="flex flex-col h-full py-16">
    <div class="flex justify-between items-start">
      <SlideTitleDark title={"Una situación alarmante"} subtitle={"UNESCO"} />
      <BuddyLogoDark />
    </div>
    <div class="grid grid-cols-2 gap-16 grow items-center grow"></div>
  </div>
</Slide>
