<template>
  <main>
    <nav style="--bs-breadcrumb-divider: '>';" aria-label="breadcrumb">
      <ol class="breadcrumb mb-0">
        <li class="breadcrumb-item"><a href="#">Home</a></li>
        <li class="breadcrumb-item active" aria-current="page">Library</li>
      </ol>
    </nav>
    <div class="folders">
      <div class="row">
        <div class="col-lg-3">
          <i class="bi bi-folder-fill" style="font-size: 3rem;"></i>
        </div>
        <div class="col-lg-3">
          <i class="bi bi-folder-fill" style="font-size: 3rem;"></i>
        </div>
        <div class="col-lg-3">
          <i class="bi bi-folder-fill" style="font-size: 3rem;"></i>
        </div>
        <div class="col-lg-3">
          <i class="bi bi-folder-fill" style="font-size: 3rem;"></i>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "MainSection",
};
</script>

<style>
  main {
    border-radius: 0.25rem;
    min-height: 530px;
    background-color: #FFF;
    
  }

  main nav {
    background-color: #e2e2e2;
    padding: 10px 15px;
  }

  .folders .row > div {
    padding: 20px;
  }
</style>
