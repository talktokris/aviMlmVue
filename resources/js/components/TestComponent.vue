<script>

const Kris= ["one", "two", "three", "Four"];

export default {

    data() {
    return {
      message: Kris,
      isRed: true,
      color: 'green'
    }
  }
}
</script>

<template lang="">
    <div>
       {{ message[0]}}
    </div>
</template>




<style lang="">
    
</style>