<template>
  <div class="w-full">
    <div class="docs-group">
      <div class="group-two">
        <div class="pert-title">Document</div>
        <div class="pert-title-sub">Lorem Ipsum is simply dummy text</div>
      </div>
      <select id="cars" name="cars" class="select-custom">
        <option value="volvo">Weekly</option>
        <option value="saab">Weekly</option>
        <option value="fiat">Weekly</option>
        <option value="audi">Weekly</option>
      </select>
    </div>

    <table>
      <tr>
        <th>Name</th>
        <th>File</th>
        <th>Category</th>
        <th>Author</th>
        <th>Status</th>
      </tr>
      <tr>
        <td>Rahul paramanik</td>
        <td>PDF</td>
        <td>Property</td>
        <td>Sam kolay</td>
        <td><button class="btn-send">Send</button></td>
      </tr>
      <tr>
        <td>Rahul paramanik</td>
        <td>PDF</td>
        <td>Property</td>
        <td>Sam kolay</td>
        <td><button class="btn-send">Send</button></td>
      </tr>
      <tr>
        <td>Rahul paramanik</td>
        <td>PDF</td>
        <td>Property</td>
        <td>Sam kolay</td>
        <td><button class="btn-send">Send</button></td>
      </tr>
      <tr>
        <td>Rahul paramanik</td>
        <td>PDF</td>
        <td>Property</td>
        <td>Sam kolay</td>
        <td><button class="btn-send pending">Pending</button></td>
      </tr>
    </table>
  </div>
</template>

<style scoped>
table {
  font-family: arial, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

td,
th {
  border: 1px solid transparent;
  text-align: left;
  padding: 8px;
}

th {
  font-size: 16px;
  font-weight: bold;
  color: #000000;
}

tr:nth-child(even) {
  background-color: transparent;
}

.w-full {
  width: 100%;
}

.group-two {
  display: flex;
  flex-direction: column;
}

.pert-title {
  font-size: 16px;
  color: #000000;
  font-weight: bold;
  margin-bottom: 6px;
}

.pert-title-sub {
  font-size: 14px;
  color: #4e4d4d;
  font-weight: normal;
}
.docs-group {
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
}

.select-custom {
  border: 0px solid gray !important;
}
.btn-send {
  background-color: #d1ebda;
  border: none;
  padding: 5px;
  border-radius: 6px;
  -webkit-border-radius: 6px;
  -moz-border-radius: 6px;
  width: 90px;
  font-size: 14px;
  color: #2c2c2c;
  height: 35px;
}
.pending {
  background-color: #ffd9ca;
}
</style>
