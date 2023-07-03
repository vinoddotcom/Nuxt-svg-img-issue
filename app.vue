<template>
  <div>
    <h3>Nuxt Image</h3>
    <nuxt-img
      :src="'/fighter.svg'"
      alt="Exam Path finder"
      format="svg"
      fetchpriority="low"
      loading="lazy"
      decoding="async"
      width="100"
      height="100"
    />
  <p></p>
  <h3>With img tag</h3>
  <img
    :src="'/fighter.svg'"
    alt="Exam Path finder"
    format="svg"
    fetchpriority="low"
    loading="lazy"
    decoding="async"
    width="109"
    height="40"
  />
  <nuxt-img
      :src="'https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/NewTux.svg/500px-NewTux.svg.png?20081002211004'"
      alt="Exam Path finder"
      format="svg"
      fetchpriority="low"
      loading="lazy"
      decoding="async"
      width="100"
      height="100"
    />
    <img
      :src="'https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/NewTux.svg/500px-NewTux.svg.png?20081002211004'"
      alt="Exam Path finder"
      format="svg"
      fetchpriority="low"
      loading="lazy"
      decoding="async"
      width="100"
      height="100"
    />

  </div>
</template>

