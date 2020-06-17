## Scalable Vector Graphics
---


#### dribbble
https://dribbble.com/

#### svg コード書き出し AdobeのIllustrator
```
// https://helpx.adobe.com/jp/illustrator/how-to/export-svg.html
<div class="icons-home">
  <a aria-label="Send email" href="mailto:{{site.email}}"><svg class="icon icon-email"><use xlink:href="#icon-email"></use></svg></a>
</div>
/*
<svg xmlns="http://www.w3.org/2000/svg" 
     xmlns:xlink="http://www.w3.org/1999/xlink">
  <textPath xlink:href="#icon-email">
</svg>
*/
/* svg コード書き出し AdobeのIllustrator icon-menu, icon-search, icon-email, icon-twitter...
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" display="none" version="1.1"><defs><symbol id="icon-menu" viewBox="0 0 1024 1024"><path class="path1" d="M128 213.333h768q17.667 0 30.167 12.5t12.5 30.167-12.5 30.167-30.167 12.5h-768q-17.667 0-30.167-12.5t-12.5-30.167 12.5-30.167 30.167-12.5zM128 725.333h768q17.667 0 30.167 12.5t12.5 30.167-12.5 30.167-30.167 12.5h-768q-17.667 0-30.167-12.5t-12.5-30.167 12.5-30.167 30.167-12.5zM128 469.333h768q17.667 0 30.167 12.5t12.5 30.167-12.5 30.167-30.167 12.5h-768q-17.667 0-30.167-12.5t-12.5-30.167 12.5-30.167 30.167-12.5z"/></symbol><symbol id="icon-search" viewBox="0 0 951 1024"><path class="path1" d="M658.286 475.429q0-105.714-75.143-180.857t-180.857-75.143-180.857 75.143-75.143 180.857 75.143 180.857 180.857 75.143 180.857-75.143 75.143-180.857zM950.857 950.857q0 29.714-21.714 51.429t-51.429 21.714q-30.857 0-51.429-21.714l-196-195.429q-102.286 70.857-228 70.857-81.714 0-156.286-31.714t-128.571-85.714-85.714-128.571-31.714-156.286 31.714-156.286 85.714-128.571 128.571-85.714 156.286-31.714 156.286 31.714 128.571 85.714 85.714 128.571 31.714 156.286q0 125.714-70.857 228l196 196q21.143 21.143 21.143 51.429z"/></symbol><symbol id="icon-email" viewBox="0 0 1024 1024"><path class="path1" d="M950.857 859.429v-438.857q-18.286 20.571-39.429 37.714-153.143 117.714-243.429 193.143-29.143 24.571-47.429 38.286t-49.429 27.714-58.571 14h-1.143q-27.429 0-58.571-14t-49.429-27.714-47.429-38.286q-90.286-75.429-243.429-193.143-21.143-17.143-39.429-37.714v438.857q0 7.429 5.429 12.857t12.857 5.429h841.143q7.429 0 12.857-5.429t5.429-12.857zM950.857 258.857v-14t-0.286-7.429-1.714-7.143-3.143-5.143-5.143-4.286-8-1.429h-841.143q-7.429 0-12.857 5.429t-5.429 12.857q0 96 84 162.286 110.286 86.857 229.143 181.143 3.429 2.857 20 16.857t26.286 21.429 25.429 18 28.857 15.714 24.571 5.143h1.143q11.429 0 24.571-5.143t28.857-15.714 25.429-18 26.286-21.429 20-16.857q118.857-94.286 229.143-181.143 30.857-24.571 57.429-66t26.571-75.143zM1024 237.714v621.714q0 37.714-26.857 64.571t-64.571 26.857h-841.143q-37.714 0-64.571-26.857t-26.857-64.571v-621.714q0-37.714 26.857-64.571t64.571-26.857h841.143q37.714 0 64.571 26.857t26.857 64.571z"/></symbol><symbol id="icon-close" viewBox="0 0 805 1024"><path class="path1" d="M741.714 755.429q0 22.857-16 38.857l-77.714 77.714q-16 16-38.857 16t-38.857-16l-168-168-168 168q-16 16-38.857 16t-38.857-16l-77.714-77.714q-16-16-16-38.857t16-38.857l168-168-168-168q-16-16-16-38.857t16-38.857l77.714-77.714q16-16 38.857-16t38.857 16l168 168 168-168q16-16 38.857-16t38.857 16l77.714 77.714q16 16 16 38.857t-16 38.857l-168 168 168 168q16 16 16 38.857z"/></symbol><symbol id="icon-twitter" viewBox="0 0 951 1024"><path class="path1" d="M925.714 233.143q-38.286 56-92.571 95.429 0.571 8 0.571 24 0 74.286-21.714 148.286t-66 142-105.429 120.286-147.429 83.429-184.571 31.143q-154.857 0-283.429-82.857 20 2.286 44.571 2.286 128.571 0 229.143-78.857-60-1.143-107.429-36.857t-65.143-91.143q18.857 2.857 34.857 2.857 24.571 0 48.571-6.286-64-13.143-106-63.714t-42-117.429v-2.286q38.857 21.714 83.429 23.429-37.714-25.143-60-65.714t-22.286-88q0-50.286 25.143-93.143 69.143 85.143 168.286 136.286t212.286 56.857q-4.571-21.714-4.571-42.286 0-76.571 54-130.571t130.571-54q80 0 134.857 58.286 62.286-12 117.143-44.571-21.143 65.714-81.143 101.714 53.143-5.714 106.286-28.571z"/></symbol><symbol id="icon-facebook" viewBox="0 0 585 1024"><path class="path1" d="M548 6.857v150.857h-89.714q-49.143 0-66.286 20.571t-17.143 61.714v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571q0-106.286 59.429-164.857t158.286-58.571q84 0 130.286 6.857z"/></symbol><symbol id="icon-rss" viewBox="0 0 805 1024"><path class="path1" d="M219.429 768q0 45.714-32 77.714t-77.714 32-77.714-32-32-77.714 32-77.714 77.714-32 77.714 32 32 77.714zM512 838.286q1.143 16-9.714 27.429-10.286 12-26.857 12h-77.143q-14.286 0-24.571-9.429t-11.429-23.714q-12.571-130.857-105.429-223.714t-223.714-105.429q-14.286-1.143-23.714-11.429t-9.429-24.571v-77.143q0-16.571 12-26.857 9.714-9.714 24.571-9.714h2.857q91.429 7.429 174.857 46t148 103.714q65.143 64.571 103.714 148t46 174.857zM804.571 839.429q1.143 15.429-10.286 26.857-10.286 11.429-26.286 11.429h-81.714q-14.857 0-25.429-10t-11.143-24.286q-6.857-122.857-57.714-233.429t-132.286-192-192-132.286-233.429-58.286q-14.286-0.571-24.286-11.143t-10-24.857v-81.714q0-16 11.429-26.286 10.286-10.286 25.143-10.286h1.714q149.714 7.429 286.571 68.571t243.143 168q106.857 106.286 168 243.143t68.571 286.571z"/></symbol><symbol id="icon-google-plus" viewBox="0 0 951 1024"><path class="path1" d="M420 454.857q0 20.571 18.286 40.286t44.286 38.857 51.714 42 44 59.429 18.286 81.143q0 51.429-27.429 98.857-41.143 69.714-120.571 102.571t-170.286 32.857q-75.429 0-140.857-23.714t-98-78.571q-21.143-34.286-21.143-74.857 0-46.286 25.429-85.714t67.714-65.714q74.857-46.857 230.857-57.143-18.286-24-27.143-42.286t-8.857-41.714q0-20.571 12-48.571-26.286 2.286-38.857 2.286-84.571 0-142.571-55.143t-58-139.714q0-46.857 20.571-90.857t56.571-74.857q44-37.714 104.286-56t124.286-18.286h238.857l-78.857 50.286h-74.857q42.286 36 64 76t21.714 91.429q0 41.143-14 74t-33.714 53.143-39.714 37.143-34 35.143-14 37.714zM336.571 400q21.714 0 44.571-9.429t37.714-24.857q30.286-32.571 30.286-90.857 0-33.143-9.714-71.429t-27.714-74-48.286-59.143-66.857-23.429q-24 0-47.143 11.143t-37.429 30q-26.857 33.714-26.857 91.429 0 26.286 5.714 55.714t18 58.857 29.714 52.857 42.857 38.286 55.143 14.857zM337.714 898.857q33.143 0 63.714-7.429t56.571-22.286 41.714-41.714 15.714-62.286q0-14.286-4-28t-8.286-24-15.429-23.714-16.857-20-22-19.714-20.857-16.571-23.714-17.143-20.857-14.857q-9.143-1.143-27.429-1.143-30.286 0-60 4t-61.429 14.286-55.429 26.286-39.143 42.571-15.429 60.286q0 40 20 70.571t52.286 47.429 68 25.143 72.857 8.286zM800.571 398.286h121.714v61.714h-121.714v125.143h-60v-125.143h-121.143v-61.714h121.143v-124h60v124z"/></symbol><symbol id="icon-angle-down" viewBox="0 0 658 1024"><path class="path1" d="M614.286 420.571q0 7.429-5.714 13.143l-266.286 266.286q-5.714 5.714-13.143 5.714t-13.143-5.714l-266.286-266.286q-5.714-5.714-5.714-13.143t5.714-13.143l28.571-28.571q5.714-5.714 13.143-5.714t13.143 5.714l224.571 224.571 224.571-224.571q5.714-5.714 13.143-5.714t13.143 5.714l28.571 28.571q5.714 5.714 5.714 13.143z"/></symbol><symbol id="icon-github-alt" viewBox="0 0 951 1024"><path class="path1" d="M365.714 694.857q0 22.857-7.143 46.857t-24.571 43.429-41.429 19.429-41.429-19.429-24.571-43.429-7.143-46.857 7.143-46.857 24.571-43.429 41.429-19.429 41.429 19.429 24.571 43.429 7.143 46.857zM731.429 694.857q0 22.857-7.143 46.857t-24.571 43.429-41.429 19.429-41.429-19.429-24.571-43.429-7.143-46.857 7.143-46.857 24.571-43.429 41.429-19.429 41.429 19.429 24.571 43.429 7.143 46.857zM822.857 694.857q0-68.571-39.429-116.571t-106.857-48q-23.429 0-111.429 12-40.571 6.286-89.714 6.286t-89.714-6.286q-86.857-12-111.429-12-67.429 0-106.857 48t-39.429 116.571q0 50.286 18.286 87.714t46.286 58.857 69.714 34.286 80 16.857 85.143 4h96q46.857 0 85.143-4t80-16.857 69.714-34.286 46.286-58.857 18.286-87.714zM950.857 594.286q0 118.286-34.857 189.143-21.714 44-60.286 76t-80.571 49.143-97.143 27.143-98 12.571-95.429 2.571q-44.571 0-81.143-1.714t-84.286-7.143-87.143-17.143-78.286-29.429-69.143-46.286-49.143-65.714q-35.429-70.286-35.429-189.143 0-135.429 77.714-226.286-15.429-46.857-15.429-97.143 0-66.286 29.143-124.571 61.714 0 108.571 22.571t108 70.571q84-20 176.571-20 84.571 0 160 18.286 60-46.857 106.857-69.143t108-22.286q29.143 58.286 29.143 124.571 0 49.714-15.429 96 77.714 91.429 77.714 227.429z"/></symbol></defs></svg>

*/
```



