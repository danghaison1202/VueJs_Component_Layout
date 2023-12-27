<template>
    <div class="employee-list">
      <h2>Drinks Management</h2>
      <router-link to="/product/add">Add Drinks</router-link>
      <table class="table">
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">Drinks Name</th>
            <th scope="col">Drinks Type</th>
            <th scope="col">Price</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>Capuchino</td>
            <td>Coffee</td>
            <td>25.000 VND</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td>Peach Tea</td>
            <td>Tea</td>
            <td>30.000 VND</td>
          </tr>
          <tr>
            <th scope="row">3</th>
            <td>Freeze Chocolate </td>
            <td>Freeze</td>
            <td>40.000 VND</td>
          </tr>
        </tbody>
      </table>
    </div>
  </template>