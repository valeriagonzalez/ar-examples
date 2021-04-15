<!-- Navigation Bar -->
    <nav>
        <div class="nav-title">
            <span class="Icon Icon--logo Icon--large"></span>

            <!-- Link in web -->
            <a class="home-link" href="{{ .Site.BaseURL }}">Twitter Open Source</a>

            <!-- Text in mobile -->
            <p class="home-text">Twitter Open Source</p>
            <span id="caret" class="Icon Icon--caretDown"></span>
        </div>
        <ul class="nav-menu">
            <!-- This link only exists in mobile -->
            <li id="extra-mobile-link" class="nav-list-item">
                <a class="nav-link" href="{{ .Site.BaseURL }}">Twitter Open Source</a>
            </li>

            <li class="nav-list-item">
                <a class="nav-link" href="{{ "projects" | relURL }}">Projects</a>
            </li>

            <li class="nav-list-item">
                <a class="nav-link" href="{{ "memberships" | relURL }}">#Squad</a>
            </li>

            <li class="nav-list-item">
              <a class="nav-link" href="{{ "year-in-review" | relURL }}">Year in Review</a>
            </li>

            <li class="nav-list-item">
                <a class="nav-link" href="https://blog.twitter.com/engineering/en_us/topics/open-source.html" target="_blank">Blog</a>
            </li>

            <li class="nav-list-item list-end">
                <a class="nav-link" href="https://github.com/twitter" target="_blank">GitHub</a>
            </li>
        </ul>
    </nav>


<!-- Header -->

<div class="header home-header">
    <div class="Grid container">
        <div id="header-text" class="Grid-cell u-size7of8">
            <h1 class="subheading">
                <a href="https://twitter.com/TwitterOSS" target="_blank">@TwitterOSS</a>
            </h1>
            <h1 class="large-title">Open Source is Happening</h1>
        </div>
    </div>
</div>

## Bienvenidos a WebAR

Se usa la librería [AR.js](https://ar-js-org.github.io/AR.js-Docs/#import-the-library) para integrar AR a la web.


```markdown
<!-- AR.js by @jerome_etienne - github: https://github.com/jeromeetienne/ar.js - info: https://medium.com/arjs/augmented-reality-in-10-lines-of-html-4e193ea9fdbf -->
<script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
<script src="https://cdn.rawgit.com/jeromeetienne/AR.js/1.6.0/aframe/build/aframe-ar.js"></script>
<body style='margin : 0px; overflow: hidden;'>
	<a-scene embedded arjs='sourceType: webcam;'>
		<a-box position='0 0.5 0' color='green' material='opacity: 0.5;'></a-box>
		<a-marker-camera preset='hiro'></a-marker-camera>
	</a-scene>
</body>
```
