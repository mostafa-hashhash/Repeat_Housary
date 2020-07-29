<template>
  <div>
      <h3> {{ $t("aya.title") }} </h3>
      <p
        v-for="aya in $t('aya.content')"
        :key="aya"
      >
          ( {{aya}} )
      </p>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>