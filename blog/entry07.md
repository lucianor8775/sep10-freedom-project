# Entry 7
##### 5/22/2025

### Content
This month I presented my website on astronomy to a lot of people during periods 1-2 as well as during 8th period. A few things that I can takeaway from my elavator pitch are to sum up all my important key points in an understandable and organized manner because if you dont then itll drive people away from your presentation and they wont understand the point of your website. A few things that i have taken away from my in class presentation with my classmates is to take my time with my presentation, give takeaways, explain my process and to look at my aduience while speaking because, something that i didnt do so well was looking at my class and taking time with my explainations.

### Sources
* [Notes](https://docs.google.com/document/d/1XJT8S4hfZrOqRuJE77YyxdEcT-xpe8Qa5nfXv4lj0fY/edit?tab=t.0)
* [Slides](https://docs.google.com/presentation/d/1Eu_DoB1AtDPFwreffgCnQiWNX0naKR0-EA5ZpFzbfHo/edit?slide=id.p#slide=id.p)

### EDP
At this point I am completely done with my project and done with all my coding having to do with my tool. 
This is some code of my model that i created by doing research about the planets in our solar system and coding and adding components like position which determine the position of your object, animation which makes my sphere move, and background which determines background color.
``` dash
html>
  <head>
    <script src="https://aframe.io/releases/1.7.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-scene background="color: black">

      <!-- SUN -->
      <a-entity position="0 1.6 -10">
        <a-sphere radius="1.5" color="yellow"
                  animation="property: rotation; to: 0 360 0; loop: true; dur: 20000"></a-sphere>
        <a-light type="point" color="#ffffff" intensity="2" distance="30"></a-light>
      </a-entity>

```
This is some of the code for the carousel in my website which I found to be the most captivating part of my website because of the text component and facts that it includes that go along with the images.
```dash
 <div class="carousel-inner">
        <div class="carousel-item active">
         <img src="tool/earth2.png" class="d-block w-100" alt="earth">
         <div class="carousel-caption d-none d-md-block">
          <h5>Earth</h5>
          <p>Our home planet, the only one known to support life.</p>
         </div>
        </div>
```

### Skills
A few skills that I have gained from this experince include:
* Public Speaking
* Organization
* Research
  
Public speaking is a very important skill to have and I gained it by practicing my elavator pitch with others and by being confident when speaking with the judges who were grading my presentation skills.
I gained the skill of organization by taking down notes and summerizing any key points that I would like to work on and or explain when doing research and doing my presentation with others.
Another skill that I gained throughout this process was research which I gained by asking my peers questions and their opinions on things as well as by doing research on my tool and looking at bootstrap templetes as a way of inspiration when building my website.


[Previous](entry06.md) | [Next](entry08.md)

[Home](../README.md)
