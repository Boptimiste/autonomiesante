---
title: "🥄Recettes"
order: 10
in_menu: true
---
![logo_Autonomie_Santé]({% link images/arbre_diaporama.jpg %})
Ici vous trouverez des assiettes repas et des gourmandises faciles et rapides à réaliser: 

<!-- MAIN (Center website) -->
<div class="main">

<h1>Assiettes_Repas</h1>
<hr>

<h2>Galerie</h2>
<p>Resize the browser window to see the responsive effect.</p>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column">
    <div class="content">
      <img src=""https://github.com/Boptimiste/autonomiesante/blob/main/images/Assiette1.jpg" alt="alt="Assiette1.jpg" style="width:100%">
      <h3>Assiette1</h3>
      <p>Sarrasin, carottes, courgettes, sucrine, betterave, gombos...</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
      <img src="https://github.com/Boptimiste/autonomiesante/blob/main/images/Assiette2.jpg"" alt="Assiette2.jpg" style="width:100%">
      <h3>Assiette2</h3>
      <p>Lorem ipsum..</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
      <img src="https://github.com/Boptimiste/autonomiesante/blob/main/images/Assiette3.jpg"" alt="Assiette3" style="width:100%">
      <h3>Assiette3</h3>
      <p>Lorem ipsum..</p>
    </div>
  </div>
  <div class="column">
    <div class="content">
      <img src="https://github.com/Boptimiste/autonomiesante/blob/main/images/Assiette4.jpg"" alt="Assiette4" style="width:100%">
      <h3>Assiette4</h3>
      <p>Lorem ipsum..</p>
    </div>
  </div>
</div>

<div class="content">
  <img src="https://github.com/Boptimiste/autonomiesante/blob/main/images/Assiette5.jpg"" alt="Assiette5" style="width:100%">
  <h3>Assiette5</h3>
  <p>Lorem ipsum..</p>
</div>

<!-- END MAIN -->
</div>

* {
  box-sizing: border-box;
}

body {
  background-color: #f1f1f1;
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

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
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

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 900px) {
  .column {
    width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}




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
</style>

<div class="footer">
  <p>Claire Bourland Praticienne de Santé Naturopathe ☀ 0690 597 609</p>
</div> 