<template>
  <div>
    <form>
      <input placeholder="What is your question?" />
    </form>
    <div class="gif-container">
    </div>
  </div>
</template>

<style>
body {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background:#18181E;
  color:white;
  padding:20px;
}

input{
  font-size:50px;
  font-family: inherit;
  background:none;
  border:none;
  outline:none;
  color:white;
  width:100%;
}

.gif-container img{
  margin-top:30px;
  min-width:600px;
}
</style>