## Read 12 Notes

Links: 

[Chart.js docs](http://www.chartjs.org/docs/)
[Basic usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
[Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
[Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
[Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)


Code to Reference and be familiar with

```
<!DOCTYPE html>
<html>
 <head>
  <meta charset="utf-8"/>

  <script type="application/javascript">
    function draw() {
      var canvas = document.getElementById('canvas');
      if (canvas.getContext) {
        var ctx = canvas.getContext('2d');

        ctx.fillStyle = 'rgb(200, 0, 0)';
        ctx.fillRect(10, 10, 50, 50);

        ctx.fillStyle = 'rgba(0, 0, 200, 0.5)';
        ctx.fillRect(30, 30, 50, 50);
      }
    }
  </script>
 </head>

 <body onload="draw();">
   <canvas id="canvas" width="150" height="150"></canvas>
 </body>

</html>
```


fillRect(x, y, width, height)  
Draws a filled rectangle.

strokeRect(x, y, width, height)
Draws a rectangular outline.

clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.


### Paths

beginPath()  
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.

Path methods  
Methods to set different paths for objects.

closePath()  
Adds a straight line to the path, going to the start of the current sub-path.

stroke()  
Draws the shape by stroking its outline.

fill()  
Draws a solid shape by filling the path's content area.

moveTo(x, y)  
Moves the pen to the coordinates specified by x and y.

lineTo(x, y)
Draws a line from the current drawing position to the position specified by x and y.

arc(x, y, radius, startAngle, endAngle, anticlockwise)  
Draws an arc which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction indicated by anticlockwise (defaulting to clockwise).

arcTo(x1, y1, x2, y2, radius)  
Draws an arc with the given control points and radius, connected to the previous point by a straight line.
