<template>
  <!-- footer -->
  <footer
    class="flex items-center h-12 mt-5 text-sm bg-gray-100 dark:bg-[#171d30] py-2 z-10 w-full"
  >
    <div class="flex flex-1">
      &copy;&nbsp;
      {{ new Date().getFullYear() }}&nbsp;
      Made With&nbsp;
      <img src="../../assets/images/heart.svg" />&nbsp;
      By&nbsp;
      <a
        class="link link-primary no-underline"
        href="https://ping.pub"
        target="_blank"
        rel="noopener noreferrer"
        >Ping.pub</a
      >
    </div>
    <div
      class="hidden md:!block"
    >
      <a
        class="link link-primary no-underline mr-4"
        href="https://coinhunterstr.com/"
        target="noopener noreferrer"
        >CoinHunters</a
      >
      <a
        class="link link-primary no-underline"
        href="https://nodes.coinhunterstr.com/"
        target="noopener noreferrer"
        >CoinHunters Nodes</a
      >
    </div>
  </footer>
</template>
