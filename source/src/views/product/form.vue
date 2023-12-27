<template>
  <div class="form">
    <h2>Drink Information Management</h2>
    <router-link to="/employee">Back</router-link>
    <form>
      <div class="row mb-3">
        <label  class="col-sm-2 col-form-label">Drinks Name</label>
        <div class="col-sm-10">
          <input type="text" class="form-control" />
        </div>
      </div>
      <div class="row mb-3">
        <label  class="col-sm-2 col-form-label">Drinks Type</label>
        <div class="col-sm-10">
          <input type="text" class="form-control"  />
        </div>
      </div>
      <div class="row mb-3">
        <label  class="col-sm-2 col-form-label">Price</label>
        <div class="col-sm-10">
          <input type="text" class="form-control"   />
        </div>
      </div>
      <!-- <fieldset class="row mb-3">
          <legend class="col-form-label col-sm-2 pt-0">Gender</legend>
          <div class="col-sm-10">
            <div class="form-check">
              <input class="form-check-input" type="radio" name="gridRadios" id="gridRadios1" value="option1" checked/>
              <label style="margin-left: -95%;" class="form-check-label" for="gridRadios1"> Male </label>
            </div>
            <div class="form-check">
              <input
                class="form-check-input"
                type="radio"
                name="gridRadios"
                id="gridRadios2"
                value="option2"
              />
              <label style="margin-left: -93.5%;" class="form-check-label" for="gridRadios2"> Female </label>
            </div>
          </div>
        </fieldset> -->

      <button type="submit" class="button-top">Submit</button>
    </form>
    <br>
    <div class="drinks-list">
      <h2>Drinks List</h2>
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
  </div>
</template>

