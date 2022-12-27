## #5 Acid Rain

[Link to the problem](https://cssbattle.dev/play/5)

```
<div class="wrapper">
  <div class="c c-1"></div>
  <div class="c c-2"></div>
  <div class="c c-3"></div>
</div>
<style>
body{
  background:#0B2429;
}
  .wrapper{
    display:flex;
    height:240px;
    margin:30px auto;

  }
  .c{
    width:120px;
    height:120px;
    background:#F3AC3C;
    border-radius:50%;
    border-top-right-radius:0;
    margin-left:-50px;
  }
  .c-1{
    align-self:flex-end;
/*     margin-left:72px; */
    z-index:3;
    margin-left:70px;
  }
  .c-2{
    align-self:center;
    background:#998235;
    z-index:2;

  }
  .c-3{
/*     border-top-right-radius:50% */
    transform:rotate(180deg)
  }
</style>


```
