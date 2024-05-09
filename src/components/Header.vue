<template>
  <nav class="navbar">
    <div class="container-custom">
      <div class="hd-flex">
        <div class="navbar-title">Overview</div>
        <div class="select-menu">
          <img src="/images/1.jpg" alt="image" class="user-img" />
          <select id="cars" name="cars" class="select-custom">
            <option value="volvo">Administrator</option>
            <option value="saab">Profile</option>
            <option value="fiat">Settings</option>
            <option value="audi">Notification</option>
          </select>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>
.hd-flex {
  width: 100%;
  display: flex;
  justify-content: space-between;
  padding-top: 10px;
}
.hd-flex .navbar-title {
  font-size: 24px;
  color: #383838;
  font-weight: bold;
}

.select-menu {
  display: flex;
  align-items: center;
  justify-items: center;
}

.user-img {
  width: 25px;
  height: 25px;
  border-radius: 100%;
  -moz-border-radius: 100%;
  -webkit-border-radius: 100%;
  margin-right: 15px;
}
.select-custom {
  border: 0px solid gray !important;
}
</style>
