## Bienvenidos a WebAR

Se usa la librería [AR.js](https://ar-js-org.github.io/AR.js-Docs/#import-the-library) para integrar AR a la web.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
<!-- AR.js by @jerome_etienne - github: https://github.com/jeromeetienne/ar.js - info: https://medium.com/arjs/augmented-reality-in-10-lines-of-html-4e193ea9fdbf -->
<script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
<script src="https://cdn.rawgit.com/jeromeetienne/AR.js/1.6.0/aframe/build/aframe-ar.js"></script>
<body style='margin : 0px; overflow: hidden;'>
	<a-scene embedded arjs='sourceType: webcam;'>
		<a-box position='0 0.5 0' material='opacity: 0.5;'></a-box>
		<a-marker-camera preset='hiro'></a-marker-camera>
	</a-scene>
</body>

