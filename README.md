<!DOCTYPE html>
<html lang="pt-PT">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Enciclopédia completa sobre poluição - tipos, causas, impactos, soluções e legislação ambiental.">
  <title>Poluição - Enciclopédia Completa</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f4f4f4;
    }

    header {
      background: linear-gradient(135deg, #2E7D32 0%, #1B5E20 100%);
      color: white;
      padding: 3rem 2rem;
      text-align: center;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    }

    header p {
      font-size: 1.2rem;
      font-style: italic;
      opacity: 0.95;
    }

    nav {
      background-color: #1B5E20;
      padding: 0;
      position: sticky;
      top: 0;
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);
      z-index: 100;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 0;
      max-width: 1200px;
      margin: 0 auto;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 1rem 1.2rem;
      display: block;
      transition: all 0.3s ease;
      border-bottom: 3px solid transparent;
    }

    nav a:hover {
      background-color: #2E7D32;
      border-bottom-color: #4CAF50;
    }

    main {
      max-width: 1100px;
      margin: 2rem auto;
      padding: 0 1.5rem;
    }

    section {
      background: white;
      margin-bottom: 2.5rem;
      padding: 2.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      animation: fadeIn 0.5s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    section h2 {
      color: #1B5E20;
      margin-bottom: 1.5rem;
      border-bottom: 4px solid #2E7D32;
      padding-bottom: 0.8rem;
      font-size: 2rem;
    }

    section h3 {
      color: #2E7D32;
      margin-top: 2rem;
      margin-bottom: 1rem;
      font-size: 1.4rem;
    }

    p {
      margin-bottom: 1rem;
      text-align: justify;
      color: #444;
      line-height: 1.8;
    }

    ul, ol {
      margin-left: 2rem;
      margin-bottom: 1rem;
    }

    li {
      margin-bottom: 0.7rem;
      line-height: 1.7;
    }

    strong {
      color: #1B5E20;
      font-weight: bold;
    }

    .glossary {
      background-color: #f0f7f0;
      border-left: 4px solid #2E7D32;
      padding: 1rem;
      margin: 1rem 0;
      border-radius: 5px;
      font-style: italic;
      font-size: 0.9rem;
      color: #555;
    }

    .card-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      margin: 2rem 0;
    }

    .card {
      background: linear-gradient(135deg, #e8f5e9 0%, #c8e6c9 100%);
      padding: 1.5rem;
      border-radius: 10px;
      border-left: 5px solid #2E7D32;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 15px rgba(0,0,0,0.15);
    }

    .card h4 {
      color: #1B5E20;
      margin-bottom: 0.8rem;
      font-size: 1.2rem;
    }

    .card p {
      font-size: 0.95rem;
      margin: 0.5rem 0;
      text-align: left;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin: 1.5rem 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      font-size: 0.9rem;
    }

    table thead {
      background-color: #2E7D32;
      color: white;
    }

    table th {
      padding: 0.8rem;
      text-align: left;
      font-weight: bold;
    }

    table td {
      padding: 0.7rem 0.8rem;
      border-bottom: 1px solid #e0e0e0;
    }

    table tbody tr:hover {
      background-color: #f9f9f9;
    }

    table tbody tr:nth-child(odd) {
      background-color: #f5f5f5;
    }

    .stats {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5rem;
      margin: 2rem 0;
    }

    .stat-box {
      background: linear-gradient(135deg, #2E7D32 0%, #1B5E20 100%);
      color: white;
      padding: 2rem;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    .stat-box .number {
      font-size: 2.5rem;
      font-weight: bold;
      display: block;
      margin-bottom: 0.5rem;
    }

    .stat-box .label {
      font-size: 0.95rem;
      opacity: 0.9;
    }

    .highlight {
      background-color: #fff3cd;
      border-left: 5px solid #FFD700;
      padding: 1.5rem;
      margin: 1.5rem 0;
      border-radius: 5px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .warning-box {
      background-color: #ffebee;
      border-left: 5px solid #f44336;
      padding: 1.5rem;
      margin: 1.5rem 0;
      border-radius: 5px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .solution-box {
      background-color: #e8f5e9;
      border-left: 5px solid #4CAF50;
      padding: 1.5rem;
      margin: 1.5rem 0;
      border-radius: 5px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 2.5rem;
      margin-top: 3rem;
    }

    footer h3 {
      color: white;
      margin-bottom: 1rem;
    }

    footer p {
      margin: 0.5rem 0;
      color: #ccc;
      text-align: center;
    }

    footer ul {
      list-style: none;
      margin-left: 0;
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      flex-wrap: wrap;
    }

    footer a {
      color: #4CAF50;
      text-decoration: none;
      transition: color 0.3s;
    }

    footer a:hover {
      color: white;
      text-decoration: underline;
    }

    .btn {
      display: inline-block;
      background-color: #2E7D32;
      color: white;
      padding: 0.8rem 1.5rem;
      border-radius: 5px;
      text-decoration: none;
      transition: all 0.3s;
      border: none;
      cursor: pointer;
      font-size: 1rem;
      margin-top: 1rem;
      margin-right: 0.5rem;
    }

    .btn:hover {
      background-color: #1B5E20;
      transform: translateY(-2px);
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    #backToTop {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #2E7D32;
      color: white;
      border: none;
      padding: 1rem;
      border-radius: 50%;
      cursor: pointer;
      font-size: 1.5rem;
      display: none;
      z-index: 100;
      transition: all 0.3s ease;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    #backToTop.show {
      display: block;
    }

    #backToTop:hover {
      background-color: #1B5E20;
      transform: translateY(-5px);
    }

    @media (max-width: 768px) {
      header h1 { font-size: 2rem; }
      nav ul { flex-direction: column; }
      section { padding: 1.5rem; }
      .card-grid { grid-template-columns: 1fr; }
      .stats { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
  <button id="backToTop" aria-label="Voltar ao topo" title="Voltar ao topo">↑</button>

  <header>
    <h1>🌍 Poluição - Enciclopédia Completa</h1>
    <p>Compreenda as causas, impactos e soluções para um planeta mais limpo</p>
  </header>

  <nav>
    <ul>
      <li><a href="#introduction">Introdução</a></li>
      <li><a href="#types">Tipos</a></li>
      <li><a href="#air">Ar</a></li>
      <li><a href="#water">Água</a></li>
      <li><a href="#soil">Solo</a></li>
      <li><a href="#noise">Sonora</a></li>
      <li><a href="#impacts">Impactos</a></li>
      <li><a href="#solutions">Soluções</a></li>
      <li><a href="#laws">Legislação</a></li>
      <li><a href="#future">Futuro</a></li>
    </ul>
  </nav>

  <main>
    <section id="introduction">
      <h2>📖 Introdução à Poluição</h2>
      <p><strong>O que é Poluição?</strong> A introdução de substâncias ou energia no ambiente que prejudicam organismos vivos. Pode ser visível (fumo, plástico) ou invisível (gases, radiação).</p>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>Propriedades Biológicas</strong> - características dos seres vivos, como reprodução, fotossíntese e metabolismo (processos químicos).
      </div>

      <div class="highlight">
        <strong>⚠️ FACTO CRÍTICO:</strong> A poluição causa <strong>9 MILHÕES de mortes prematuras por ano</strong> - mais que malária, tuberculose e VIH/SIDA juntos!
      </div>

      <h3>Origens da Poluição</h3>
      <ul>
        <li><strong>Fontes Naturais (10%):</strong> Vulcões, tempestades de poeira, decomposição</li>
        <li><strong>Fontes Antrópicas (90%):</strong> Actividades humanas - indústria, transporte, agricultura, energia</li>
      </ul>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>Antrópicas</strong> - causadas por seres humanos (do grego "anthropos" = homem).
      </div>

      <div class="stats">
        <div class="stat-box">
          <span class="number">92%</span>
          <span class="label">População Respirando Ar Acima dos Limites OMS</span>
        </div>
        <div class="stat-box">
          <span class="number">2 mil milhões</span>
          <span class="label">Pessoas sem Água Potável Segura</span>
        </div>
        <div class="stat-box">
          <span class="number">5 triliões</span>
          <span class="label">Fragmentos de Plástico nos Oceanos</span>
        </div>
        <div class="stat-box">
          <span class="number">€4,6 biliões</span>
          <span class="label">Custo Anual de Danos Ambientais</span>
        </div>
      </div>
    </section>

    <section id="types">
      <h2>🔬 Tipos de Poluição</h2>
      <div class="card-grid">
        <div class="card">
          <h4>💨 Poluição do Ar</h4>
          <p><strong>O que é:</strong> Gases tóxicos, vapores e partículas na atmosfera.</p>
          <p><strong>Poluentes:</strong> CO₂, CO, NO₂, SO₂, PM2.5, ozono troposférico.</p>
          <p><strong>Afecta:</strong> Saúde respiratória, clima global.</p>
        </div>

        <div class="card">
          <h4>💧 Poluição da Água</h4>
          <p><strong>O que é:</strong> Contaminação de rios, lagos, oceanos e aquíferos.</p>
          <p><strong>Poluentes:</strong> Metais pesados, plástico, pesticidas, esgoto.</p>
          <p><strong>Afecta:</strong> Água potável, peixes, recifes de coral.</p>
        </div>

        <div class="card">
          <h4>🌱 Poluição do Solo</h4>
          <p><strong>O que é:</strong> Contaminação da camada superficial de terra.</p>
          <p><strong>Poluentes:</strong> Mercúrio, chumbo, pesticidas, plástico.</p>
          <p><strong>Afecta:</strong> Produção de alimentos, segurança alimentar.</p>
        </div>

        <div class="card">
          <h4>🔊 Poluição Sonora</h4>
          <p><strong>O que é:</strong> Ruído excessivo que prejudica organismos vivos.</p>
          <p><strong>Níveis:</strong> Acima de 55dB durante o dia é poluição.</p>
          <p><strong>Afecta:</strong> Audição, sono, comportamento animal.</p>
        </div>

        <div class="card">
          <h4>☢️ Poluição Radioactiva</h4>
          <p><strong>O que é:</strong> Radiação ionizante que danifica ADN.</p>
          <p><strong>Fontes:</strong> Usinas nucleares, acidentes, testes antigos.</p>
          <p><strong>Afecta:</strong> Cancro, mutações genéticas, infertilidade.</p>
        </div>

        <div class="card">
          <h4>💡 Poluição Luminosa</h4>
          <p><strong>O que é:</strong> Excesso de luz artificial que altera ciclos naturais.</p>
          <p><strong>Efeitos:</strong> Desorientação de aves, confunde insectos.</p>
          <p><strong>Afecta:</strong> Navegação animal, ciclos de reprodução.</p>
        </div>

        <div class="card">
          <h4>🧪 Poluição Química</h4>
          <p><strong>O que é:</strong> Produtos químicos tóxicos sintéticos no ambiente.</p>
          <p><strong>Exemplos:</strong> PFAS, BPA, dioxinas.</p>
          <p><strong>Afecta:</strong> Sistema reprodutivo, hormônios, imunidade.</p>
        </div>

        <div class="card">
          <h4>🦠 Poluição Biológica</h4>
          <p><strong>O que é:</strong> Organismos patogénicos que causam doenças.</p>
          <p><strong>Fontes:</strong> Esgoto não tratado, criação intensiva.</p>
          <p><strong>Afecta:</strong> Saúde gastrointestinal, disenteria, cólera.</p>
        </div>
      </div>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>Ionizante</strong> - radiação que remove electrões, danificando ADN. <strong>Patogénico</strong> - que causa doença. <strong>ADN</strong> - Ácido Desoxirribonucleico, molécula com instruções genéticas.
      </div>
    </section>

    <section id="air">
      <h2>💨 Poluição do Ar - Análise Detalhada</h2>
      <p>A poluição ocorre principalmente na troposfera (0-12km), onde vivemos. Poluentes podem viajar globalmente - uma partícula de Xangai chega à Califórnia em 5-7 dias!</p>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>Troposfera</strong> - camada mais baixa da atmosfera onde ocorrem fenómenos meteorológicos.
      </div>

      <h3>Principais Poluentes Atmosféricos</h3>
      <table>
        <thead>
          <tr>
            <th>Poluente</th>
            <th>Fórmula</th>
            <th>Fontes</th>
            <th>Concentração</th>
            <th>Impacto</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>CO₂</strong></td>
            <td>Dióxido de Carbono</td>
            <td>Combustíveis fósseis, indústria</td>
            <td>420 ppm</td>
            <td>Aquecimento global principal agente</td>
          </tr>
          <tr>
            <td><strong>CO</strong></td>
            <td>Monóxido de Carbono</td>
            <td>Combustão incompleta, veículos</td>
            <td>0.5 ppm</td>
            <td>Reduz oxigénio no sangue</td>
          </tr>
          <tr>
            <td><strong>NO₂</strong></td>
            <td>Dióxido de Nitrogénio</td>
            <td>Veículos diesel, queimadores</td>
            <td>0.05-0.1 ppm</td>
            <td>Irritação vias aéreas, asma</td>
          </tr>
          <tr>
            <td><strong>SO₂</strong></td>
            <td>Dióxido de Enxofre</td>
            <td>Usinas termoelétricas</td>
            <td>0.01-0.05 ppm</td>
            <td>Chuva ácida, danifica estruturas</td>
          </tr>
          <tr>
            <td><strong>PM2.5</strong></td>
            <td>Partículas Finas</td>
            <td>Combustão, construção</td>
            <td>10 μg/m³</td>
            <td>Penetra pulmões, inflamação sistémica</td>
          </tr>
        </tbody>
      </table>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>PPM</strong> - partes por milhão (1 milionésimo). <strong>μg/m³</strong> - microgramas por metro cúbico. <strong>Sistémica</strong> - que afecta o corpo inteiro.
      </div>
    </section>

    <section id="water">
      <h2>💧 Poluição da Água - Análise Profunda</h2>
      <p>Tudo o que entra num rio chega ao oceano. Tudo que entra no solo infiltra-se em aquíferos subterrâneos que fornecem água potável a mil milhões.</p>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>Bioacumulação</strong> - contaminante aumenta concentração ao subir cadeia alimentar. Um predador concentra toxinas de todas presas. <strong>Cadeia alimentar</strong> - sequência: algas → peixe pequeno → peixe grande → humano.
      </div>

      <h3>Principais Contaminantes</h3>
      <div class="card-grid">
        <div class="card">
          <h4>🪨 Metais Pesados</h4>
          <p><strong>Exemplos:</strong> Mercúrio, chumbo, arsênico, cádmio.</p>
          <p><strong>Problema:</strong> Não biodegradáveis - permanecem para sempre.</p>
          <p><strong>Bioacumulação:</strong> Concentração aumenta 100x ou 1000x na cadeia alimentar.</p>
          <p><strong>Impacto:</strong> Mercúrio = tremores, demência. Chumbo = QI baixo em crianças.</p>
        </div>

        <div class="card">
          <h4>🌿 Nutrientes Excessivos</h4>
          <p><strong>Tipos:</strong> Nitratos, fosfatos de fertilizantes.</p>
          <p><strong>Processo:</strong> Crescimento explosivo de algas (eutrofização).</p>
          <p><strong>Consequência:</strong> Algas morrem, bactérias consomem oxigénio.</p>
          <p><strong>Resultado:</strong> Zonas mortas onde peixes não conseguem viver.</p>
        </div>

        <div class="card">
          <h4>🧬 Pesticidas e Herbicidas</h4>
          <p><strong>Exemplos:</strong> Glifosato, neonicotinoides.</p>
          <p><strong>Persistência:</strong> Residem em sedimentos por anos.</p>
          <p><strong>Efeito:</strong> Disruptores endócrinos - imitam hormônios.</p>
          <p><strong>Impacto:</strong> Girinos mudam de sexo, peixes ficam inférteis.</p>
        </div>

        <div class="card">
          <h4>♻️ Plásticos e Microplásticos</h4>
          <p><strong>Quantidade:</strong> 10 MILHÕES de toneladas entram nos oceanos anualmente!</p>
          <p><strong>Problemas:</strong> Tartarugas confundem sacolas com algas marinhas.</p>
          <p><strong>Microplásticos:</strong> Fragmentos menores que 5mm penetram organismos.</p>
          <p><strong>Seu Corpo:</strong> Consome em média 5g de plástico por semana!</p>
        </div>
      </div>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>Eutrofização</strong> - enriquecimento excessivo com nutrientes. <strong>Disruptores endócrinos</strong> - imitam hormônios, confundem sistema reprodutivo.
      </div>
    </section>

    <section id="soil">
      <h2>🌱 Poluição do Solo</h2>
      <p>Um centímetro de solo leva 100 ANOS para se formar naturalmente, mas pode ser destruído em uma estação agrícola! O solo produz 99% da comida mundial.</p>

      <h3>Contaminantes do Solo - Persistência e Riscos</h3>
      <table>
        <thead>
          <tr>
            <th>Contaminante</th>
            <th>Fonte</th>
            <th>Persistência</th>
            <th>Risco Humano</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Chumbo (Pb)</strong></td>
            <td>Gasolina antiga, baterias, munição</td>
            <td>PERMANENTE</td>
            <td>QI reduzido em crianças, comportamento agressivo</td>
          </tr>
          <tr>
            <td><strong>Mercúrio (Hg)</strong></td>
            <td>Minas de ouro, termómetros</td>
            <td>PERMANENTE</td>
            <td>Tremores, demência, morte em altas doses</td>
          </tr>
          <tr>
            <td><strong>Arsênico (As)</strong></td>
            <td>Pesticidas históricos, minas</td>
            <td>PERMANENTE</td>
            <td>Cancro de pele e pulmão</td>
          </tr>
          <tr>
            <td><strong>PFAS</strong></td>
            <td>Teflon, espuma de combate incêndio</td>
            <td>NUNCA DEGRADA</td>
            <td>Reduz imunidade, afecta tiróide, aumenta colesterol</td>
          </tr>
        </tbody>
      </table>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>PFAS</strong> - Substâncias Perfluoradas e Polifluoradas, compostos sintéticos que NUNCA se degradam naturalmente. Encontrados em 97% da população humana! <strong>Tiróide</strong> - glândula que regula metabolismo.
      </div>
    </section>

    <section id="noise">
      <h2>🔊 Poluição Sonora - Análise Detalhada</h2>
      <p>Som é vibração no ar. Ouvido humano detecta 20-20.000 Hz. Cada aumento de 10dB = 10 vezes mais energia sonora (escala logarítmica).</p>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>Hz (Hertz)</strong> - unidade de frequência. 1 Hz = 1 oscilação por segundo. Sons baixos = menos Hz, sons agudos = mais Hz.
      </div>

      <h3>Escala Completa de Ruído em Decibéis</h3>
      <table>
        <thead>
          <tr>
            <th>dB</th>
            <th>Fonte Típica</th>
            <th>Efeito no Corpo</th>
            <th>Tempo Máximo Seguro</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>0</td>
            <td>Limiar da audição</td>
            <td>Imperceptível</td>
            <td>Infinito</td>
          </tr>
          <tr>
            <td>30</td>
            <td>Sussurro, biblioteca</td>
            <td>Relaxante</td>
            <td>Infinito</td>
          </tr>
          <tr>
            <td>50</td>
            <td>Conversação normal</td>
            <td>Normal</td>
            <td>Infinito</td>
          </tr>
          <tr>
            <td>70</td>
            <td>Tráfego urbano</td>
            <td>Desconfortável</td>
            <td>Infinito (fadiga)</td>
          </tr>
          <tr>
            <td>85</td>
            <td>Cortador de relva, metrô</td>
            <td>Perda auditiva</td>
            <td>8 horas máximo</td>
          </tr>
          <tr>
            <td>100</td>
            <td>Concerto, discoteca</td>
            <td>Perda auditiva PERMANENTE</td>
            <td>15 minutos máximo</td>
          </tr>
          <tr>
            <td>120</td>
            <td>Decolagem avião, trovão</td>
            <td>Dor; dano GARANTIDO</td>
            <td>Nenhum tempo seguro</td>
          </tr>
        </tbody>
      </table>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>Decibel (dB)</strong> - unidade de intensidade sonora. Escala logarítmica, não linear.
      </div>
    </section>

    <section id="impacts">
      <h2>⚠️ Impactos da Poluição na Saúde</h2>
      
      <h3>Doenças Causadas por Poluição</h3>
      <ul>
        <li><strong>Respiratórias:</strong> Asma, DPOC (Doença Pulmonar Obstrutiva Crónica), tuberculose, fibrose pulmonar</li>
        <li><strong>Cardiovasculares:</strong> Enfarte, acidente vascular, hipertensão</li>
        <li><strong>Cancro:</strong> Principalmente pulmão, pele, tiróide</li>
        <li><strong>Reprodutivas:</strong> Infertilidade, abortos, má formação fetal</li>
        <li><strong>Neurológicas:</strong> Alzheimer, Parkinson associados a poluição do ar</li>
      </ul>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>DPOC</strong> - grupo de doenças pulmonares incluindo enfisema (destruição dos alvéolos) e bronquite crónica.
      </div>

      <div class="warning-box">
        <strong>⚠️ ESTATÍSTICAS ALARMANTES:</strong> 1 em cada 8 mortes mundiais associada a poluição = 9 MILHÕES mortes/ano!
      </div>
    </section>

    <section id="solutions">
      <h2>✅ Soluções e Prevenção</h2>
      
      <h3>Tecnologias Inovadoras</h3>
      <div class="card-grid">
        <div class="card">
          <h4>⚡ Energias Renováveis</h4>
          <p>Solar, eólica, hidrelétrica, geotérmica reduzem emissões.</p>
        </div>

        <div class="card">
          <h4>🚗 Veículos Elétricos</h4>
          <p>Reduzem poluição urbana e dependência de combustíveis.</p>
        </div>

        <div class="card">
          <h4>🏭 Filtros Avançados</h4>
          <p>Filtros HEPA e precipitadores electrostáticos.</p>
        </div>

        <div class="card">
          <h4>🌿 Plantas Purificadoras</h4>
          <p>Absorvem CO₂ e libertam O₂.</p>
        </div>

        <div class="card">
          <h4>♻️ Reciclagem Eficiente</h4>
          <p>Incineração controlada, compostagem, reprocessamento.</p>
        </div>

        <div class="card">
          <h4>💧 Tratamento de Água</h4>
          <p>Purificação em múltiplas etapas avançadas.</p>
        </div>
      </div>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>Filtro HEPA</strong> - High Efficiency Particulate Air, remove 99.97% de partículas até 0.3 micrómtros.
      </div>

      <h3>Acções Individuais</h3>
      <ul>
        <li>Usar transporte público, bicicleta ou caminhar</li>
        <li>Consumir menos plástico, usar sacos/garrafas reutilizáveis</li>
        <li>Reduzir carne vermelha (causa gases de efeito estufa)</li>
        <li>Separar lixo para reciclagem</li>
        <li>Economizar água e energia</li>
        <li>Apoiar empresas sustentáveis</li>
        <li>Plantar árvores</li>
      </ul>

      <div class="solution-box">
        <strong>✅ Sucesso Global:</strong> Desde 1990, qualidade do ar melhorou em vários países com regulações e tecnologias limpas!
      </div>
    </section>

    <section id="laws">
      <h2>⚖️ Legislação e Acordos Internacionais</h2>
      
      <h3>Principais Acordos Globais</h3>
      <table>
        <thead>
          <tr>
            <th>Acordo</th>
            <th>Ano</th>
            <th>Objectivo</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td><strong>Protocolo de Kyoto</strong></td>
            <td>1997</td>
            <td>Reduzir emissões de gases efeito estufa em 5%</td>
          </tr>
          <tr>
            <td><strong>Acordo de Paris</strong></td>
            <td>2015</td>
            <td>Limitar aquecimento global a 1,5-2°C</td>
          </tr>
          <tr>
            <td><strong>Protocolo de Montreal</strong></td>
            <td>1987</td>
            <td>Proteger camada de ozono</td>
          </tr>
        </tbody>
      </table>

      <div class="glossary">
        <strong>📚 GLOSSÁRIO:</strong> <strong>Camada de ozono</strong> - camada protectora que bloqueia radiação ultravioleta do sol, que causa cancro de pele.
      </div>

      <h3>Legislação Nacional (Portugal)</h3>
      <ul>
        <li><strong>Decreto-Lei 102/2010:</strong> Poluição Sonora</li>
        <li><strong>Lei da Qualidade do Ar:</strong> Padrões de qualidade do ar</li>
        <li><strong>Lei da Água (Lei 58/2005):</strong> Protecção de recursos hídricos</li>
        <li><strong>Código do Ambiente:</strong> Enquadramento ambiental geral</li>
        <li><strong>Estratégia de Gestão de Resíduos 2030:</strong> Redução e reciclagem</li>
      </ul>
    </section>

    <section id="future">
      <h2>🔮 Futuro e Inovações Emergentes</h2>
      
      <div class="card-grid">
        <div class="card">
          <h4>🤖 Inteligência Artificial</h4>
          <p>Monitorar poluição em tempo real e optimizar processos.</p>
        </div>

        <div class="card">
          <h4>🧪 Bioplásticos</h4>
          <p>Plásticos degradáveis de algas, cana-de-açúcar e plantas.</p>
        </div>

        <div class="card">
          <h4>🔬 Fusão Nuclear</h4>
          <p>Energia limpa e ilimitada para substituir combustíveis.</p>
        </div>

        <div class="card">
          <h4>🌍 Captura de Carbono</h4>
          <p>Remover CO₂ da atmosfera em larga escala industrial.</p>
        </div>

        <div class="card">
          <h4>🐟 Limpeza de Oceanos</h4>
          <p>Projectos como "Ocean Cleanup" para remover plástico.</p>
        </div>

        <div class="card">
          <h4>🌱 Cidades Inteligentes</h4>
          <p>Urbanismo sustentável com energia renovável e transporte limpo.</p>
        </div>
      </div>

      <div class="solution-box">
        <strong>✅ Esperança:</strong> Progressos tecnológicos e políticas agressivas mostram que é POSSÍVEL reverter a poluição com acção coordenada!
      </div>
    </section>

    <section>
      <h2>📧 Contribua para a Mudança</h2>
      <p>Apoie organizações que trabalham pela redução de poluição:</p>
      <a href="https://www.greenpeace.org" target="_blank" class="btn">🌍 Greenpeace</a>
      <a href="https://www.worldwildlife.org" target="_blank" class="btn">🦁 WWF</a>
      <a href="https://www.theoceancleanup.com" target="_blank" class="btn">🌊 Ocean Cleanup</a>
    </section>
  </main>

  <footer>
    <h3>🌍 Poluição - Enciclopédia Completa</h3>
    <p>&copy; 2026 - Enciclopédia Ambiental. Todos os direitos reservados.</p>
    <p>Informações baseadas em dados científicos, relatórios da ONU, OMS e organizações ambientais internacionais.</p>
    
    <h3 style="margin-top: 1.5rem;">Links Úteis</h3>
    <ul>
      <li><a href="#introduction">Sobre</a></li>
      <li><a href="#solutions">Soluções</a></li>
      <li><a href="#laws">Legislação</a></li>
      <li><a href="#future">Futuro</a></li>
    </ul>

    <p style="margin-top: 1.5rem; font-size: 0.9rem;">Desenvolvido com ❤️ para educação ambiental</p>
  </footer>

  <script>
    const backToTopBtn = document.getElementById('backToTop');
    window.addEventListener('scroll', () => {
      if (window.pageYOffset > 300) {
        backToTopBtn.classList.add('show');
      } else {
        backToTopBtn.classList.remove('show');
      }
    });

    backToTopBtn.addEventListener('click', () => {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    });
  </script>
</body>
</html>
