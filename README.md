![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Start%20Page.png)
# Final Project
> My final project is an interactive data visualisation showcasing world life expectancy across the past 200 years. It features a coded background produced using HTML and Sass. 
> Link to my final project [_here_](https://app.flow.gl/flow/9htu02r). 

## Table of Contents
* [Key Concepts](#key-concepts)
* [Technologies Used](#technologies-used)
* [Setup and Usage](#setup-and-usage)
* [Project Status](#project-status)
* [Screenshots](#screenshots)
* [Acknowledgements](#acknowledgements)


## Key Concepts 
My project has engaged with the following key concepts:

Week 01:
- Code Literacy 
- Data Literacy 

Week 02: 
- Code 
- Data 
- Record, Storing, Encoding, Decoding
- Programming language
- Object-oriented programming
- High-level, low-level language
- Code's associated practices (Library's of Code etc.)

Week 03: 
- Software 
- Open-source Software 

Week 04:
- Graphical User Interface 

Week 06:
- Data point
- Types of data
- Qualitative and quantitative data
- Data structures (Table, Graph)
- Type of values (in programming concepts as data types)

Week 07:
- Data (sample) distribution
- Statistical transformation
- Averages (median, mean, mode, etc.)
- Time series

Week 08:
- Data visualisation and data reporting
- Mapping data
- Geometric mapping (line, bar, density, area, histograms, point, box plot, etc.)

Week 09:
- Open data

Other related concepts include:
- Variables 
- Values 
- Data Types 
- HTML
- Markup Language 
- CSS

## Technologies Used
- [Flow Immersive](https://flowimmersive.com/) - Data visualisation software
- [WebXR Viewer](https://apps.apple.com/us/app/webxr-viewer/id1295998056) on iOS - Mobile AR viewer
- [Code Pen](https://codepen.io/) - Open-source software
- HTML - High-level markup language
- CSS (Sass) - High-level markup language


## Features
- Awesome feature 1
- Awesome feature 2
- Awesome feature 3


## Setup and Usage

Data Visualisation 
1. Create an account at [Flow Immersive](https://flowimmersive.com/) 
2. Download datasets found [_here_](https://drive.google.com/drive/folders/1pxbeBI75I_uA3wXf12DL_trpRCTVRHA2?usp=sharing). 
3. Replicate steps shown [_here_](https://app.flow.gl/flow/9htu02r).

To present visualisation on desktop/screen: select _share_ in Flow project and then _present_

To present visualisation in AR/VR: 
1. Download [WebXR Viewer](https://apps.apple.com/us/app/webxr-viewer/id1295998056) on iOS
2. Paste (https://app.flow.gl/flow/9htu02r) into WebXR Viewer browser
3. Select AR View button (circled in red) 

![Alt Text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/AR%20View%20Button.png)

Coded Background 
1. Create an account at [Code Pen](https://codepen.io/)
2. Create a new [Pen](https://codepen.io/pen/)
3. Input [HTML](https://github.com/cdansereau2022/Final-Project-/blob/main/Code/index.haml) 

``` 
#stars 
#stars2
#stars3
``` 

5. Input [Sass](https://github.com/cdansereau2022/Final-Project-/blob/main/Code/style.sass)

``` 
@import compass


// n is number of stars required
@function multiple-box-shadow ($n) 
  $value: '#{random(2000)}px #{random(2000)}px #FFF'
  @for $i from 2 through $n
    $value: '#{$value} , #{random(2000)}px #{random(2000)}px #FFF'

  @return unquote($value)

$shadows-small:  multiple-box-shadow(700)
$shadows-medium: multiple-box-shadow(200)
$shadows-big:    multiple-box-shadow(100)

html
  height: 100%
  background: radial-gradient(ellipse at bottom, #131a24 0%, #090A0F 100%)
  overflow: hidden
    
#stars
  width: 1px
  height: 1px
  background: transparent
  box-shadow: $shadows-small
  animation			: animStar 50s linear infinite
    
  &:after
    content: " "
    position: absolute
    top: 2000px
    width: 1px
    height: 1px
    background: transparent
    box-shadow: $shadows-small
    
#stars2
  width: 2px
  height: 2px
  background: transparent
  box-shadow: $shadows-medium
  animation			: animStar 100s linear infinite
    
  &:after
    content: " "
    position: absolute
    top: 2000px
    width: 2px
    height: 2px
    background: transparent
    box-shadow: $shadows-medium
    
#stars3
  width: 3px
  height: 3px
  background: transparent
  box-shadow: $shadows-big
  animation			: animStar 150s linear infinite
    
  &:after
    content: " "
    position: absolute
    top: 2000px
    width: 3px
    height: 3px
    background: transparent
    box-shadow: $shadows-big
    
    span
      background: -webkit-linear-gradient(white, #1f2933)
      -webkit-background-clip: text 
      -webkit-text-fill-colour: transparent 
      
  @keyframes animStar 
    from 
      transform: translateY(0px) 
    to 
      transform: translateY(-2000px)
 ```

## Project Status
Project is: _complete_ 


## Screenshots
Screenshot of Final Visualisation Step #1
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%201.png)

Screenshot of Final Visualisation Step #2
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%202.png)

Screenshot of Final Visualisation Step #3 
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%203.png)

Screenshot of Final Visualisation Step #4
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%204.png)

Screenshot of Final Visualisation Step #5
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%205.png)

Screenshot of Final Visualisation Step #7 
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%207.png)

Screenshot of Final Visualisation Step #8
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%208.png)

Screenshot of Final Visualisation Step #9
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%209.png)

Screenshot of Final Visualisation Step #10 
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%2010.png)

Screenshot of Final Visualisation Step #11 
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%2011.png)

Screenshot of Final Visualisation Step #12
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%2012.png)

Screenshot of Final Visualisation Step #13
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20Step%2013.png)

Screenshot of Coded Animation from Code Pen
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/CodePen%20Screenshot.png)

Screenshot of Final Visualisation AR Presentation
![alt text](https://github.com/cdansereau2022/Final-Project-/blob/main/Images/Viz%20AR%20Presentation.JPG)



## Sources 

Quantitative Data Sourced From:

- Gap Minder. (2021). _Life Expectancy at Birth (v12)_ [Data Set]. Retrieved from https://www.gapminder.org/data/documentation/gd004/

- Lasso, F. (2017). _Countries of the World_ [Data Set]. Retrieved from https://www.kaggle.com/datasets/fernandol/countries-of-the-world

- World Health Organization. (2019). _Life expectancy at birth (years)_ [Data Set]. Retrieved from https://www.who.int/data/gho/data/indicators/indicator-details/GHO/life-expectancy-at-birth-(years)

Qualitative  Data Sourced From: 

- BBC News. (2019, April 4). _Rwanda genocide: 100 days of slaughter_. BBC News https://www.bbc.com/news/world-africa-26875506

- Centers for Disease Control and Prevention, National Center for Immunization and Respiratory Diseases (NCIRD). (2019, January 30). _Influenza Historic Timeline_. CDC. https://www.cdc.gov/flu/pandemic-resources/pandemic-timeline-1930-and-beyond.htm

- Desjardins, J. (2018, March 28). _These discoveries saved billions of lives_. World Economic Forum. https://www.weforum.org/agenda/2018/03/the-50-most-important-life-saving-breakthroughs-in-history

- Roser, M., Ortiz-Ospina, E., & Ritchie, H. (2019, October). _Life Expectancy_. Our World in Dat. https://ourworldindata.org/life-expectancy

- Wikipedia. (n.d.). _List of epidemics_. Wikipedia. https://en.wikipedia.org/wiki/List_of_epidemics

- Wikipedia. (n.d.). _List of wars and anthropogenic disasters by death toll_. Wikipedia. https://en.wikipedia.org/wiki/List_of_wars_and_anthropogenic_disasters_by_death_toll

## Acknowledgements
- This project was inspired by the work of Flow Immersive
