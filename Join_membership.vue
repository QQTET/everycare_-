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
import JoinMembership from '@/components/join_membership.vue';


export default {
  components:{
      JoinMembership
  }
}
</script>

<style>

</style>