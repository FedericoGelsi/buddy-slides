<script>
  import Slide from "../lib/Slide.svelte";
  import Background from "../assets/buddy-bg.png";
  import DataCard from "../lib/DataCard.svelte";
  import SlideTitleDark from "../lib/SlideTitleDark.svelte";
  import BuddyLogoDark from "../lib/BuddyLogoDark.svelte";
</script>

<Slide bgImage={Background}>
  <div class="flex flex-col h-full py-16">
    <div class="flex justify-between items-start">
      <SlideTitleDark
        title={"¿Cómo es buddy?"}
        subtitle={"Nuestra propuesta"}
      />
      <BuddyLogoDark />
    </div>
    <div class="flex justify-center items-center grow">
      <div class="grid grid-cols-2 grid-rows-2 gap-8 grow">
        <DataCard footer={"JUEGO DE SIMULACIÓN"}>
          <div class="rounded-full bg-[#F3F9EB] w-min p-4">
            <svg
              width="48"
              height="48"
              viewBox="0 0 94 95"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M43.103 16.3113C43.103 12.0048 46.5941 8.51367 50.9006 8.51367C55.2071 8.51367 58.6982 12.0048 58.6982 16.3113V20.2101C58.6982 22.3634 60.4437 24.1089 62.597 24.1089H74.2934C76.4467 24.1089 78.1922 25.8545 78.1922 28.0077V39.7041C78.1922 41.8574 76.4467 43.603 74.2934 43.603H70.3946C66.0881 43.603 62.597 47.0941 62.597 51.4006C62.597 55.7071 66.0881 59.1982 70.3946 59.1982H74.2934C76.4467 59.1982 78.1922 60.9437 78.1922 63.097V74.7934C78.1922 76.9467 76.4467 78.6922 74.2934 78.6922H62.597C60.4437 78.6922 58.6982 76.9467 58.6982 74.7934V70.8946C58.6982 66.5881 55.2071 63.097 50.9006 63.097C46.5941 63.097 43.103 66.5881 43.103 70.8946V74.7934C43.103 76.9467 41.3574 78.6922 39.2041 78.6922H27.5077C25.3545 78.6922 23.6089 76.9467 23.6089 74.7934V63.097C23.6089 60.9437 21.8634 59.1982 19.7101 59.1982H15.8113C11.5048 59.1982 8.01367 55.7071 8.01367 51.4006C8.01367 47.0941 11.5048 43.603 15.8113 43.603H19.7101C21.8634 43.603 23.6089 41.8574 23.6089 39.7041V28.0077C23.6089 25.8545 25.3545 24.1089 27.5077 24.1089H39.2041C41.3574 24.1089 43.103 22.3634 43.103 20.2101V16.3113Z"
                stroke="#628A2C"
                stroke-width="4.67857"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
        </DataCard>
        <DataCard footer={"IDENTIKIT"}>
          <div class="rounded-full bg-[#F3F9EB] w-min p-4">
            <svg
              width="48"
              height="48"
              viewBox="0 0 94 95"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M82.0877 82.5877L58.6952 59.1952M66.4927 39.7014C66.4927 54.7739 54.2739 66.9927 39.2014 66.9927C24.1289 66.9927 11.9102 54.7739 11.9102 39.7014C11.9102 24.6289 24.1289 12.4102 39.2014 12.4102C54.2739 12.4102 66.4927 24.6289 66.4927 39.7014Z"
                stroke="#628A2C"
                stroke-width="4.68"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
        </DataCard>
        <DataCard footer={"FORMULARIO PARA CUIDADORES"}>
          <div class="rounded-full bg-[#F3F9EB] w-min p-4">
            <svg
              width="48"
              height="48"
              viewBox="0 0 94 95"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M35.304 20.2077H27.5065C23.2 20.2077 19.709 23.6987 19.709 28.0052V74.7902C19.709 79.0966 23.2 82.5877 27.5065 82.5877H66.494C70.8004 82.5877 74.2915 79.0966 74.2915 74.7902V28.0052C74.2915 23.6987 70.8004 20.2077 66.494 20.2077H58.6965M35.304 20.2077C35.304 24.5141 38.795 28.0052 43.1015 28.0052H50.899C55.2054 28.0052 58.6965 24.5141 58.6965 20.2077M35.304 20.2077C35.304 15.9012 38.795 12.4102 43.1015 12.4102H50.899C55.2054 12.4102 58.6965 15.9012 58.6965 20.2077M47.0002 47.4989H58.6965M47.0002 63.0939H58.6965M35.304 47.4989H35.343M35.304 63.0939H35.343"
                stroke="#628A2C"
                stroke-width="4.68"
                stroke-linecap="round"
              />
            </svg>
          </div>
        </DataCard>
        <DataCard footer={"INFORME DE PROGRESO"}>
          <div class="rounded-full bg-[#F3F9EB] w-min p-4">
            <svg
              width="48"
              height="48"
              viewBox="0 0 94 95"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M43.1002 12.627C25.556 14.5664 11.9102 29.4404 11.9102 47.5015C11.9102 66.8805 27.6199 82.5903 46.9989 82.5903C65.0601 82.5903 79.9341 68.9445 81.8735 51.4003H43.1002V12.627Z"
                stroke="#628A2C"
                stroke-width="4.68"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M80.0908 35.8053H58.6952V14.4101C68.665 17.9339 76.5668 25.8356 80.0908 35.8053Z"
                stroke="#628A2C"
                stroke-width="4.68"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
        </DataCard>
      </div>
    </div>
  </div>
</Slide>
