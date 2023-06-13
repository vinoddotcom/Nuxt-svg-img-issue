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

  </div>
</template>
