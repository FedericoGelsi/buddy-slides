<script>
  import Slide from "../lib/Slide.svelte";
  import Background from "../assets/Slide-3-bg.png";
  import SlideTitleLight from "../lib/SlideTitleLight.svelte";
  import BuddyLogoLight from "../lib/BuddyLogoLight.svelte";
  import TeamMember from "../lib/TeamMember.svelte";
  import Ana from "../assets/profile/ana.png";
  import Fran from "../assets/profile/fran.png";
  import Flor from "../assets/profile/flor.png";
  import Bauti from "../assets/profile/bauti.png";
  import Fede from "../assets/profile/fede.png";
  import Andre from "../assets/profile/andre.png";
  import Agus from "../assets/profile/agus.png";
  import Diego from "../assets/profile/diego.png";
</script>

<Slide bgImage={Background}>
  <div class="flex flex-col justify-between h-[80vh]">
    <div class="flex justify-between items-start">
      <SlideTitleLight title={"¿Quién es Buddy?"} subtitle={"Nuestro equipo"} />
      <BuddyLogoLight />
    </div>
    <div class="grid grid-cols-4 grid-rows-2 gap-4">
      <TeamMember name={"Ana V. Faré Vergara"} img={Ana} />
      <TeamMember name={"Andrea F. Celtich"} img={Andre} />
      <TeamMember name={"Agustín Buset"} img={Agus} />
      <TeamMember name={"Francisco Arenas V."} img={Fran} />
      <TeamMember name={"M. Florencia Bird"} img={Flor} />
      <TeamMember name={"Diego Bari"} img={Diego} />
      <TeamMember name={"Federico Gelsi"} img={Fede} />
      <TeamMember name={"Juan Bautista Bianco L."} img={Bauti} />
    </div>
  </div>
</Slide>
