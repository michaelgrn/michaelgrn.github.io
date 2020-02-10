---
title: Classes
layout: splash
header:
    overlay_filter: "0.5"
    overlay_image: /images/projects.jpg
    caption: "Photo by [Helloquence](https://unsplash.com/@helloquence) on [Unsplash](https://unsplash.com/photos/5fNmWej4tAA)"
    excerpt: "Classes I teach"

---

<style>
body {
  margin: 40px;
}

.sidebar {
    grid-area: sidebar;
}

.content {
    grid-area: content;
}

.header {
    grid-area: header;
}


.wrapper {
    display: grid;
grid-gap: 10px;
    grid-template-columns: 120px  120px  120px;
    grid-template-areas:
           "....... header  header"
                         "sidebar content content";
    background-color: #fff;
    color: #444;
}
.box {
  background-color: #444;
  color: #fff;
  border-radius: 5px;
  padding: 20px;
  font-size: 150%;
}

.header {
  background-color: #999;
}

</style>

  


<div class="wrapper">
  <div class="box header">Header</div>
  <div class="box sidebar">Sidebar</div>
  <div class="box content">Content</div>
</div>

  
  
CS 361: Introduction to the Theory of Computation

Fall 2014, Fall 2015, Spring 2016, Summer 2016, Spring 2017, Spring 2018, Fall 2018, Spring 2019

CS 537: Introduction to Information Retrieval 

Fall 2016

CS 481: CS Seminar  

Spring 2017, Fall 2018

CS 637: Information Retrieval 

Spring 2015, Fall 2017
