# 2016-homepage-slideshow
Slideshow at the bottom of the homepage

https://medillcherubs.github.io/2016-homepage-slideshow/

Paste this into your Wordpress post:

```
<div id="homepage-slideshow"></div>
<script> var pymParent = new pym.Parent("homepage-slideshow", "//medillcherubs.github.io/2016-homepage-slideshow/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2016-homepage-slideshow/edit/gh-pages/index.html -->
```

Paste this into the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script> <script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script> <script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```
