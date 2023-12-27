<template>
  <div class="employee-list">
    <h2>Employee Management</h2>
    <router-link to="/employee/add">Add Employee</router-link>
    <table class="table">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">First name</th>
          <th scope="col">Last name</th>
          <th scope="col">Gender</th>
          <th scope="col">Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">1</th>
          <td>Mark</td>
          <td>Otto</td>
          <td>Male</td>
          <td>mark@gmail.com</td>
        </tr>
        <tr>
          <th scope="row">2</th>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>Male</td>
          <td>jacob@gmail.com</td>
        </tr>
        <tr>
          <th scope="row">3</th>
          <td>Larry</td>
          <td>Bird</td>
          <td>Male</td>
          <td>larry@gmail.com</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>