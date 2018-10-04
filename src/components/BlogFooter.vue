<template>
  <transition appear name="v--mask">
    <footer v-once class="blog__footer">
      <socials></socials>
    </footer>
  </transition>
</template>

<script>
	import Socials from './Socials.vue';
	export default { name: 'blog-footer', components: {'socials': Socials} };
</script>
