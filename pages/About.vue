<template>
  <div>
    <h1>About page</h1>
    <NuxtLink to="/">Home</NuxtLink>
  </div>
</template>
<script>
import auth from '~/middleware/auth';

export default {
  middleware: [auth]
}
</script>
