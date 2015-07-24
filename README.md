
SAMPLE USAGE:
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
