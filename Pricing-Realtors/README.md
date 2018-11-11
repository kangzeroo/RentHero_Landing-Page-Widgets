# Template Widget
For some purpose

## Steps to Deploy
1. Host `index.html` on a secure https web address - currently `https://photoshoot.renthero.ca` <br/>
2. Load into your website or drag-and-drop builder as an `iframe` <br/>

```
  <!-- COPY THE BELOW -->
  <style>
  .price-wrap {
    width: 100vw !important;
    height: 100vh;
    padding: 0;
    overflow: hidden;
   }
   .price-frame {
    border: 0;
    width: 100vw !important;
    height: 100vh;
    overflow: hidden;
    -ms-transform: scale(0.80);
    -moz-transform: scale(0.80);
    -o-transform: scale(0.80);
    -webkit-transform: scale(0.80);
    transform: scale(0.80);

    -ms-transform-origin: 0 0;
    -moz-transform-origin: 0 0;
    -o-transform-origin: 0 0;
    -webkit-transform-origin: 0 0;
    transform-origin: 0 0;
   }
  </style>
  <div class="price-wrap">
   <iframe class="price-frame" src="https://velocity.renthero.ca" frameborder="0" max-width="90vw" ></iframe>
  </div>
```
