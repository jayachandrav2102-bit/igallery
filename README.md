# Ex.08 Design of Interactive Image Gallery
## Date:

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
gallery.html

<!DOCTYPE html>
<html>
<head>
  <title>Gallery</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body style="margin:0;">
  <h1 style="text-align:center;background:#333;color:#fff;padding:1rem;">Gallery</h1>
  <div style="white-space:nowrap;overflow-x:auto;padding:1rem;">
    <img src="img1.jpg" style="height:200px;margin-right:10px;cursor:pointer" onclick="show(this)">
    <img src="img2.jpg" style="height:200px;margin-right:10px;cursor:pointer" onclick="show(this)">
    <img src="img3.jpg" style="height:200px;margin-right:10px;cursor:pointer" onclick="show(this)">
    <img src="img4.jpg" style="height:200px;margin-right:10px;cursor:pointer" onclick="show(this)">
   
  </div>
  <div id="m" style="display:none;position:fixed;top:0;left:0;width:100%;height:100%;background:#000c;z-index:1;">
    <span style="position:absolute;top:15px;right:35px;color:#fff;font-size:40px;cursor:pointer" onclick="m.style.display='none'">&times;</span>
    <img id="img" style="display:block;margin:5% auto;max-width:80%;">
  </div>
  <script>
    function show(el){img.src=el.src;m.style.display='block'}
  </script>
</body>
</html>
```
## OUTPUT:

![Screenshot_13-10-2025_14842_](https://github.com/user-attachments/assets/8e80b2ab-2b76-4e0c-ade8-e5d0ab64c02b)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
