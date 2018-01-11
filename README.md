# JDeation.com Designer
This projects initial purpose is to allow for the custom design of mounting plates and custom cases for the DIY Christmas Light community.
The JDeation Designer allows creation of these custom designed mounting plates via our Web App located at http://jdeation.com through simple drag and drop actions.

# This Repository
This repository holds all of the components which are used by the JDeation Designer.  Are you a product designer or an enthusiest that would like to have your design in the JDeation Designer?
Use this GitHub repository to add it.

# How To Create A Component
To create a component you must follow 4 simple steps.

### 1) Create the component SVG

* Use Inkscape or other vector program to create your SVG.
* Colors are very important in JDeation Designer.  **Only Black colors are cut lines.**  Use Red to highlight component connection points or other visual component points to allow for easier placement.
* SVG Must be fixed size **in millimeters**.  Example:
  ><svg
   xmlns:dc="http://purl.org/dc/elements/1.1/"
   xmlns:cc="http://creativecommons.org/ns#"
   xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
   xmlns:svg="http://www.w3.org/2000/svg"
   xmlns="http://www.w3.org/2000/svg"
   xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
   xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape"
   **width="35mm"
   height="26mm"
   viewBox="0 0 35 26"**
   version="1.1"
   id="svg7655"
   inkscape:version="0.92.1 r15371"
   sodipodi:docname="espixel_pops.svg">

* Use stroke sizes of less than .5 millimeters.
* No embedded images or fonts.  Everything must be converted to Paths.
* When creating mounting holes use the following sized holes:
  * For 4-40 screw / standoff - hole size should be 2.44 millimeters

### 2) Create a photo

Take a photo of your component.  Width / Height not important as image will be scaled,  but please
keep your photo to a minimal filesize.  Any web based file format accepted (jpg, gif, png)

### 3) Edit the CSV

Add your SVG and Image to the appropriate directory in GitHub.  Please try to keep things organized.  See how
rest of directory structure is organized and follow along.

In the root GitHub directory there is CSV file named jdeation_component_list.csv.  Add your
design to the csv file.  **All Fields are Mandatory.**

### 4) Initiate Pull Request

Initiate a GitHub pull request and we will pull your design into the solution.  Upon the next JDeation Designer build your components will be part of the solution.


# How To Create a Model

A Model is the base svg of every design.
Typically it is created in CAD software and forms the basis for a case design.

New Models may be added to GitHub similar to components.

#1) Create the model SVG

Create the svg Model using your favorite design software (Fusion 360, Inkskape, etc...).

Keep your parts close together to reduce material waste.

#2) Edit the CSV

Add your model to the ** models ** directory in Git.

In the root GitHub directory there is CSV file named jdeation_model_list.csv.  Add your
model to the csv file.  **All Fields are Mandatory.**

#3 Initiate Pull Request

Initiate a GitHub pull request and we will pull your design into the solution.  Upon the next JDeation Designer build your model will be part of the solution.





