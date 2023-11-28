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
        title={"Un compromiso social"}
        subtitle={"Modelo de negocio"}
      />
      <BuddyLogoDark />
    </div>
    <div class="flex justify-center items-center grow">
      <div class="grid grid-cols-2 grid-rows-2 gap-8 grow">
        <DataCard footer={"INSITUTUCIONES EDUCATIVAS"}>
          <div class="rounded-full bg-[#F3F9EB] w-min p-4">
            <svg
              width="48"
              height="48"
              viewBox="0 0 94 95"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M46.9999 25.0933V75.777M46.9999 25.0933C42.4466 22.0682 36.2646 20.209 29.4555 20.209C22.6464 20.209 16.4645 22.0682 11.9111 25.0933V75.777C16.4645 72.7519 22.6464 70.8927 29.4555 70.8927C36.2646 70.8927 42.4466 72.7519 46.9999 75.777M46.9999 25.0933C51.5532 22.0682 57.7351 20.209 64.5443 20.209C71.3534 20.209 77.5353 22.0682 82.0886 25.0933V75.777C77.5353 72.7519 71.3534 70.8927 64.5443 70.8927C57.7351 70.8927 51.5532 72.7519 46.9999 75.777"
                stroke="#628A2C"
                stroke-width="4.68"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
        </DataCard>
        <DataCard footer={"INSTITUCIONES DE SALUD"}>
          <div class="rounded-full bg-[#F3F9EB] w-min p-4">
            <svg
              width="48"
              height="48"
              viewBox="0 0 94 95"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M46.9996 16.3105V78.6905M78.1896 47.5005L15.8096 47.5005"
                stroke="#628A2C"
                stroke-width="4.68"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
        </DataCard>
        <DataCard footer={"INSTITUCIONES PÚBLICAS"}>
          <div class="rounded-full bg-[#F3F9EB] w-min p-4">
            <svg
              width="48"
              height="48"
              viewBox="0 0 94 95"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M31.4049 55.2945V66.9907M46.9999 55.2945V66.9907M62.5949 55.2945V66.9907M11.9111 82.5857H82.0886M11.9111 39.6995H82.0886M11.9111 28.0032L46.9999 12.4082L82.0886 28.0032M15.8099 39.6995H78.1899V82.5857H15.8099V39.6995Z"
                stroke="#628A2C"
                stroke-width="4.68"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>
          </div>
        </DataCard>
        <DataCard footer={"PADRES Y TUTORES"}>
          <div class="rounded-full bg-[#F3F9EB] w-min p-4">
            <svg
              width="48"
              height="48"
              viewBox="0 0 94 95"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M46.9999 17.6878C49.8575 14.4502 54.0383 12.4082 58.6961 12.4082C67.309 12.4082 74.2911 19.3903 74.2911 28.0032C74.2911 36.6161 67.309 43.5982 58.6961 43.5982C54.0383 43.5982 49.8575 41.5562 46.9999 38.3186M58.6961 82.5857H11.9111V78.687C11.9111 65.7676 22.3843 55.2945 35.3036 55.2945C48.223 55.2945 58.6961 65.7676 58.6961 78.687V82.5857ZM58.6961 82.5857H82.0886V78.687C82.0886 65.7676 71.6155 55.2945 58.6961 55.2945C54.4353 55.2945 50.4406 56.4336 46.9999 58.424M50.8986 28.0032C50.8986 36.6161 43.9165 43.5982 35.3036 43.5982C26.6908 43.5982 19.7086 36.6161 19.7086 28.0032C19.7086 19.3903 26.6908 12.4082 35.3036 12.4082C43.9165 12.4082 50.8986 19.3903 50.8986 28.0032Z"
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
