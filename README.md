## Scalable Vector Graphics
---
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

