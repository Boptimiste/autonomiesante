---
title: "🥄Recettes"
order: 10
in_menu: true
---
![logo_Autonomie_Santé]({% link images/arbre_diaporama.jpg %})
Ici vous trouverez des assiettes repas et des gourmandises faciles et rapides à réaliser: 

<h2>Galerie santé</h2>
<div id="myBtnContainer">
  <button class="btn active" onclick="filterSelection('all')"> Tout voir</button>
  <button class="btn" onclick="filterSelection('snack')"> Snack</button>
  <button class="btn" onclick="filterSelection('assiette-repas')"> Assiette-repas</button>
  <button class="btn" onclick="filterSelection('gourmandises')"> Gourmandises</button>
</div>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column snack">
    <div class="content">
      <img src="/w3images/mountains.jpg" alt="Mountains" style="width:100%">
      <h4>Mountains</h4>
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>
  <div class="column nature">
    <div class="content">
      <img src="/w3images/lights.jpg" alt="Lights" style="width:100%">
      <h4>Lights</h4>
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>
  <div class="column nature">
    <div class="content">
      <img src="/w3images/nature.jpg" alt="Nature" style="width:100%">
      <h4>Forest</h4>
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>

  <div class="column cars">
    <div class="content">
      <img src="/w3images/cars1.jpg" alt="Car" style="width:100%">
      <h4>Retro</h4>
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>
  <div class="column cars">
    <div class="content">
      <img src="/w3images/cars2.jpg" alt="Car" style="width:100%">
      <h4>Fast</h4>
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>
  <div class="column cars">
    <div class="content">
      <img src="/w3images/cars3.jpg" alt="Car" style="width:100%">
      <h4>Classic</h4>
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>

  <div class="column people">
    <div class="content">
      <img src="/w3images/people1.jpg" alt="People" style="width:100%">
      <h4>Girl</h4>
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>
  <div class="column people">
    <div class="content">
      <img src="/w3images/people2.jpg" alt="People" style="width:100%">
      <h4>Man</h4>
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>
  <div class="column people">
    <div class="content">
      <img src="/w3images/people3.jpg" alt="People" style="width:100%">
      <h4>Woman</h4>
      <p>Lorem ipsum dolor..</p>
    </div>
  </div>
<!-- END GRID -->
</div>

<style>
.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: #6C5353;
  color: white;
  text-align: center;
}

* {
  box-sizing: border-box;
}

body {
  background-color: #fcfefd;
  padding: 20px;
  font-family: Arial;
}

/* Center website */
.main {
  max-width: 1000px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
}

.row {
  margin: 8px -16px;
}

/* Add padding BETWEEN each column (if you want) */
.row,
.row > .column {
  padding: 8px;
}

/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  display: none; /* Hide columns by default */
}

/* Clear floats after rows */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Content */
.content {
  background-color: white;
  padding: 10px;
}

/* The "show" class is added to the filtered elements */
.show {
  display: block;
}

/* Style the buttons */
.btn {
  border: none;
  outline: none;
  padding: 12px 16px;
  background-color: white;
  cursor: pointer;
}

/* Add a grey background color on mouse-over */
.btn:hover {
  background-color: #2bbf9c;
}

/* Add a dark background color to the active button */
.btn.active {
  background-color: #a58765;
   color: white;



</style>

<div class="footer">
  <p>Claire Bourland Praticienne de Santé Naturopathe ☀ 0690 597 609</p>
</div> 