# d3-standalone
Version of the D3.js JavaScript library for visualizing data modified to run within the SVG format

See https://d3js.org for tutorials on D3.js

How to run example:
 - Git clone this repository
 - Open index.html in a web browser

---

This approach generates an SVG that links to the modified D3.js library, which is otherwise a fairly large (300kb+) javascript library. You can alternatively download the `d3.v5.min.js` file locally and link to it or even dump the entire contents into the SVG `data:` URI if you like, in the latter case you'll want to escape single quotes with `&quot;`.
