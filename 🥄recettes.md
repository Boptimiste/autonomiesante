---
title: "🥄Recettes"
order: 10
in_menu: true
---
![logo_Autonomie_Santé]({% link images/arbre_diaporama.jpg %})
Ici vous trouverez des assiettes repas et des gourmandises faciles et rapides à réaliser: 

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

/* The grid: Four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
  padding: 10px;
}

/* Style the images inside the grid */
.column img {
  opacity: 0.8; 
  cursor: pointer; 
}

.column img:hover {
  opacity: 1;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* The expanding image container */
.container {
  position: relative;
  display: none;
}

/* Expanding image text */
#imgtext {
  position: absolute;
  bottom: 15px;
  left: 15px;
  color: white;
  font-size: 20px;
}

/* Closable button inside the expanded image */
.closebtn {
  position: absolute;
  top: 10px;
  right: 15px;
  color: white;
  font-size: 35px;
  cursor: pointer;
}
</style>
</head>
<body>

<div style="text-align:center">
  <h2>Tabbed Image Gallery</h2>
  <p>Click on the images below:</p>
</div>

<!-- The four columns -->
<div class="row">
  <div class="column">
    <img src="https://github.com/Boptimiste/autonomiesante/blob/main/images/Assiette9.jpg?raw=true" alt="Assiette9" style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="https://github.com/Boptimiste/autonomiesante/blob/main/images/Assiette1.jpg?raw=true" alt="Assiette1" style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="https://github.com/Boptimiste/autonomiesante/blob/main/images/Assiette2.jpg?raw=true" alt="Assiette2" style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="img_lights.jpg" alt="Lights" style="width:100%" onclick="myFunction(this);">
  </div>
</div>

<div class="container">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <img id="expandedImg" style="width:100%">
  <div id="imgtext"></div>
</div>

<script>
function myFunction(imgs) {
  var expandImg = document.getElementById("expandedImg");
  var imgText = document.getElementById("imgtext");
  expandImg.src = imgs.src;
  imgText.innerHTML = imgs.alt;
  expandImg.parentElement.style.display = "block";
}
</script>

</body>
</html>

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