<template>
  <div>
    <nav class="wrapper py-6">
      <div class="px-10 flex justify-between items-center">
        <div class="logo">
          <h1 class="text-2xl font-semibold text-gray-700">
            <a href="https://www.insp.com">INSP.COM</a>
          </h1>
        </div>
      </div>
    </nav>
  </div>
</template>


<script>
export default {
  components: {},

  data() {
    return {
      isOpen: false,
    };
  },

  methods: {
    toggle() {
      this.isOpen = !this.isOpen;
    },
  },
};
</script>

<style>
</style>