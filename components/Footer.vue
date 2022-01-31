<template>
  <nav
    class="
      w-full
      flex
      justify-between
      items-center
      text-center
      p-5
      space-x-4
      bg-yellow-500
      font-semibold
      fixed
      bottom-0
      overflow-scroll
    "
  >
    <div>
      <NuxtLink to="/cervezas">
        <a>Cervezas</a>
      </NuxtLink>
    </div>
    <div>
      <NuxtLink to="/cocteles-cerveza">
        <a>Cócteles Cerveza</a>
      </NuxtLink>
    </div>
    <div>
      <NuxtLink to="/cocteles">
        <a>Cócteles</a>
      </NuxtLink>
    </div>
    <div>
      <NuxtLink to="/licores">
        <a>Licores</a>
      </NuxtLink>
    </div>
    <div>
      <NuxtLink to="/bebidas">
        <a>Bebidas</a>
      </NuxtLink>
    </div>
    <div>
      <NuxtLink to="/para-compartir">
        <a>Para Compartir</a>
      </NuxtLink>
    </div>
    <div>
      <NuxtLink to="/para-uno">
        <a>Para 1 Persona</a>
      </NuxtLink>
    </div>
    <div>
      <NuxtLink to="/snacks">
        <a>Snacks</a>
      </NuxtLink>
    </div>
  </nav>
</template>

<script>
export default {};
</script>