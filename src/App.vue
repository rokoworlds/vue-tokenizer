<script>

</script>

<template>
  <h1 class="title">tokenizer.</h1>

  <!-- control panel -->

<div>
  <hr>
  <p>control panel.</p>
  <button>Add random user</button>
  <div class="flex col">
    <label for="username">name</label>
    <input type="text" name="username" placeholder="user name">
    <label for="usermail">email</label>
    <input type="text" name="usermail" placeholder="user's mail">
    <label for="userphone">phone</label>
    <input type="text" name="userphone" placeholder="user's phone number">
    <label for="userwebsite">website</label>
    <input type="text" name="userwebsite" placeholder="user's website">
  </div>
</div>
<div>
  <hr>
  <div class="gap">
    <p>add token:</p>
    <button>name</button>
    <button>email</button>
    <button>phone</button>
    <button>website</button>
  </div>
  <br>
  <label for="letter">enter yout text.</label>
  <br>
  <textarea name="letter" id="" cols="50" rows="10"></textarea>

</div>

<div>
  <hr>
  <button>get from localStorage</button>
  <button>add to localStorage</button>
</div>

<div>
  <br>
  <label for="letter">your letter.</label>
  <br>
  <textarea name="letter" id="" cols="50" rows="10"></textarea>
</div>

</template>

<style>
body {
  background-color: #333;
  color: #fffdf5;
  font-family: monospace;
  
}

.title {
  letter-spacing: 5px;
}

.flex {
  display: flex;
}


.col {
  flex-direction: column;
}


/* blue - #5d70d0 */
/* red - #d05d5d */
/* yellow - #e0c24d */
</style>
