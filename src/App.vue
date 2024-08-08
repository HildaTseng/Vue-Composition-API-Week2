<script setup>

</script>

<template>
  <div class="container d-flex flex-column align-items-center">
    <h1 class="my-3 fs-3 text-center">2024 Vue 前端新手營 - Composition API - 第二週</h1>
    
    <div class="d-flex flex-column rounded from-card align-items-center">
      <h3 class="text-center p-2 rounded mt-2">註冊</h3>

      <div class="mb-3 w-75">
        <label for="emailInput" class="form-label text-white">電子信箱</label>
        <input type="email" class="form-control" id="emailInput" placeholder="name@gmail.com">
      </div>
      <div class="mb-3 w-75">
        <label for="passwordInput" class="form-label text-white">密碼</label>
        <input type="password" class="form-control" id="passwordInput" placeholder="請輸入6位數以上密碼">
      </div>
      <div class="mb-3 w-75">
        <label for="nicknameInput" class="form-label text-white">暱稱</label>
        <input type="text" class="form-control" id="nicknameInput" placeholder="請輸入暱稱">
      </div>

      <button type="button" class="mb-4 mt-3 border-0 w-75 submit-button">註冊</button>
    
    </div>

  </div>
</template>

<style lang="scss">
body {
  background-color: #cbe9e9;
}

h3 {
  // background-color: #7ca8a8;
  color: white;
  // width: 500px;
}

.from-card {
  width: 500px;
  background-color: #7ca8a8;
}

.submit-button {
  background-color: #327777; 
  border: 1px soild #327777;
  color: #fff;
  transition: background-color 0.3s;
  border-radius: 4px;
  padding: 6px 0;

  &:hover {
    background-color: #285f5f;
  }

  &:active {
    background-color: #1e4d4d;
  }

}


</style>
