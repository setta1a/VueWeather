<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body id="app">
    <div class="informer-container"></div>
</body>
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<script>
"use strict";
export default{
  name: 'FirstComponent',
  data(){
    return {text: 'Я новый компонент!'}
  }
}


</script>
<style>
    .informer-container {
        display: flex;
        align-items: flex-start;
        justify-content: space-between;
        flex-wrap: wrap;
        width: 400px;
        min-height: 255px;
        padding: 30px;
        background-image: url('img/forest.png');
        background-size: cover;
        background-position: center center;
        border-radius: 20px;
        box-shadow: 0px 0px 10px 0px rgba(50, 50, 50, 0.75);
    }
</style>
</html>