# Pool

Pool game in JavaScript.

![alt screenshot](https://raw.githubusercontent.com/lrusso/Pool/master/Pool.png)

## Web:

https://lrusso.github.io/Pool/Pool.htm

## Generating ball bitmap:

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
- Paste the image into the image stored in the imageBalls variable (in PoolGame.js) that has all the balls used in the game. The image is stored as base64, so you can copy and paste the content of the variable and paste it in your browser as a URL to see and download the image.
