<template>
  <div class="wrapper">
    <div class="sidebar">
      <sidebar></sidebar>
    </div>
    <div class="main-panel">
      <Header></Header>
      <RouterView />
      <Footer></Footer>
    </div>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Sidebar from '@/components/Sidebar.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Sidebar,
    Footer
  },
  data() {
    return {
      isOpen: false
    }
  },
  methods: {
    toggleDropDown() {
      this.isOpen = !this.isOpen
      this.$emit('change', this.isOpen)
    },
    closeDropDown() {
      this.isOpen = false
      this.$emit('change', this.isOpen)
    }
  }
}
</script>
<style scoped>
.dropdown .dropdown-toggle {
  cursor: pointer;
}
</style>
