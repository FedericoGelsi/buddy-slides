<script>
  export let header = "";
  export let footer;
</script>

<div
  class="card bg-[#2A4B62] rounded-xl flex flex-col justify-center items-center gap-4 p-4"
>
  <div class="card-header text-[#D0D0D0] font-bold text-xl">
    {header}
  </div>
  <div class="card-body">
    <slot />
  </div>
  <div class="card-footer text-[#D0D0D0] font-bold text-xl">
    {footer}
  </div>
</div>
