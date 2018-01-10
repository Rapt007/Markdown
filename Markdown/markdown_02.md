# This is about my WDM project(Ping Pong) and this is the brief description of UI part and its code.
#### I need to work on two parts:
> * User Interface using HTML, CSS.
> * How it will interact using Javascript.

### 1. User Interface
This part is quite easy as I just need to work on UI and this can be easily built like:
```
<!-- Ping pong game UI-->
<!DOCTYPE html>
<html>
<head>
	<title>Ping Pong game- Project 1</title>
</head>
<body onload="" style="background-color: maroon">
<h1 style="color: yellow">Aman-Bassi(1001393217)</h1>
<h1 style="color:yellow">Ping Pong(Project 1)</h1>
<form>
	<input type="button" value="start"/>
	<input type="button" value="reset"/>
</br></br>
	<label>Slow</label>
	<input type="radio" name="slow" value="slow" id="1" checked="checked" onclick="" />
	<label>medium</label>
	<input type="radio" name="medium" value="medium" id="2" onclick="" />
	<label>Fast</label>
	<input type="radio" name="Fast" value="Fast" id="3" onclick="" />
	<label><b>Strikes:</b><span id="strike">0</span></label>
	<label><b>Max Score:</b><span id="max">0</span></label>
</br></br>
<div class="container" id="pong-court" style="border:solid black;cursor: none;width:1000px;height: 600px;border-right-style: dashed;">
<img src="ball.gif" id="ball" height="24px"  style="margin:0px;left:5px;top:200px;position: relative;" />
<img src="paddle.gif" id="paddle" style="margin:0px;position: relative;left:950px;
" />
</div>
</br>
</br>
```
In the above code I have just used radio button for **slow**, **medium** and **fast**.
Moreover, I have given them id and how they will respond when they will be clicked.

