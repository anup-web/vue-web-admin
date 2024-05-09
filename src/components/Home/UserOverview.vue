<template>
  <div class="doc-section w-full">
    <div class="row-custom">
      <div class="col-30">
        <div class="group-one">
          <div class="docu-title">Docuument</div>
          <div class="icon-round">
            <i class="fa-regular fa-file"></i>
          </div>
        </div>
      </div>
      <div class="col-30">
        <div class="group-one">
          <div class="docu-title">Contact</div>
          <div class="icon-round">
            <i class="fa-regular fa-address-book"></i>
          </div>
        </div>
      </div>
      <div class="col-30">
        <div class="group-one">
          <div class="docu-title">Email</div>
          <div class="icon-round">
            <i class="fa-regular fa-envelope"></i>
          </div>
        </div>
      </div>
    </div>

    <div class="row-custom mt-40">
      <div class="col-30">
        <div class="group-two">
          <div class="pert-title">146.000</div>
          <div class="pert-title-sub">
            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
          </div>
        </div>
      </div>
      <div class="col-30">
        <div class="group-two">
          <div class="pert-title">14000</div>
          <div class="pert-title-sub">
            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
          </div>
        </div>
      </div>
      <div class="col-30">
        <div class="group-two">
          <div class="pert-title">146.580</div>
          <div class="pert-title-sub">
            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.col-30 {
  -ms-flex: 0 0 33%;
  flex: 0 0 33%;
  max-width: 33%;
}

.col-30 {
  position: relative;
  width: 100%;
  min-height: 1px;
  padding-right: 15px;
  padding-left: 15px;
}
.group-one {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.docu-title {
  font-size: 16px;
  color: #000000;
  font-weight: normal;
}
.icon-round {
  width: 40px;
  height: 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #d7d7d7;
  border-radius: 100%;
  -webkit-border-radius: 100%;
  -moz-border-radius: 100%;
}
.icon-round i {
  font-size: 20px;
}

.w-full {
  width: 100%;
}

.group-two {
  display: flex;
  flex-direction: column;
}
.mt-40 {
  margin-top: 30px;
}
.pert-title {
  font-size: 20px;
  color: #000000;
  font-weight: bold;
  margin-bottom: 10px;
}

.pert-title-sub {
  font-size: 14px;
  color: #4e4d4d;
  font-weight: normal;
  line-height: 17px;
}
</style>
