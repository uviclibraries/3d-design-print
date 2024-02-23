---
layout: default
title: 8-Importing and Modifying STL in TinkerCad
nav_order: 10
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

<img src="images/tinkercad-import-01.png" style="float:right;width:220px" alt="TinkerCad logo">

# Importing and Modifying STL in TinkerCad

If you and your group have any questions or get stuck as you work through this in-class exercise, please ask the instructor for assistance.  Have fun!<br>
NOTE: no responsibility for the accuracy of the VEX 3d parts for 3rd party website.

1. If you haven’t already, please go to the [TinkerCad website](http://tinkercad.com){:target="_blank"} and create an account for yourself.  If you find yourself in a tutorial, click on the Tinkercad logo in the top left of the screen to exit to the home page.

2. Click **Create new design**. If the TinkerCad tutorial pane is up on the right-hand side, you will need to get out of it before proceeding. Click on the TinkerCad logo at the top to bring you back to your main page. From there you should see the “Create new design” button. 
    <img src="images/tinkercad-import-02.png" style="float:right;width:250px" alt="Importing menu">

3. Download and import an STL model file into TinkerCad in preparation for modifying it.
- Download the (first file only) [frog.stl](https://www.thingiverse.com/thing:4838220/files){:target="_blank"} file to your computer. 
- In TinkerCad click on the grey **Import** button on the top right of the screen, and then find and select the STL file you just downloaded. Click on the **Import** button.(see image)
<img src="images/import-frog.png" style="float:right;width:300px" alt="import button">

4. Modify and customize the model you just imported into TinkerCad. You can use any of the tools you learned to use in the other TinderCad activities to customize this model.<br>
 - Click on the **Torus** Tool and then click on the Workplane where you would like to put it.
<img src="images/torus.png" style="float:right;width:300px" alt="torus button">

 - **Rotate** the torus 45 degrees so that it is standing on end by dragging the curved arrow at the top of the torus (see image on right).<img src="images/45-torus.png" style="float:right;width:220px" alt="white handles rotation">
 - Click on the **white handle** at the top of the Roof and then change the height from 20.00mm to 6.35mm (see image on right).
 - You can now stretch and move the triangle to the shape you would like for your modified part. Below is an example of a modified part where the part was stretched and then copied before moving the additional elements of the model into position (see below):<br>
    <button onclick="toggle('gif3')">Show/Hide Animation</button>
    <div id="gif3">
    <img src="images/tinkercad-import-07.gif">
    </div>

    <img src="images/tinkercad-import-08.png" style="float:right;width:280px" alt="final product">
5. When you are finished modifying the model, click on the **Export** button on the top right of the toolbar, and then select **.STL** and save the file to your hard drive so it’s ready for the next stage of the 3D printing process.

    Good Job!

**OPTIONAL: If you would like to modify one of hundreds of VEX parts continue with this optional activity:**

6. Download a ZIP file with all [VEX IQ CAD parts in STEP format](https://link.vex.com/cad/STEP/VEX-IQ-All-Parts-STEP){:target="_blank"} (Zip, 96.27 MB) and Unzip the file.

7. Convert one of the models into STL format:
- Open the [eMachine Shop](https://convert.emachineshop.com/){:target="_blank"} website, and then click on the blue Upload File button.
- Select one of the STEP model files you just downloaded and unzipped on your computer.
    ![Image uploading files](images/tinkercad-import-09.png)
- Select the “Convert Uploaded File to type” to **STL**.
- Click on the green **Convert File** button. Once the website has finished converting the STEP file to STL format you can download the file, and then import the STL file into TinkerCad (see Step 3 above).

8. If you’d like to design your VEX compatible parts based on the VEX 2600 structure pieces, you can use the [measurements on this PDF](https://content.vexrobotics.com/docs/276-2600-Structure-Pieces.pdf){:target="_blank"} for reference purposes. Note that the measurements on the PDF are in inches and TinkerCad uses mm, as does the 3D printing software in the DSC. 

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

[NEXT STEP: Importing and Modifying 2D images](9-Importing-2D.html){: .btn .btn-blue }
