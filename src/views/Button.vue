<template>
    <div class="button">
        <h1>This is an Button </h1>
        <ExButton />
    </div>
</template>
<script>
// @ is an alias to /src
import ExButton from '@/components/ExButton.vue'
export default {
  name: 'home',
  components: {
    ExButton
  }
}

</script>
