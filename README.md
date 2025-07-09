# phyton2
<!DOCTYPE html>
<html>
<body>

<canvas id="myCanvas" width="400" height="400" style="border:1px solid #d3d3d3;">
Your browser does not support the HTML canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");

for (let i = 50; i < 400; i += 50){

	ctx.moveTo(i,0);
	ctx.lineTo(i,400);
    
    ctx.moveTo(0,i);
	ctx.lineTo(400,i);
    }
ctx.stroke();
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<canvas id="myCanvas" width="300" height="300" style="border:1px solid #d3d3d3;">
Your browser does not support the HTML canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.moveTo(100,0);
ctx.lineTo(100,300);

ctx.moveTo(200,0);
ctx.lineTo(200,300);

ctx.moveTo(0,100);
ctx.lineTo(300,100);

ctx.moveTo(0,200);
ctx.lineTo(300,200);

ctx.stroke();
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript For Loop</h2>

<p id="demo"></p>

<script>
let text = "";

for (let i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}

document.getElementById("demo").innerHTML = text;
</script>

</body>
</html>
