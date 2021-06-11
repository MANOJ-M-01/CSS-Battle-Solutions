    <div class="fl">

      <div class="a" style="--height:150;--bg:#AA445F;--bg2:#E38F66">
        <div class="cir1">
          <div class="cir2">
          </div>
        </div>
        <div class="bal">
        </div>
      </div>
      <div class="a" style="--height:50;--bg:#E38F66;--bg2:#AA445F">
        <div class="cir1">
          <div class="cir2">
          </div>
        </div>
        <div class="bal">
        </div>
      </div>

      <div class="a" style="--height:150;--bg:#AA445F;--bg2:#E38F66">
        <div class="cir1">
          <div class="cir2">
          </div>
        </div>
        <div class="bal">
        </div>
      </div>

      <div>
        <style>
          body{background:#62306D;display:flex;align-items:center;justify-content:center;}
          .fl{
            display:grid;
            grid-template-columns:1fr 1fr 1fr;
            width:300;
            position:absolute;
            bottom:0;

          }
          .a{  position:relative;
            top:var(--height);

          }
          .cir1{
            width:100px;
            height:100px;
            background:var(--bg);
            border-radius:50%;
            z-index:2;
            display:flex;align-items:center;justify-content:center;
          }
          .bal{
            z-index:-1;
            position:relative;
            top:-50;
            height:200px;
            background:#F7EC7D;
          }
          .cir2{
            width:60px;
            height:60px;
            background:var(--bg2);
            border-radius:50%;
            z-index:3;
          }
        </style>

