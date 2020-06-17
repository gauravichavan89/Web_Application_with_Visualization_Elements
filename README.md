# Web Application with Visualization Elements


We created a visualization website on ‘World Happiness Index’ with graphs, charts, event calendar, chatbot, maps using D3.js, Chart.js, JavaScript, jQuery, HTML, CSS, BootStrap.


## Getting Started


The following instructions shall ensure that the web application is up and running on your local machine for
testing purposes. See ‘Running the tests’ section to know how to run the assignment.

Prerequisite Software Required
* Any browser: Google Chrome(recommended), Firefox, Microsoft Edge(preferred), explorer for
loading the website.
* Software Required: Python 2.7 (Anaconda3 2018.12 64 bit) for Windows 10 as IDE
* For editing the code I have used Sublime editor by following the instructions on
https://www.sublimetext.com/3 for downloading Sublime for Windows 64 bit Installer. You may not
need to download this as this is a development editor and not for testing purpose.
* I just write this statement and import d3.js library; you may not have to download anything for this
as I have included this line in my code.
<script src=' https://d3js.org/d3.v4.min.js '></script>
* I import canvasjs assets by including the following sentence in code:
<script src=" https://canvasjs.com/assets/script/canvasjs.min.js "></script>
Again you do not have to download anything for this.


## Installation


As I am using a python server for loading my website on localhost; please follow the following
instructions to download anaconda which comes along with python:
* Follow the instructions in the documentation https://docs.anaconda.com/anaconda/install/windows/
for downloading Python version 2.7 for Anaconda 2018.12 for Windows Installer.
* After launching the Anaconda Navigator, create a new environment for running vtk programs
by referring to the following documentation:
https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/#creating-a-new-environ
ment
* Import vtk, numpy and scipy packages into this newly created environment by following the
guidelines specified in:
https://docs.anaconda.com/anaconda/navigator/tutorials/manage-packages/#installing-a-package
* In the Anaconda Navigator, click ‘Home’ on the left panel, then choose the newly created
environment for running the vtk programs from the drop down provided under ‘Applications on’ located
on the top most section of the navigator.
* Click on the ‘Install’ button under Spyder. On completing the installation click the ‘Launch’ button
under it.


## Running the tests


* Enter Windows+R (Run command) on your system and open drivers.
* Now follow this path: \drivers\etc\hosts
* Open hosts file using notepad++ and edit it in administrative mode.
* UnComment the line “127.0.0.1 localhost” and save it.
* Go to the directory where you have your root html file(index.html in our case)
\mini_project\NiceAdmin and type cmd
* Type python -m http.servers and receive the port number
* Do not close the command prompt until you are finished evaluating the website on local host.
* Type localhost:portnumber example, localhost:8000 on browser and refresh it.
(Note: Please clear cache on chrome before evaluating the website if you choose to use that as your
browser.)

