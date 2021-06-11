    <div class="fl">

      <div class="a" style="--height:150;--c1w:100px;--c2w:60px;--top:-300;">
        <div class="cir1">
          <div class="cir2">
          </div>
        </div>
        <div class="bal">
        </div>
      </div>

      <div class="a s" style="--height:130;--c1w:140px;--c2w:100px;">
        <div class="cir1">
          <div class="cir2">
            <div class="cir3">
            </div>
          </div>
        </div>
      </div>

      <div class="a" style="--height:150;--c1w:100px;--c2w:60px;--top:-50;--left:-40">
        <div class="cir1">
          <div class="cir2">
          </div>
        </div>
        <div class="bal">
        </div>
      </div>

      <div>
        <style>
    body {
      background: #191210;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .fl {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      width: 300;
      position: absolute;
      bottom: 0;
    }
    .a {
      position: relative;
      top: var(--height);
      left: var(--left);
    }
    .cir1 {
      width: var(--c1w);
      height: var(--c1w);
      background: #eca03d;
      border-radius: 50%;
      z-index: 2;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .bal {
      z-index: 3;
      position: relative;
      top: var(--top);
      height: 250px;
      background: #191210;
    }
    .cir2 {
      width: var(--c2w);
      height: var(--c2w);
      background: #191210;
      border-radius: 50%;
      z-index: 3;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .cir3 {
      width: 50px;
      height: 50px;
      background: #84271c;
      border-radius: 50%;
      z-index: 3;
    }
    .s {
      position: absoulute;
      left: -20;
      z-index: 4;
    }

    </style>
