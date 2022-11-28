---
Title: Technologies
Description: This is the Technology page.
Template: technologies
---

<div class="grid-container">

<div class="grid-title"><h1>Teknologier</h1></div>
  <div class="grid-item item1"><a href="css">
  <h3>CSS</h3>
  <p style="font-size: 16px;"> Lorem ipsum doler sit amet</p>
  </a></div>
  <div class="grid-item item2"><a href="html">
  <h3>HTML</h3>
  <p style="font-size: 16px;"> Lorem ipsum doler sit amet</p>
  </a></div>
  <div class="grid-item item3"><a href="javascript">
  <h3>Javascript</h3>
  </a></div>
  <div class="grid-item item4"><a href="php">
  <h3>PHP</h3>
  </a></div>  
  <div class="grid-item item5"><a href="python">
  <h3>Python</h3>
  <p style="font-size: 16px;"> Lorem ipsum doler sit amet</p>
  </a></div>
  <div class="grid-item item6"><a href="git">
  <h3>GIT</h3>
  </a></div>  
  <div class="grid-item item7"><a href="sqlite">
  <h3>SQLite</h3>
  </a></div>
</div>

<style>
.grid-container {
  display: grid;
  gap: 10px;
  background-color: #2196F3;
  padding: 10px;
}

.grid-title {
  grid-column: span 4;
  grid-row: 1;
  text-align: center;
}

.grid-item {
  background-color: rgba(255, 255, 255, 0.8);
  text-align: center;
  padding: 20px;
  font-size: 30px;
}

.item1 {
  grid-column: 2 / span 3;
  grid-row: 2;
}

.item3 {
    grid-column: 1 / span 3;
    grid-row: 3;
}

.item5 {
    grid-column: span 4;
    grid-row: 4;
}

.item6 {
    grid-column: 1;
    grid-row: 5;
}

.item7 {
    grid-column: 2 / span 3;
    grid-row: 5;
}



</style>