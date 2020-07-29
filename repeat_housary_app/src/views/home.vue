<template>
  <div>

    <br>
    
    <Aya />

    <SiderImage source="childrens.svg"/>

    <MainMenu />

  </div>
</template>

<script>

import Aya from "@/components/global/Aya"
import SiderImage from "@/components/global/SiderImage"
import MainMenu from "@/components/home/MainMenu"

export default {
    components: {
        Aya,
        SiderImage,
        MainMenu
    }
}
</script>

<style>

</style>