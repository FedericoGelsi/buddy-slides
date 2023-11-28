<script>
  export let name;
  export let img;
</script>

<div class="flex flex-col justify-center items-center">
  <img
    src={img}
    alt={name}
    class="rounded-full border-4 border-[#0C969D] w-32 h-32"
  />
  <p class="text-bold text-[#2C2C2E] text-[1.5rem] m-0">{name}</p>
</div>
