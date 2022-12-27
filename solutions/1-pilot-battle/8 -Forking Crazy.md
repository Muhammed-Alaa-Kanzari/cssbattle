## #8 Forking Crazy

[Link to the problem](https://cssbattle.dev/play/8)

```
<div class="wrapper">
  <div class="stick"></div>
  <div class="body"></div>
  <div class="claw-wrapper">
    <div class="claw"></div>
    <div class="claw  reverse"></div>
    <div class="claw "></div>
    <div class="claw reverse"></div>
    <div class="claw "></div>
    <div class="claw reverse"></div>
    <div class="claw "></div>
  </div>
</div>
<style>
  *{margin:0}
  body{
    background:#6592CF;
    display:flex;
    justify-content:center;
    align-items:flex-end;
  }
  .wrapper{
    height:250px;
    width:140px;
    position:relative;
  }
  div:not(.wrapper):not(.claw-wrapper){
    background:#060F55;
  }
    .body{
    width:140px;
    height:100px;
    position:absolute;
    bottom:50.9px;
    border-bottom-left-radius:69px;
    border-bottom-right-radius:69px;

  }
  .stick{
    width:20px;
    height:52px;
    position:absolute;
    bottom:0;
    left:43%;
  }
.claw-wrapper {
    width: 140px;
    height: 110px;
    display: flex;
    justify-content: space-between;
  }
  .claw {
    width: 20px;
    border-top-left-radius: 20px;
    border-top-right-radius: 20px;
  }
  .claw.reverse {
/*     transform: scaleY(-1); */
      transform: rotate(180deg);
    background: #6592CF !important;
  }
</style>

```
