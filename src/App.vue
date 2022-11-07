<template>
    <div>
      <myheader/>
      <mylist/>
    </div>
</template>

<script>
import myheader from "./components/myheader.vue"
import mylist from "./components/mylist.vue"
export default {
  name: 'App',
  components: {
        myheader,
        mylist    
  }
}
</script>


