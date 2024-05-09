<template>
  <div class="content">
    <div class="container-custom">
      <div class="row-custom">
        <div class="col-80">
          <UserOverview />
          <Charts />
          <DocumentInfo />
        </div>
        <div class="col-20">
          <PopularProduct />
          <ChatUser />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import UserOverview from './UserOverview.vue'
import Charts from './Charts.vue'
import DocumentInfo from './DocumentInfo.vue'
import PopularProduct from './PopularProduct.vue'
import ChatUser from './ChatUser.vue'
export default {
  name: 'home',
  components: {
    UserOverview,
    Charts,
    DocumentInfo,
    PopularProduct,
    ChatUser
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
