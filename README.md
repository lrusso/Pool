# Pool

Pool game in JavaScript.

![alt screenshot](https://raw.githubusercontent.com/lrusso/Pool/master/Pool.png)

## Web:

https://lrusso.github.io/Pool/Pool.htm

## Using a new pool table image:

- Download or design a pool table image.
- Resize it proportionally and set a 416px height.
- Modify the imageTable variable. It has an image in Base64 format. Delete the original table image and paste the new one. DO NOT modify the image size. It must always be a 800x416 image.
- Enable the Debug Mode (by setting the showDebug variable as true).
- Update the tableJSON variable. It has JSON data in Base64 format where you can set the table limits/borders and where each hole is located.
- Update the placeRect variable. It is a rectangle that must cover all the green/playable zone with a 15px padding.
- Disable the Debug Mode (by setting the showDebug variable as false).
