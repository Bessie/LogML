# Initial Plan

To get started understanding the necessary XML and XSLT details I'll start with the most simple case - truth table semantics.

This is in theory simple since the aim would be to define some XML elements and then the XSLT needed to turn that into an HTML table.

Some target XML for this might be:

    <tt>
    <variables values='2' 1='T' 2='F'>
    <var>P<val>T</val><value>F</value></var>
    <var>Q<value>T</value><value>F</value><value>T</value><value>F</value></variable>
    </variables>
    <operator type='and'>∨ <val>T</val></operator>
    </tt>
    
    <semanticProof>
    </semanticProof>


some code for later:

<!DOCTYPE html>
<html>
<body>

<canvas id="myCanvas" width="200" height="100" >
Your browser does not support the HTML canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.moveTo(100,0);
ctx.lineTo(200,100);
ctx.stroke();
ctx.moveTo(100,0);
ctx.lineTo(0,100);
ctx.stroke();
</script>

</body>
</html>
