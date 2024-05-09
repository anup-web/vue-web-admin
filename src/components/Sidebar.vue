<template>
  <div class="sidebar-wrapper">
    <div class="logo">
      <a href="#" class="simple-text"> CRM.io </a>
    </div>
    <div class="dashboard">Dashboard</div>

    <div class="management">Management</div>
    <ul class="nav">
      <li class="nav-item active">
        <a href="#" class="nav-link">Document</a>
      </li>
      <li class="nav-item">
        <a href="#" class="nav-link">Contact</a>
      </li>
      <li class="nav-item">
        <a href="#" class="nav-link">Prospect</a>
      </li>
      <li class="nav-item">
        <a href="#" class="nav-link">Workflow</a>
      </li>
    </ul>

    <div class="management mt-20">Connection</div>
    <ul class="nav">
      <li class="nav-item active">
        <a href="#" class="nav-link">Chat Integration</a>
      </li>
      <li class="nav-item">
        <a href="#" class="nav-link">Marketing Automation</a>
      </li>
      <li class="nav-item">
        <a href="#" class="nav-link">Email Integration</a>
      </li>
    </ul>

    <div class="management mt-20">Customer</div>
    <ul class="nav bbottom-zero">
      <li class="nav-item active">
        <a href="#" class="nav-link">Transaction</a>
      </li>
      <li class="nav-item">
        <a href="#" class="nav-link">Maintenance</a>
      </li>
    </ul>
  </div>
</template>

<style scoped>
.sidebar .logo {
  padding: 10px 5px;
  margin: 0 20px;
  border-bottom: 1px solid hsla(0, 0%, 100%, 0.2);
  position: relative;
  z-index: 4;
}

.sidebar .logo a {
  color: #fe8d7e;
  font-size: 25px;
  text-decoration: none;
  font-weight: bold;
}

.dashboard {
  background-color: #3963ad;
  margin: 20px 20px;
  padding: 15px 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 10px;
  font-size: 18px;
  color: #ffffff;
}
.management {
  color: #1f3765;
  margin: 0px 20px;
  font-size: 16px;
}

.sidebar .nav {
  padding: 20px 0px;
  float: none;
  display: block;
  margin: 0px 20px;
  border-bottom: 2px solid hsla(0, 0%, 100%, 0.2);
}

.nav .nav-item {
  float: none;
  padding: 10px 0px;
}

.nav .nav-item .nav-link {
  color: #465f82;
  font-size: 15px;
  font-weight: normal;
  float: none;
}
.mt-20 {
  margin-top: 20px;
}

.bbottom-zero {
  border: 0px !important;
}
</style>
