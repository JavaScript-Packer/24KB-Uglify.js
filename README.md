
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
 website[5] = "http://www.BoobSigns.com";\n\
 website[6] = "http://www.SeekFreak.com";\n\
 website[7] = "http://www.Is-A-Jerk.com";\n\
 website[8] = "http://www.HolyBibleVerse.com";\n\
 website[9] = "http://www.HolyBibleSearch.com";\n\
 website[10] = "http://www.SirSeek.com";\n\
 website[11] = "http://www.TXT2PIC.com";\n\
 website[12] = "http://www.13KG.com";\n\
 website[13] = "http://www.Nerdful.com";\n\
 website[14] = "http://www.FanSignGenerator.com";\n\
 website[15] = "http://www.Holy-Bibles.org";\n\
 website[16] = "http://www.VirtualHolyBible.com";\n\
 website[17] = "http://www.BibleThumper.net";\n\
 tempValue = Math.floor(Math.random() * website.length);\n\
 return website[tempValue];\n}\n\
alert(randomSite());';

document.write("<pre>"+fugly(code)+"</pre>");
