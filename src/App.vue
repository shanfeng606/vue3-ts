<template>
  <div>
    <div>
      导航栏|
      <router-link to="/">Frank</router-link>|
      <router-link to="/xxx">Frank2</router-link>
    </div>
    <hr />
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>
