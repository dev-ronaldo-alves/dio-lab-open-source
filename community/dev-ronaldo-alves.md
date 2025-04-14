<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    }

    .card {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(12px);
      border-radius: 20px;
      padding: 3rem 2rem;
      text-align: center;
      box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
      border: 1px solid rgba(255, 255, 255, 0.18);
      max-width: 400px;
      width: 90%;
      animation: fadeIn 1.5s ease-in-out;
    }

    .card h1 {
      font-size: 1.8rem;
      margin-bottom: 1rem;
      animation: pulse 2s infinite;
    }

    .card p {
      margin: 0.5rem 0;
      font-size: 1rem;
      opacity: 0.9;
    }

    .contact-btn {
      display: inline-block;
      margin-top: 1.5rem;
      padding: 0.8rem 1.2rem;
      background: #38bdf8;
      color: #0f172a;
      border: none;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s ease;
    }

    .contact-btn:hover {
      background: #0ea5e9;
      color: white;
    }

    .cursor {
      color: #38bdf8;
      animation: blink 1s step-end infinite;
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.05); }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    @keyframes blink {
      from, to { opacity: 0 }
      50% { opacity: 1 }
    }
    .whatsapp {
  margin-top: 2rem;
}

.whatsapp-btn {
  display: inline-block;
  background-color: #25d366;
  color: #fff;
  padding: 0.8rem 1.2rem;
  border-radius: 8px;
  font-weight: bold;
  text-decoration: none;
  transition: background 0.3s ease;
  font-size: 1rem;
  box-shadow: 0 4px 15px rgba(37, 211, 102, 0.3);
}

.whatsapp-btn:hover {
  background-color: #1ebe5d;
}

    
  </style>
</head>
<body>
  <main class="card">
    <h1 id="typewriter"></h1>
    <p><h1> DEV Ronaldo Alves</h1>
    <p>💻 HTML5 • CSS3 • JavaScript • PHP • Python</p>
    <p>🤖 IA • Projetos • Criatividade</p>
    <a href="mailto:dev.ronaldoalves@gmail.com" class="contact-btn">📩 Fale comigo</a>

<section class="whatsapp">
  <a href="https://wa.me/5544991563832" target="_blank" class="whatsapp-btn">
    <span>💬 Fale no WhatsApp</span>
  </a>
</section>

    <p><h2>Habilidades</h2>
    <section class="skills">
  <h2>🧠 Minhas Habilidades</h2>
  <p>
    Como <strong>Desenvolvedor Web</strong>, domino tecnologias essenciais como <strong>HTML5, CSS3, JavaScript</strong> e <strong>PHP</strong>,
    criando interfaces modernas, responsivas e funcionais. Tenho experiência prática no desenvolvimento de sites, sistemas web e aplicações dinâmicas, sempre com foco em performance e usabilidade. 
  </p>
  <p>
    Atualmente estou expandindo meus conhecimentos em <strong>Python</strong>, com foco em automações e aplicações envolvendo <strong>Inteligência Artificial</strong>,
    áreas que despertam meu entusiasmo e curiosidade.
  </p>
  <p>
    Além das linguagens, possuo boa comunicação, organização e gosto de trabalhar em equipe, colaborando em soluções que realmente fazem a diferença.
  </p>
</section>

    <section class="contrib">
  <h2>🌟 Minhas Contribuições</h2>
  <ul>
    <li>✅ Participo de projetos open-source no GitHub.</li>
    <li>🧠 Compartilho conhecimentos sobre desenvolvimento web e IA.</li>
    <li>💬 Auxilio a comunidade em fóruns como Stack Overflow e GitHub Discussions.</li>
    <li>📦 Criei repositórios com soluções em HTML, CSS, JS e PHP.</li>
    <li>🚀 Estou aprendendo Python e aplicando em automações e IA.</li>
  </ul>
</section>

  </main>

  </body>
</html>
