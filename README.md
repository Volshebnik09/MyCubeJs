# MyCubeJs
 Animated cube on the background
 
## Setup

html code

```html
<body>
    <div class="cube-plate">
        <div class="cube">
            <!-- There a cube-sides -->
            <div class="cube-side> 
            Bla bla bla
            </div>
            <div class="cube-side> 
            Bla bla bla
            </div>
            <div class="cube-side> 
            Bla bla bla
            </div>
            <div class="cube-side> 
            Bla bla bla
            </div>
            <div class="cube-side> 
            Bla bla bla
            </div>
            <div class="cube-side> 
            Bla bla bla
            </div>
        </div>
    </div>
</body>
```

Connect css

```css
body {
    overflow-x: hidden;
}
.cube-plate{
    width:100%;   
    height: 100vh;
    position: relative;
}
.cube-side{
    border: 3px solid black;
    backface-visibility: hidden;
}
```
position style is important
backface-visibility: hidden or visible try

Ok. let's connect js.

```js
<script src=".../cube.js"></script>
<scrpit>
buildCube(height,posX,posY,
speedRotationX,speedRotationY,speedRotationZ,
rotateStartX,rotateStartY,rotateStartZ);
</script>
```

## arguments
+ height - does not have a default value
+ posX, posY - in default place cube in center
+ speedRotationX,speedRotationY,speedRotationZ - in default 0
+ rotateStartX,rotateStartY,rotateStartZ - in default 0

## More

html code

```html
<scrpit>
clip = false 
<!-- Dragging a cube with the mouse -->
</scrpit>
```

