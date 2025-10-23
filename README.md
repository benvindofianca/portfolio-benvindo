<!doctype html>
<html lang="pt-PT">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Portfólio — Benvindo Fiança Figueiredo Marimba</title>
  <link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;700&family=Roboto+Slab:wght@500&display=swap" rel="stylesheet">
  <style>
    :root{--bg:#f8fafc;--card:#ffffff;--accent:#004b8d;--muted:#555;--border:#e0e0e0}
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:'Lato', sans-serif;background:var(--bg);color:#1a1a1a;line-height:1.6}
    .container{max-width:1000px;margin:40px auto;padding:20px}
    header{display:flex;align-items:center;gap:20px;background:var(--card);padding:20px;border-radius:12px;box-shadow:0 4px 12px rgba(0,0,0,0.05)}
    header img{width:110px;height:110px;border-radius:12px;object-fit:cover;border:3px solid var(--accent)}
    .info h1{font-family:'Roboto Slab',serif;font-size:24px;color:var(--accent)}
    .subtitle{font-size:15px;color:var(--muted);margin-top:4px}
    .contacts{margin-top:8px;display:flex;flex-wrap:wrap;gap:8px}
    .contacts span{font-size:14px;color:var(--muted)}
    main{margin-top:20px;display:grid;grid-template-columns:2fr 1fr;gap:20px}
    section{background:var(--card);padding:20px;border-radius:12px;box-shadow:0 4px 10px rgba(0,0,0,0.04)}
    h2{color:var(--accent);font-family:'Roboto Slab',serif;font-size:18px;margin-bottom:8px}
    ul{margin-left:18px}
    li{margin-bottom:6px}
    .skills, .certs{display:grid;grid-template-columns:1fr 1fr;gap:6px}
    .pill{background:#f2f6fa;padding:6px 10px;border-radius:6px;border:1px solid var(--border);font-size:13px;color:#1a1a1a}
    .project{margin-top:12px}
    .project img{width:100%;height:150px;object-fit:cover;border-radius:10px;border:1px solid var(--border);margin-bottom:8px}
    footer{text-align:center;margin-top:30px;font-size:13px;color:var(--muted)}
    a{color:var(--accent);text-decoration:none}
    @media(max-width:860px){main{grid-template-columns:1fr}header{flex-direction:column;align-items:flex-start}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <!-- Foto profissional -->
      <img src="1.jpg" alt="Foto de Benvindo Fiança" />
      <div class="info">
        <h1>Benvindo Fiança Figueiredo Marimba</h1>
        <div class="subtitle">Técnico Médio de Informática — Redes | Infraestrutura | Windows Server</div>
        <div class="contacts">
          <span>📍 Luanda, Angola</span>
          <span>✉️ benvindofianca@gmail.com</span>
          <span>📞 +244 926 052 415</span>
          <span>🔗 <a href="https://www.linkedin.com/in/benvindo-fian%C3%A7a-126267327" target="_blank">LinkedIn</a></span>
        </div>
      </div>
    </header>

    <main>
      <div>
        <section>
          <h2>💼 Perfil Profissional</h2>
          <p>Sou Técnico Médio de Informática com experiência prática em redes, infraestrutura de TI e programação. Tenho sólida formação pelo Instituto de Telecomunicações e experiência de estágio no Instituto de Telecomunicações e INFOSI. Domino redes (CCNA 1 e 2), reparação de equipamentos e administração de servidores Windows Server. Caracterizo-me por ser proativo, dedicado e com boa capacidade de trabalho em equipa.</p>
        </section>

        <section>
          <h2>🧰 Experiência Profissional</h2>
          <ul>
            <li><b>Instituto de Telecomunicações</b> — Estágio em Infraestrutura (2023)<br/>Instalação e manutenção de redes, suporte técnico e resolução de falhas.</li>
            <li><b>INFOSI</b> — Estágio em Infraestrutura (2024)<br/>Administração de servidores Windows Server, gestão de rede e manutenção de equipamentos.</li>
          </ul>
        </section>

        <section>
          <h2>🎓 Formação Académica</h2>
          <p><b>Instituto de Telecomunicações</b> — Técnico Médio de Informática (2024/2025)<br/>Áreas principais: Redes (CCNA 1 e 2), Programação, Sistemas Operativos e Reparação de Equipamentos.</p>
        </section>

        <section>
          <h2>📜 Certificações</h2>
          <div class="certs">
            <div class="pill">CCNA 1 – Introduction to Networks</div>
            <div class="pill">CCNA 2 – Switching, Routing & Wireless</div>
            <div class="pill">Windows Server Administration</div>
          </div>
        </section>

        <section>
          <h2>💻 Portfólio de Projetos</h2>
          <div class="project">
            <img src="imagem_pgdi.jpg" alt="Projeto PGDI">
            <b>Plataforma de Gestão Documental Integrada (PGDI)</b>
            <p>Plataforma web para armazenamento e gestão de documentos de diferentes formatos, permitindo visualização direta no navegador e organização eficiente de ficheiros.</p>
          </div>
          <div class="project">
            <img src="imagem_profissionais.jpg" alt="Plataforma de Profissionais Técnicos">
            <b>Plataforma de Profissionais Técnicos</b>
            <p>Sistema web que conecta técnicos de diversas áreas (TI, programação, advocacia, etc.) a clientes, facilitando a procura e oferta de serviços especializados.</p>
          </div>
        </section>
      </div>

      <aside>
        <section>
          <h2>⚙️ Competências Técnicas</h2>
          <div class="skills">
            <div class="pill">Redes de Computadores (CCNA)</div>
            <div class="pill">Windows Server</div>
            <div class="pill">Packet Tracer / VirtualBox</div>
            <div class="pill">Configuração de Switches e Routers</div>
            <div class="pill">Reparação de Equipamentos</div>
            <div class="pill">Python, HTML, CSS, JavaScript</div>
          </div>
        </section>

        <section>
          <h2>🤝 Soft Skills</h2>
          <ul>
            <li>Trabalho em equipa</li>
            <li>Responsabilidade e proatividade</li>
            <li>Boa comunicação</li>
            <li>Aprendizado rápido</li>
            <li>Resolução de problemas técnicos</li>
          </ul>
        </section>

        <section>
          <h2>🎯 Objetivo Profissional</h2>
          <p>Atuar na área de Infraestrutura de Redes e Sistemas, aplicando conhecimentos técnicos para propor soluções eficientes e contribuir para o desenvolvimento tecnológico das instituições.</p>
        </section>
      </aside>
    </main>

    <footer>
      <p>© 2025 Benvindo Fiança Figueiredo Marimba — Portfólio Profissional. Desenvolvido em estilo clássico.</p>
    </footer>
  </div>
</body>
</html>
