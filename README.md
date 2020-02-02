# Pool

Pool game in JavaScript.

![alt screenshot](https://raw.githubusercontent.com/lrusso/Pool/master/Pool.png)

## Web:

https://lrusso.github.io/Pool/Pool.htm

## Using a new pool table:

- Download or design any pool table image.
- Resize it proportionally and set a 416px height.
- Use the Debug Mode (set the Debug variable to true) to set the table limits (for the physics), to set each hole is located and how much space the table actually has is available.
**DETAIL 1:** You have to update the tableJSON variable. It has a JSON in Base64 format where you can set the table limits.
**DETAIL 2:** You have to update the placeRect variable. It must have a 15px padding.

## Using new balls:

- Use the following code in a new blank HTML file and use two colors (in the background css property) to generate the ball that you want:

```
<style>
.circle {
  border-radius: 50%;
  height: 300px;
  width: 300px;
  background: radial-gradient(circle at 100px 100px, white, gray);
}
</style>
<div class="circle"></div>
```
- Open that HTML file and take a screenshot of the window browser.
- Crop the ball from the screenshot (using GIMP or Photoshop).
- Add an alpha channel to delete the white background.
- Resize the cropped image to 26x26.
- Paste the image into the image stored in the imageBalls variable (in PoolGame.js) that has all the balls used in the game. The image is stored as Base64, so you can copy and paste the content of the variable and paste it in your browser as a URL to see and download the image.
