#---https://www.youtube.com/@ghostyex---
 
Tutorial on ^^^^^
 
 code Fullscreen button
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
<center>
<button onclick="openGame()" > Play in Fullscreen </button>
<script>
function openGame() {
	var win = window.open ()
	var url = "https://science246.github.io/SlopeHD/"
	var iframe = win.document.createElement('iframe')
	iframe.style.width = "100%"
	iframe.style.height = "100%"
	iframe.style.border = "none"
	iframe.src = url
	win.document.body.appendChild(iframe)
}
</script>
</center>
 
~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
(update log)
 
added the <center> part to the code so you don't have to fiddle around with the sizing 
 
---------------------------------------
