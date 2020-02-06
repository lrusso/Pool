# Pool

Pool game in JavaScript.

![alt screenshot](https://raw.githubusercontent.com/lrusso/Pool/master/Pool.png)

## Web:

https://lrusso.github.io/Pool/Pool.htm

## Using a new pool table image:

- Download or design a pool table image.
- Resize it proportionally and set a 416px height.
- Modify the imageTable variable. It has an image in Base64 format. Delete the original table image and paste the new one. DO NOT modify the image size. It must always be a 800x416 image.
- Use the Debug Mode (set the Debug variable as true) to set the table limits/borders (for the physics), to set where the holes are located and how much available space the table actually has.

**DETAIL 1:** You have to update the tableJSON variable. It has JSON data in Base64 format where you can set the table limits/borders.

**DETAIL 2:** You have to update the placeRect variable. That rectangle must cover all the green/playable zone of the table with a 15px padding.

**DETAIL 3:** This process can be done only by initially activating the Debug mode. Otherwise you won't see the table limits/borders that you are setting.
