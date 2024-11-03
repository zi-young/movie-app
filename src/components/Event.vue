<template>
      <div class="event">
         <p>{{text}}</p>
      </div>
</template>
   
<script>
   export default {
      name: "EventComponent",
      props: {
         text: String,
      }
   }
</script>
   
<style>
   .event {
      background: #444;
      padding: 10px 20px;
      color: #fff;
      text-align: center;
      font-size: small;
      vertical-align: middle;
   }
   .event  p{
      margin: 0;
   }
</style>