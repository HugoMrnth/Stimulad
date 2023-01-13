<template>
{{ JSON.stringify(discussion) }}

</template>

<script>
import { onMounted } from 'vue';
import csv from '../../discussion.csv'
export default {
  name: 'HomeVue',
}


onMounted(
  console.log(csv)
)


</script>
<style scoped>
</style>
