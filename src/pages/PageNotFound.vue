<template>
  <div class="col-full" :class="$style.centered">
    <h1 :class="$style.headingLarge">Not Found</h1>
    <p :class="$style.textLarge">Oops, we couldn't find what you ae looking for. Why don't you
      <router-link :to="{name: 'Home'}">
        go home instead?
      </router-link>
    </p>
  </div>
</template>

<script>
  export default {

  }
</script>

<style module>
.headingLarge {
  font-size: 100px;
  font-weight: 400;
}
.textLarge {
  font-size: 40px;
  font-weight: 100;
}
.centered {
  text-align: center;
}
</style>
