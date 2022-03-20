<template>
  <div>
<div class="row">
	<Navbar />
</div>
<div class="row">
<div class="col-2">
	<Sidebar />
</div>
<div class="col-10">
<Notice />
</div>
</div>
</div>
</template>

<script>
import MyInformation from '@/components/my_information.vue';


export default {
  components:{
      MyInformation
  }
}
</script>

<style>

</style>