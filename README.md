# SmoothScroll v2.0

Pimp up your webpage's experience by adding smooth locomotion effects in it!
![Ray Concepts - SmoothScroll 2.0 Banner](https://github.com/ray-concepts/SmoothScroll2.0/blob/main/smoothscroll2_banner-1.png?raw=true)
## Usage
First, download the file and extract SmoothScroll-v2.0.js and link it into your page.
```
#For a Container with locomotive effect:
    <div loco-scroll-container class="container"> 

#For adding the effect to a specific element:
    -Mention 'loco-scroll' before specifying parameters:

  PARAMETERS:
    -Speed:
       Values: 1-10   
           Change the value to -ve to set the effect to opposite direction
        -Sample: 
        <div loco-scroll loco-scroll-speed="" class="">

    -Orientation:
        Values: horizontal, vertical 
           By default the effect is set on vertical orientation
        -Sample: 
        <div loco-scroll loco-scroll-direction="horizontal" class="">

   -You can use multiple parameters at the same time
       -Sample: 
       <div loco-scroll loco-scroll-speed="" loco-scroll-direction="horizontal" class="">

```
