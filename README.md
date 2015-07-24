# Uglify.js

This version is minified and compressed with bzip2 to client side self extracting/executing JavaScript in just 24KB! Other versions are 100KB to 250KB.

UglifyJS is a JavaScript compressor/minifier written in JavaScript. It also contains tools that allow one to automate working with JavaScript code:

* A parser which produces an abstract syntax tree (AST) from JavaScript code.
* A code generator which outputs JavaScript code from an AST, also providing the option to get a source map.
* A compressor (optimizer) — it uses the transformer API to optimize an AST into a smaller one.
* A mangler — reduce names of local variables to (usually) single-letters.
* A scope analyzer, which is a tool that augments the AST with information about where variables are defined/referenced etc.
* A tree walker — a simple API allowing you to do something on every node in the AST.
* A tree transformer — another API intended to transform the tree.

# Sample Usage:
```javascript
var code='\
function randomSite() {\n\
 var tempValue, website = new Array();\n\
 website[0] = "http://www.WHAK.com";\n\
 website[1] = "http://www.ScriptCompress.com";\n\
 website[2] = "http://www.Trollize.com";\n\
 website[3] = "http://www.Holy-Bibles.com";\n\
 website[4] = "http://www.Make-A-Meme.com";\n\
 tempValue = Math.floor(Math.random() * website.length);\n\
 return website[tempValue];\n}\n\
alert(randomSite());';

document.write("<pre>"+fugly(code)+"</pre>");
