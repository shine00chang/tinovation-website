<script>
  import Leaderboard from "$lib/components/Leaderboard.svelte";
</script>

<svelte:head>
  <title>{"Leaderboard - Tinovation"}</title>
  <meta property="og:title" content={"Leaderboard - Tinovation"} />
</svelte:head>

<div class="absolute -z-10 h-full w-full fill-purple-300">
  <div class="h-72 bg-purple-300" />

  <div class="fill-inherit">
    <svg
      width="100%"
      height="100%"
      viewBox="0 0 800 250"
      version="1.1"
      xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink"
      xml:space="preserve"
      style="fill-rule:evenodd;clip-rule:evenodd;stroke-linejoin:round;stroke-miterlimit:2;">
      <g transform="matrix(1,0,0,1.08017,-0.533333,-133.653)">
        <path
          d="M800.533,123.733L606.364,247.925L435.23,261.713L323.774,320.979L127.776,285.362L0.533,355.178L0.533,123.733" />
      </g>
    </svg>
  </div>
</div>

<div class="fixed -z-20 h-full min-h-screen w-full bg-retro-black" />

<div class="flex flex-row justify-center">
  <div class="mb-8 mt-20 flex w-full flex-col md:mt-24 md:w-auto">
    <Leaderboard />
  </div>
</div>
