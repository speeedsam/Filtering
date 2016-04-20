# Filtering - CSS3 Filter Effects
Filtering - is simple hover effects created with CSS filters. CSS3 filters are currently supported in WebKit nightlies. Hence, the walkthrough only uses the -webkit prefix for applying the filter effects.
<hr>
<h3>Where is one of:</h3>
<ul>
    <li>blur()</li>
    <li>grayscale()</li>
    <li>brightness() </li>
    <li>saturate()</li>
    <li>contrast() </li>
    <li>invert()</li>
    <li>sepia()</li>
    <li>hue-rotate() </li>
    <li>opacity()</li>
</ul>
<style type="text/css">
    .prose-diff>.markdown-body pre {
    padding: 10px 20px;
    background: #000;
    color: #E5442E;
}
</style>
<section>
<p> 1. CSS3 Filter Blur Effects</p>
<a href="http://codepen.io/speeedsam/pen/mPKMJJ">Live Demo & Code Editor</a><br>
<h3>HTML MARKUP</h3>
```
<div class="blur box">
    <a href="#">
        <img src="images.jpg" alt="Image">
    </a>
</div>
```
<h3>CSS Filter Functions</h3>
```
.blur img {
    -webkit-filter: blur(2px);
}
```
</section>
<hr>

<section>
<p>2. CSS3 Filter Grayscale Effects</p>
<a href="http://codepen.io/speeedsam/pen/MyXvKV ">Live Demo & Code Editor</a><br>
<h3>HTML MARKUP</h3>
```
<div class="grayscale box">
    <a href="#">
        <img src="images.jpg" alt="Image">
    </a>
</div>
```
<h3>CSS Filter Functions</h3>
```
.grayscale img {
    -webkit-filter: grayscale(100%);
}
```
</section>
<hr>

<section>
<p>3.CSS3 Filter Brightness Effects</p>
<a href="http://codepen.io/speeedsam/pen/zqadBM">Live Demo & Code Editor</a><br>
<h3>HTML MARKUP</h3>
```
<div class="brightness box">
    <a href="#">
        <img src="images.jpg" alt="Image">
    </a>
</div>
```
<h3>CSS Filter Functions</h3>
```
.brightness img {
    -webkit-filter: brightness(55%);
}
```
</section>
<hr>


<section>
<p>4.CSS3 Filter Saturate Effects</p>
<a href="http://codepen.io/speeedsam/pen/oxyezK">Live Demo & Code Editor</a><br>
<h3>HTML MARKUP</h3>
```
<div class="saturate box">
    <a href="#">
        <img src="images.jpg" alt="Image">
    </a>
</div>
```
<h3>CSS Filter Functions</h3>
```
.saturate img {
    -webkit-filter: saturate(10);
}
```
</section>
<hr>


<section>
<p>5. CSS3 Filter Contrast Effects</p>
<a href="http://codepen.io/speeedsam/pen/mPKMRV">Live Demo & Code Editor</a><br>
<h3>HTML MARKUP</h3>
```
<div class="contrast box">
    <a href="#">
        <img src="images.jpg" alt="Image">
    </a>
</div>
```
<h3>CSS Filter Functions</h3>
```
.contrast img {
    -webkit-filter: contrast(160%);
}
```
</section>
<hr>


<section>
<p>6.CSS3 Filter Invert Effects</p>
<a href="http://codepen.io/speeedsam/pen/zqadZy">Live Demo & Code Editor</a><br>
<h3>HTML MARKUP</h3>
```
<div class="invert box">
    <a href="#">
        <img src="images.jpg" alt="Image">
    </a>
</div>
```
<h3>CSS Filter Functions</h3>
```
.invert img {
    -webkit-filter: invert(65%);
}
```
</section>
<hr>


<section>
<p>7.CSS3 Filter Sepia Effects</p>
<a href="http://codepen.io/speeedsam/pen/wGXqed">Live Demo & Code Editor</a><br>
<h3>HTML MARKUP</h3>
```
<div class="sepia box">
    <a href="#">
        <img src="images.jpg" alt="Image">
    </a>
</div>
```
<h3>CSS Filter Functions</h3>
```
.sepia img {
    -webkit-filter: sepia(100%);
}
```
</section>
<hr>


<section>
<p>8.CSS3 Filter Huerotate Effects</p>
<a href="http://codepen.io/speeedsam/pen/LNrjrE">Live Demo & Code Editor</a><br>
<h3>HTML MARKUP</h3>
```
<div class="huerotate box">
    <a href="#">
        <img src="images.jpg" alt="Image">
    </a>
</div>
```
<h3>CSS Filter Functions</h3>
```
.huerotate img {
    -webkit-filter: hue-rotate(180deg);
}
```
</section>
<hr>


<section>
<p>9.CSS3 Filter Opacity Effects</p>
<a href="http://codepen.io/speeedsam/pen/BKVdJZ">Live Demo & Code Editor</a><br>
<h3>HTML MARKUP</h3>
```
<div class="opacity box">
    <a href="#">
        <img src="images.jpg" alt="Image">
    </a>
</div>
```
<h3>CSS Filter Functions</h3>
```
.opacity img {
    -webkit-filter: opacity(50%);
}
```
</section>
<hr>
<h3>Browser Support</h3>
<table class="browser-support-table" border="1"  cellpadding="10">
<thead>
<tr>
<th class="chrome"><span>Chrome</span></th>
<th class="safari"><span>Safari</span></th>
<th class="firefox"><span>Firefox</span></th>
<th class="opera"><span>Opera</span></th>
<th class="ie"><span>IE</span></th>
<th class="android"><span>Android</span></th>
<th class="iOS"><span>iOS</span></th>
</tr>
</thead>
<tbody>
<tr>
<td class="yep" data-browser-name="Chrome">31+ <small>(-webkit-)</small></td>
<td class="yep" data-browser-name="Safari">7+ <small>(-webkit-)</small></td>
<td class="yep" data-browser-name="Firefox">35+</td>
<td class="yep" data-browser-name="Opera">18+ <small>(-webkit-)</small></td>
<td class="nope" data-browser-name="IE">nope</td>
<td class="yep" data-browser-name="Android">4.4+ <small>(-webkit-)</small></td>
<td class="yep" data-browser-name="iOS">6+ <small>(-webkit-)</small></td>
</tr>
</tbody>
</table>
