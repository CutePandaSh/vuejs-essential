<template>
  <div class="navbar-right">
    <div class="nav navbar-nav github-login">
      <a href="#" class="btn btn-default login-btn">
        <i class="fa fa-user"> 登 录 </i>
      </a>
      <router-link to="/auth/register" class="btn btn-default login-btn">
        <i class="fa fa-user-plus"> 注 册 </i>
      </router-link>

    </div>
  </div>
</template>

<script>
  export default {
    name: 'TheEntry'
  }
</script>

<style scoped>

</style>
