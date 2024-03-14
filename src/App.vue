<script setup>
import Search from './components/Search.vue'
</script>

<template>
  <div class="contents">
    <div class="search-box">
      <Search />
    </div>
    <div class="result-box">
      <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
        Launch demo modal
      </button>
    </div>
  </div>

  <!-- Modal -->
  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-xl">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="exampleModalLabel">詳細</h1>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          ...
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.contents {
  width: 100%;
  height: 100%;
  background-color: #313031;
  border: 1px solid black;
  border-radius: 10px;
  display: flex;
}

.search-box {
  width: 300px;
  margin: 2.5px;
  border-radius: 5px 0 0 5px;
  padding: 0 10px 0 10px;
}

.result-box {
  flex: 1;
  background-color: #a3e2bd;
  margin: 2.5px;
  border-radius: 0 5px 5px 0;
}

.modal-body {
  height: 70vh;
}
</style>
