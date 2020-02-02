# Pool

Pool game in JavaScript.

![alt screenshot](https://raw.githubusercontent.com/lrusso/Pool/master/Pool.png)

## Web:

https://lrusso.github.io/Pool/Pool.htm

## Using a new pool table image:

- Download or design a pool table image.
- Resize it proportionally and set a 416px height.
- Modify the imageTable variable. It is a image in Base64 format. Delete the original table image and paste the new one. DO NOT modify the image size. It must always be 800x500.
- Use the Debug Mode (set the Debug variable to true) to set the table limits (for the physics), to set each hole is located and how much space the table actually has is available.

**DETAIL 1:** You have to update the tableJSON variable. It has a JSON in Base64 format where you can set the table limits.
**DETAIL 2:** You have to update the placeRect variable. That rectangle must cover all the green/playable zone of the table. Must include a 15px padding. For example, if the width or height that you are setting is 400, use 385 instead. The same for the X and Y values.

## Button Generator:

```
<style>
body
	{
	background-color:#001b07;
	}
.myButton
	{
	box-shadow:inset 0px 1px 0px 0px #9acc85;
	background:linear-gradient(to bottom, #74ad5a 5%, #68a54b 100%);
	background-color:#74ad5a;
	border-radius:5px;
	border:1px solid #3b6e22;
	display:inline-block;
	cursor:pointer;
	color:#ffffff;
	font-family:Arial;
	font-size:20px;
	font-weight:bold;
	padding:9px 12px;
	text-decoration:none;
	text-shadow:1px 1px 1px black;
	text-align:center;
	}
.myButton:hover
	{
	background:linear-gradient(to bottom, #68a54b 5%, #74ad5a 100%);
	background-color:#68a54b;
	}
.myButton:active
	{
	position:relative;
	top:1px;
	}
</style>
<a href="#" class="myButton">RESTART GAME</a><br/><br/>
<a href="#" class="myButton">INFO@LRUSSO.COM</a>
```