https://www.w3.org/Graphics/SVG/

.js
https://github.com/svgdotjs/svg.js

https://svgjs.com/docs/3.0/tutorials/

```js
var draw = SVG('drawing').size(300, 300)
var rect = draw.rect(100, 100).attr({ fill: '#f06' })

var draw = SVG('drawing').size('100%', '100%')

if(SVG.supported){
  var draw = SVG('drawing')
  var rect = draw.rect(100, 100)
} else {
  alert('SVG not supported')
}

SVG.on(document, 'DOMContentLoaded', function(){
  var draw = SVG('drawing')
})

var draw = SVG('drawing')
draw.rect(100, 100).move(100, 50).fill('#f06')

var draw = SVG('drawing')

var nested = draw.nested()
var rect = nested.rect(200, 200)

var group = draw.group()
group.path('M10, 20L30,40')

group.add(rect)

var symbol = draw.symbol()
symbol.rect(100, 100).fill('#09')
var use = draw.use(symbol).move(200, 200)

var des = draw.defs()

var defs = rect.doc().defs()

var link = draw.link('http://svgdot.js.github.io/')
var rect = link.rect(100, 100)

link.to('http://apple.com')
link.show('replace')
link.target('_blank')
rect.linkTo('http://svgdotjs.github.io/')

rect.linkTo(function(link){
  link.to('http://svgdotjs.github.io/').target('_blank')
})

```

