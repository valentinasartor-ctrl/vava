🌾🌽 PROJETO AGRINHO 2026
Do Campo à Mesa: A Jornada do Trigo e do Milho
📌 1. CONCEITO DO PROJETO

O projeto “Do Campo à Mesa: A Jornada do Trigo e do Milho” apresenta uma experiência interativa que mostra como esses dois grãos fundamentais percorrem toda a cadeia produtiva — desde o cultivo no campo até sua chegada à mesa das famílias.

A proposta destaca a importância do agronegócio sustentável, mostrando como tecnologia, agricultura, indústria e consumo consciente se conectam para garantir um futuro equilibrado entre produção e meio ambiente.

🎯 OBJETIVO

Conscientizar sobre a importância do trigo e do milho na alimentação mundial e na economia, destacando práticas sustentáveis que preservam o solo, reduzem impactos ambientais e promovem inovação no campo.

🧭 FUNCIONALIDADES DO SITE
🏠 Página inicial com tema principal
🌾 Seção sobre o cultivo do trigo
🌽 Seção sobre o cultivo do milho
🚜 Jornada produtiva (campo → indústria → cidade)
🖼️ Carrossel de imagens
🧠 Quiz interativo
💡 Curiosidades
🌿 Cards de sustentabilidade
🎬 Vídeo explicativo
📖 História em quadrinhos (HQ)
♿ Acessibilidade (fonte + contraste)
📱 Layout responsivo
📁 ESTRUTURA DO PROJETO
/
├── index.html
├── style.css
├── script.js
├── img/
│   ├── hero.jpg
│   ├── trigo.jpg
│   ├── milho.jpg
│   ├── campo.jpg
│   ├── industria.jpg
│   ├── cidade.jpg
│   └── logo.png
└── hq/
    └── hq.html
💻 2. CÓDIGO BASE DO PROJETO
🌐 index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Do Campo à Mesa</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
  <h1>🌾🌽 Do Campo à Mesa</h1>
  <p>Trigo e milho: base da alimentação e do futuro sustentável</p>
</header>

<nav>
  <a href="#trigo">Trigo</a>
  <a href="#milho">Milho</a>
  <a href="#jornada">Jornada</a>
  <a href="#quiz">Quiz</a>
</nav>

<section id="hero">
  <h2>Agro forte, futuro sustentável</h2>
</section>

<section id="trigo">
  <h2>🌾 O Trigo</h2>
  <p>O trigo é essencial na produção de pães, massas e diversos alimentos consumidos diariamente.</p>
</section>

<section id="milho">
  <h2>🌽 O Milho</h2>
  <p>O milho é um dos grãos mais versáteis, utilizado na alimentação humana, animal e na indústria.</p>
</section>

<section id="jornada">
  <h2>🚜 Jornada do Campo à Mesa</h2>
  <p>Do cultivo ao consumo, o trigo e o milho passam por processos tecnológicos e sustentáveis.</p>
</section>

<section id="quiz">
  <h2>🧠 Quiz Sustentável</h2>

  <p>Qual prática ajuda o meio ambiente?</p>
  <button onclick="responder(true)">Rotação de culturas</button>
  <button onclick="responder(false)">Queimadas</button>

  <p id="resultado"></p>
</section>

<footer>
  <p>Projeto Agrinho 2026 - Sustentabilidade no Agro</p>
</footer>

<script src="script.js"></script>
</body>
</html>
🎨 style.css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f4f7f2;
}

header {
  background: #2e7d32;
  color: white;
  text-align: center;
  padding: 20px;
}

nav {
  display: flex;
  justify-content: center;
  background: #1b5e20;
}

nav a {
  color: white;
  padding: 15px;
  text-decoration: none;
}

nav a:hover {
  background: #388e3c;
}

section {
  padding: 40px;
  max-width: 900px;
  margin: auto;
}

#hero {
  background: url('img/hero.jpg') center/cover;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

button {
  margin: 10px;
  padding: 10px;
  cursor: pointer;
}

footer {
  text-align: center;
  background: #2e7d32;
  color: white;
  padding: 10px;
}
⚙️ script.js
function responder(correto) {
  const resultado = document.getElementById("resultado");

  if (correto) {
    resultado.innerHTML = "✅ Correto! A rotação de culturas preserva o solo.";
  } else {
    resultado.innerHTML = "❌ Errado! Queimadas prejudicam o meio ambiente.";
  }
}
🌿 3. IDEIAS PARA DEIXAR O PROJETO NOTA 10

Se quiser elevar MUITO o nível do seu trabalho, adicione:

🧠 Quiz com pontuação
🖼️ Carrossel de imagens (trigo/milho)
🌿 Cards de sustentabilidade
irrigação inteligente
rotação de culturas
biotecnologia
agricultura de precisão
🎬 Vídeo explicativo
📖 HQ (história em quadrinhos)
personagem: agricultor + estudante
explicando o ciclo do milho e trigo
🌟 4. DIFERENCIAL DO PROJETO (IMPORTANTE)

Você pode usar isso no README:

O projeto combina educação, tecnologia e sustentabilidade para demonstrar a importância do trigo e do milho na cadeia alimentar global, promovendo consciência ambiental e valorização do agronegócio brasileiro.

🚀 SE VOCÊ QUISER IR MAIS LONGE

Posso melhorar isso para você em nível “campeão de concurso”:

site MUITO mais bonito (UI moderna estilo Netflix/Apple)
animações CSS
quiz com múltiplas perguntas e ranking
carrossel automático
modo escuro
acessibilidade completa
README profissional igual projeto real do GitHub
versão pronta para GitHub Pages

Só me diga:
👉 “quero versão avançada”

Obtenha respostas mais inteligentes, carregamento de imagens e de arquivos e muito mais.
