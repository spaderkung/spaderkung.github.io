# Shapes
## 2026-02-01 In progress

Something simple is often a good starting point. And sometimes something simple is just perfect. Making a computer generate something simple always feels like an achievement, and today I use the html canvas library p5.js to engulfe in some beautiful simple shapes. And colors. No disrespect to the primary colors, but anything slighlty off is so much prettier.

With p5 (and I believe html canvas as well) an rectangle is easily created. The colors are chosen from the _gruvbox_ theme with a dark grey background color `#1D2021` and a bluish foreground color `#83A598`.
```js
rect(width/2, height/2, width*0.6, height*0.6);
```
<p align="center"><img src="assets/rect_0.png" alt="drawing" width="80%"/></p>

Standard functions exists for changing the corner radius. This leaf has the greenish color `#689d6a` also from the gruvbox palette
```js
rect(width/2, height/2, width*0.6, height*0.6, width*0.3, 0, width*0.3, 0);
```
<p align="center"><img src="assets/rect corn.png" alt="drawing" width="80%"/></p>
