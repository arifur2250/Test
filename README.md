<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Kids Learning App</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f0f8ff;
}

header{
background:#ff5722;
color:white;
text-align:center;
padding:15px;
font-size:24px;
}

.menu{

display:grid;
grid-template-columns:repeat(2,1fr);
gap:15px;
padding:15px;

}

.card{

background:white;
padding:25px;
border-radius:15px;
text-align:center;
font-size:18px;
font-weight:bold;
box-shadow:0 3px 8px rgba(0,0,0,0.2);
cursor:pointer;
transition:0.3s;

}

.card:hover{
transform:scale(1.05);
background:#e3f2fd;
}

.footer{
text-align:center;
padding:10px;
font-size:14px;
color:#555;
}

</style>

</head>

<body>

<header>
🎓 Kids Learning App
</header>

<div class="menu">

<div class="card" onclick="openPage('numbers')">🔢 Numbers</div>
<div class="card" onclick="openPage('alphabet')">🔤 Alphabet</div>
<div class="card" onclick="openPage('bangla')">🔡 বাংলা</div>
<div class="card" onclick="openPage('math')">➕ Math</div>
<div class="card" onclick="openPage('games')">🎮 Games</div>
<div class="card" onclick="openPage('quiz')">🧠 Quiz</div>

</div>

<div class="footer">
Offline Kids Learning App
</div>

<script>

function openPage(page){

if(page==="numbers"){
window.location="numbers.html";
}

if(page==="alphabet"){
window.location="alphabet.html";
}

if(page==="bangla"){
window.location="bangla.html";
}

if(page==="math"){
window.location="math.html";
}

if(page==="games"){
window.location="games.html";
}

if(page==="quiz"){
window.location="quiz.html";
}

}

</script>

</body>
</html>
