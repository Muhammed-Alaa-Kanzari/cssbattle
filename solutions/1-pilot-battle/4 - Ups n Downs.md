## #4 - Ups n Downs

[Link to the problem](https://cssbattle.dev/play/4)

```
<div class="wrapper">
  <div class="box1"></div>
  <div class="box2"></div>
  <div class="box3"></div>
</div>

<style>
  body{
    background:#62306D;
  }
  .wrapper{
    height:200px;
    display:flex;
    justify-content:center;
    margin-top:50px;
  }
  div[class^="box"]{
    background:#F7EC7D;
    height: 100px;
    width: 100px;
    border-radius:50% 50% 0 0;
  }
  .box1,.box3{
    align-self:flex-end;
    transform:rotate(180deg)
  }

</style>
```
