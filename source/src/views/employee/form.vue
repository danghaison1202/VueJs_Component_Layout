<template>
  <div class="form">
    <h2>Employee Information Management</h2>
    <router-link to="/employee">Back</router-link>
    <form>
      <div class="row mb-3">
        <label for="inputPassword3" class="col-sm-2 col-form-label">First Name</label>
        <div class="col-sm-10">
          <input type="text" class="form-control" id="inputPassword3" />
        </div>
      </div>
      <div class="row mb-3">
        <label for="inputPassword3" class="col-sm-2 col-form-label">Last Name</label>
        <div class="col-sm-10">
          <input type="text" class="form-control" id="inputPassword3" />
        </div>
      </div>
      <div class="row mb-3">
        <label for="inputEmail3" class="col-sm-2 col-form-label">Email</label>
        <div class="col-sm-10">
          <input type="email" class="form-control" id="inputEmail3" />
        </div>
      </div>
      <fieldset class="row mb-3">
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
      </fieldset>

      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </div>
</template>