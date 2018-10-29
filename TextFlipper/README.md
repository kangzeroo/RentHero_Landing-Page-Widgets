# Template Widget
For some purpose

## Steps to Deploy
1. Host `index.html` on a secure https web address - In this case `https://myrenthelper.com` <br/>
2. Load into your website or drag-and-drop builder as an `iframe` <br/>

```
  <!-- COPY THE BELOW -->
  <!-- Codepen: https://codepen.io/yemon/pen/pWoROm?editors=1100 -->
  <style>
  .rottie_wrap {
    width: 90vw;
    height: 30vh;
    padding: 0;
    overflow: hidden;
   }
   .rottie_frame {
    border: 0;
    width: 550px;
    -ms-transform: scale(0.90);
    -moz-transform: scale(0.90);
    -o-transform: scale(0.90);
    -webkit-transform: scale(0.90);
    transform: scale(0.90);

    -ms-transform-origin: 0 0;
    -moz-transform-origin: 0 0;
    -o-transform-origin: 0 0;
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
   }
  </style>
  <div class="rottie_wrap">
   <iframe class="rottie_frame" src="https://myrenthelper.com" width="100%" height="250px" frameborder="0" ></iframe>
  </div>
```
