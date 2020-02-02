# Pool

Pool game in JavaScript.

![alt screenshot](https://raw.githubusercontent.com/lrusso/Pool/master/Pool.png)

## Web:

https://lrusso.github.io/Pool/Pool.htm

## Using a new pool table image:

- Download or design a pool table image.
- Resize it proportionally and set a 416px height.
- Modify the imageTable variable. It is a image in Base64 format. Delete the original table image and paste the new one. DO NOT modify the image size. It must always be 800x600.
- Use the Debug Mode (set the Debug variable to true) to set the table limits (for the physics), to set each hole is located and how much space the table actually has is available.

**DETAIL 1:** You have to update the tableJSON variable. It has a JSON in Base64 format where you can set the table limits.
**DETAIL 2:** You have to update the placeRect variable. That rectangle must cover all the green/playable zone of the table. Must include a 15px padding. For example, if the width or height that you are setting is 600, use 585 instead. The same for the X and Y values.
