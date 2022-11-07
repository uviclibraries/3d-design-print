---
layout: default
title: 5-Heart Shaped Box
nav_order: 7
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---
<img src="images/tinkercad-box-01.png" style="float:right;width:200px" alt="heart box measurements"> 

# Heart-Shaped Box Activity

1. Open up [TinkerCad](https://www.tinkercad.com/){:target="_blank"}, create an account or log-in. Open a new design. 

2. Make a heart:
- Grab a **Heart** from the **Basic Shapes** panel on the right and drag it onto the workplane.
- Resize the heart so that its length and width are both **80mm** by dragging the white square handles on the base and top of the heart (or by clicking on one of the white square handles and entering “**80**” in the fields). 
- Change the height of the heart to **30mm** by clicking on the handle in the middle of the heart. 
<button onclick="toggle('gif1')">Show/Hide Animation</button>
    <div id="gif1">
    <img src="images/tinkercad-box-02.gif" >
    </div>

3. Make a second heart: <img src="images/tinkercad-box-03.png" style="float:right;width:200px" alt="small black cones to drag"> 
- Duplicate the heart by clicking **Duplicate** at the top-left of the screen or by clicking **Ctrl + D**.
- Resize the heart so that its length and width are both **70mm** by dragging the white square handles on the base and top of the heart (or by clicking on one of the white square handles and entering “**70**” in the fields). 
- Raise this heart **2mm** from the workplane by dragging the small black “cone” on the top of the heart upwards.
<button onclick="toggle('gif2')">Show/Hide Animation</button>
    <div id="gif2">
    <img src="images/tinkercad-box-04.gif" >
    </div>

4. Make a copy for the lid:
- Select both hearts by holding down the Shift key and clicking them. 
- Click on **Duplicate** and drag the new hearts to a clear area on the workplane.
- There should now be four hearts on the workplane.
<button onclick="toggle('gif3')">Show/Hide Animation</button>
    <div id="gif3">
    <img src="images/tinkercad-box-05.gif" >
    </div>

5. Make the box out of one set of hearts: <img src="images/tinkercad-box-06.png" style="float:right;width:150px;height:80px" alt="solid vs hole icons"> 
- Make the smaller heart a hole by changing the **Shape** from **Solid** to **Hole** at the top-right of the screen.
- Select both hearts and click **Align** at the top-right of the screen.<img src="images/tinkercad-box-07.png" style="float:right;width:150px;height:100px" alt="heart box alignment"> 
- Click on the two middle black circular handles to bring the hearts into alignment.
- Click **Group** at the top-right of the screen to combine the objects into one.<img src="images/tinkercad-box-08.png" style="float:right;width:140px" alt="heart box grouping"> 
<button onclick="toggle('gif4')">Show/Hide Animation</button>
    <div id="gif4">
    <img src="images/tinkercad-box-09.gif" >
    </div>

6. Make the lid out of the second set of hearts: <img src="images/tinkercad-box-10.png" style="float:right;width:200px" alt="heart box lid"> 
- Change the height of the larger heart to **3mm** by clicking on the white square handle in the middle of the heart.
- Change the height of the smaller heart to **6mm**.
- Resize the smaller heart so that its length and width are both **68mm** by dragging the white square handles on the base and top of the heart (or by clicking on one of the white square handles and entering “**68**” in the fields). This allows the lid to fit easily in the box.
- Select both hearts and click **Align** at the top-right of the screen.
- Click on the two middle black circular handles to bring the hearts into alignment.
- Click **Group** to combine the objects into one.
<button onclick="toggle('gif5')">Show/Hide Animation</button>
    <div id="gif5">
    <img src="images/tinkercad-box-11.gif" >
    </div>

7. **OPTIONAL**: Place text on the inside of the lid.  <img src="images/tinkercad-box-12.png" style="float:right;width:220px" alt="editing menu"> 
- Grab a **Text** from the **Basic Shapes** panel on the right and drag it onto the workplane.
- Write whatever is to be written on the inside of the box in the **Text** field. 
- Change the Bevel to approximately **1**. This makes the text thicker and therefore easier to 3D print.
- Resize the length and width to be small enough to fit on the inside of the lid. <img src="images/tinkercad-box-13.png" style="float:right;width:200px" alt="heart box lid with writing"> 
- Drag the text into the lid. 
- Select the text and the heart, then click Align  at the top-right of the screen.
- Click on the two middle black circular handles to bring the hearts into alignment.
- Select the text and the lid, then click **Group**.
<button onclick="toggle('gif6')">Show/Hide Animation</button>
    <div id="gif6">
    <img src="images/tinkercad-box-14.gif" >
    </div>

8. Export your design as 3D printable files: <img src="images/tinkercad-box-15.png" style="float:right;width:300px" alt="menu selecting include the selected shape">
- Select the main box. 
- Click on the “**Export**” button on the top right of the toolbar. Select the option include “the selected shape” and then select “**.STL**” and save the file to your computer.
- **Repeat with the lid**.<br>
![Final product of project](images/tinkercad-box-16.png)


<script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

[NEXT STEP: Snowperson Ornament Activity](6-snowperson-activity.html){: .btn .btn-blue }
