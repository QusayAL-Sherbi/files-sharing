<template>
  <aside>
    <div class="add-class">
      <p>
        Lorem ipsum dolor sit, amet <br>
        consectetur adipisicing elit. Error?
      </p>
      <button class="btn btn-success">Add Class</button>
    </div>
    <div class="filters">
      <h5>Lorem, ipsum dolor.</h5>
      <label class="mt-3" for="class">Lorem, ipsum.</label>
      <select class="d-block w-100 p-1" name="class" id="class">
        <option value="Lorem, ipsum dolor.">Lorem, ipsum dolor.</option>
      </select>
      <label class="mt-3" for="class">Lorem, ipsum.</label>
      <select class="d-block w-100 p-1" name="class" id="class">
        <option value="Lorem, ipsum dolor.">Lorem, ipsum dolor.</option>
      </select>
      <label class="mt-3" for="class">Lorem, ipsum.</label>
      <select class="d-block w-100 p-1" name="class" id="class">
        <option value="Lorem, ipsum dolor.">Lorem, ipsum dolor.</option>
      </select>
      <br>
      <h5>Lorem ipsum dolor sit.</h5>
      <input type="checkbox" name="option-one" id="option-one">
      <label for="option-one">Option One</label>
      <br>
      <input type="checkbox" name="option-one" id="option-one">
      <label for="option-two">Option Two</label>
      <br>
      <input type="checkbox" name="option-one" id="option-one">
      <label for="option-Three">Option Three</label>
      <br>
      <input type="checkbox" name="option-one" id="option-one">
      <label for="option-four">Option Four</label>
    </div>
  </aside>
</template>

<script>
export default {
  name: 'Sidebar'
}
</script>

<style>
  aside {
    background-color: #fff;
    text-align: center;
    border-radius: 0.25rem;
  }

  aside .add-class {
    background-color: #e2e2e2;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  aside .add-class p {
    text-align: left;
  }

  aside .filters {
    text-align: left;
    padding: 20px 15px;
  }
</style>