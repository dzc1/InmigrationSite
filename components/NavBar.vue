<template>
  <nav
    class="
      flex
      justify-between
      items-center
      p-4
      bg-blue-600
      overflow-hidden
      min-h-full
      sticky
      top-0
    "
  >
    <a class="text-3xl font-semibold leading-none" href="#">
      <nuxt-link class="text-md text-blue-600 hover:text-blue-800" to="/"
        ><img
          src="https://res.cloudinary.com/dnsnkrcru/image/upload/v1629322682/BarcelonaBars/easyapply/easy-expat_bouw77.svg"
          alt="EasyXpat"
          width="NaN" /></nuxt-link
    ></a>
    <div class="lg:hidden">
      <button
        class="
          navbar-burger
          flex=
          items-center
          py-2
          px-3
          text-blue-600
          hover:text-blue-700
          rounded
          border border-blue-200
          hover:border-blue-300
        "
      >
        <svg
          class="fill-current h-4 w-4"
          viewBox="0 0 20 20"
          xmlns="http://www.w3.org/2000/svg"
        >
          <title>Mobile menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
        </svg>
      </button>
    </div>
    <ul class="hidden lg:flex lg:items-center lg:w-auto lg:space-x-12">
      <li>
        <nuxt-link class="text-md text-white hover:text-gray-200" to="/about"
          >About</nuxt-link
        >
      </li>
      <li>
        <a class="text-md text-white hover:text-gray-200" href="#">Guides</a>
      </li>
      <li>
        <nuxt-link
          class="text-md text-white hover:text-gray-200"
          to="/resources"
          >Resources</nuxt-link
        >
      </li>
    </ul>
    <div class="hidden lg:block">
      <a
        class="
          inline-block
          px-4
          py-3
          text-xs
          font-semibold
          leading-none
          bg-white
          hover:bg-gray-200
          text-blue-600
          rounded
        "
        href="#"
        >Login</a
      >
    </div>
  </nav>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
</style>