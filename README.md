# fabricjs-prodeasy-snappy-rect
Mastering Object Snapping in Fabric.js: Introducing the SnappyRect Class

## Using the SnappyRect Class

To utilize the SnappyRect class in your code, follow these steps:

### 1. Import the SnappyRect class:

```
import { SnappyRect } from "./fabric-smart-object.js";
```

### 2. Create an instance of SnappyRect 

by providing the necessary parameters, such as width, height, fill, top, and left:

```
var snappy = new SnappyRect({
  width: 150,
  height: 150,
  fill: "yellow",
  top: 10,
  left: 10
});
```

### 3. Add the SnappyRect object to the canvas:
```
canvas.add(snappy).renderAll();
```
With these steps, you have successfully added a SnappyRect object to your canvas. The SnappyRect class will handle the snapping functionality and provide smart guides to align and position the object accurately.
