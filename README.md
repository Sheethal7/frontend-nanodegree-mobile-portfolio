# Website Performance Optimization portfolio project

## Getting started
* Clone or fork the repository
* Open the html files and run through any browser to view the page

### Part 1: Optimize PageSpeed Insights score for index.html
* Open index.html in a browser of your choice
* Run the file through PageSpeed Insights to view score 

#### Optimisations:
##### index.html:
* Critical css files were inlined
* media query for print was included in the link tag as media=print
* Java Script files is now loaded in the head tag

### Part 2: Optimize Frames per Second in pizza.html
* Open pizza.html in a browser of your choice
* Open Timeline in Developer tools to view whether the page runs at 60fps

#### Optimisations:
##### pizza.html:
* Style tags were removed as much as possible
* Bootstrap Classes were assigned instead of width in style tags

##### main.js:
* for loops have been modified
