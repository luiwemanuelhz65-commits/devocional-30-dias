<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Devocional 30 Dias</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body{
  margin:0;
  font-family: Arial,sans-serif;
  color:white;
  background: linear-gradient(135deg, #000000, #0a0f2c);
  overflow-x:hidden;
  position: relative;
}
body::before{
  content:"";
  position: fixed;
  width:200%;
  height:200%;
  background: radial-gradient(circle, rgba(255,0,150,0.15) 1px, transparent 1px);
  background-size:40px 40px;
  animation:moveBg 20s linear infinite;
  top:-50%;
  left:-50%;
  z-index:-1;
}
@keyframes moveBg{
  from{transform:translate(0,0);}
  to{transform:translate(100px,100px);}
}
section{
  padding:60px 20px;
  text-align:center;
}
.card{
  background: rgba(22,27,34,0.9);
  padding:30px;
  margin:40px auto;
  border-radius:20px;
  max-width:600px;
  backdrop-filter: blur(10px);
  transition:0.3s;
}
.card:hover{
  transform: translateY(-5px);
}
.btn{
  display:inline-block;
  margin-top:20px;
  padding:14px 30px;
  border-radius:30px;
  text-decoration:none;
  font-weight:bold;
  background: linear-gradient(45deg,#833ab4,#fd1d1d,#fcb045);
  color:white;
}
.blur-overlay{
  height:140px;
  margin-top:-70px;
  margin-bottom:-70px;
  backdrop-filter: blur(30px);
  -webkit-backdrop-filter: blur(30px);
  background: linear-gradient(to bottom, rgba(0,0,0,0), rgba(0,0,0,0.5), rgba(0,0,0,0));
  position: relative;
  z-index:1;
}
</style>
</head>
<body>

<section>
<h1 style="color:#58a6ff;">📘 Devocional 30 Dias</h1>
<p style="max-width:700px;margin:auto;color:#c9d1d9;">
Um guia completo para fortalecer sua fé durante 30 dias.
</p>
<div class="card">
<h2 style="color:#58a6ff;">O que você vai aprender:</h2>
<p>✔ Constância espiritual</p>
<p>✔ Entender melhor a Bíblia</p>
<p>✔ Aplicação prática diária</p>
<h3 style="color:#1f6feb;">Apenas R$29,90</h3>
<a href="https://pay.kiwify.com.br/kAQrrEc" class="btn">
QUERO FORTALECER MINHA FÉ
</a>
</div>
</section>

<div class="blur-overlay"></div>

<section>
<h2>Me acompanhe no Instagram</h2>
<a href="https://www.instagram.com/_luisxzr7_" class="btn">Seguir @_luisxzr7_</a>
</section>

</body>
</html>
