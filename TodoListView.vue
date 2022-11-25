<template>
<div class="TodoListView">
<h1>TO DO LIST</h1>

<p>welcome to your my do listAPP</p>

  <p>please fill in your details</p>
  
<form action="https://formsubmit.co/giftgichuhi4138@gmail.com" method="POST">
<label name="date">date
<input type="date" required name="date">
</label>

<label name="location">location
<input  required name="location">
</label>

<label name="task">task
<input  required name="task">
</label>

<label name="people">people
<input  required name="people">
</label>
<label name="submit">submit
<input type="submit" required name="submit">
</label>
</form>
</div>
</template>

<style scoped>
h1{
    text-align:center;
}
div{
  color:red;
}
</style>

<script>
  
  export default{
    name: "TodoListView",
    
  };
</script>