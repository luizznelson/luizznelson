<h1 align="center">Luiz Nelson dos Santos Lima</h1>

<p align="center">
  <strong>Analista de Automação & Inteligência de Processos</strong>
</p>

<p align="center">
  Dados & Analytics · Automação · IA Aplicada
</p>

<p align="center">
  Diagnostico problemas operacionais e construo soluções com dados, automação e IA<br>
  para tornar processos mais eficientes, mensuráveis e inteligentes.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/luiznelson">
    <img src="https://img.shields.io/badge/LinkedIn-luiznelson-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:luizznelsonpro@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contato-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://luizznelson.github.io">
    <img src="https://img.shields.io/badge/Portfólio-Web-181717?style=flat-square&logo=github&logoColor=white" alt="Portfólio">
  </a>
</p>

Sobre mim

Atuo na interseção entre processos, dados e tecnologia.

Meu trabalho começa entendendo como uma operação funciona: quais são suas regras, onde estão os gargalos, quais dados explicam seu desempenho e quais atividades poderiam ser executadas de forma mais eficiente.

A partir desse diagnóstico, construo soluções envolvendo automação de processos, análise de dados, integração de sistemas e IA aplicada.

<p align="center">
  <strong>Problema → Diagnóstico → Dados → Solução → Implementação → Medição</strong>
</p>

Tenho experiência com Python, SQL, Power BI, APIs REST, FastAPI, PostgreSQL, automação, BPMN, LLMs e LangChain, além de levantamento de requisitos, definição de regras de negócio, testes, homologação e acompanhamento dos resultados das soluções implantadas.

Atualmente curso Mestrado em Ciência da Computação na Universidade Federal do Piauí (UFPI) e também atuo em pesquisa aplicada.

Projetos em destaque

📊 Competitive Intelligence Agent

Da coleta de preços públicos à inteligência competitiva

Sistema desenvolvido para responder a um problema de negócio:

Como substituir o monitoramento manual de concorrentes por uma rotina estruturada, rastreável e capaz de indicar quais produtos e fontes merecem atenção?

O projeto monitora produtos equivalentes em KaBuM!, Pichau e TerabyteShop, registra preço e disponibilidade, mantém histórico e transforma as observações em indicadores comparáveis.

<p align="center">
  <strong>Discovery → Matching → Coleta → Validação → Histórico → Analytics → MCP → AI Analyst</strong>
</p>

O que foi construído

catálogo com 100 produtos canônicos;

225 ofertas ativas monitoradas em três fontes principais;

Product Discovery baseado em sitemaps públicos;

matching por MPN, modelo e identidade canônica;

coleta HTTP com retry, backoff e fallback via Playwright;

tratamento separado de falha de coleta, indisponibilidade e oferta disponível;

histórico de preço e disponibilidade;

analytics determinístico para menor preço, mediana, dispersão percentual, disponibilidade, liderança de preço e movimentos entre coletas;

servidor MCP com ferramentas estruturadas;

Analista de IA utilizando Groq para investigação dos dados;

dashboard executivo em Streamlit;

snapshot SQLite real para demonstração pública somente leitura;

testes automatizados.

Decisão arquitetural

O LLM não calcula os indicadores de mercado.

Preço, disponibilidade, dispersão e variações são calculados deterministicamente. A IA recebe essas evidências através de ferramentas e atua na investigação e síntese.

<p>
  <a href="https://github.com/luizznelson/competitive-intelligence-agent">
    <img src="https://img.shields.io/badge/GitHub-Repositório-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://competitive-intelligence-agent.streamlit.app/">
    <img src="https://img.shields.io/badge/Live%20Demo-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Live Demo">
  </a>
</p>

Python Pandas PostgreSQL SQLite Requests Playwright Streamlit Plotly MCP Groq Docker Pytest

⚙️ Industrial Hydraulic DataOps

De sinais industriais heterogêneos a uma base analítica confiável

Pipeline desenvolvido sobre dados experimentais reais de um sistema hidráulico contendo 2.205 ciclos operacionais.

O problema central é de engenharia de dados:

Como tornar comparáveis sinais industriais coletados a 100 Hz, 10 Hz e 1 Hz sem perder informação relevante de cada ciclo?

Sensores diferentes produzem volumes incompatíveis dentro dos mesmos 60 segundos:

100 Hz → 6.000 amostras/ciclo
10 Hz  →   600 amostras/ciclo
1 Hz   →    60 amostras/ciclo

O pipeline transforma essas séries em uma representação analítica comum por ciclo.

<p align="center">
  <strong>Sensores → Ingestão → Qualidade → Harmonização → Features → SQL → Analytics → Dashboard</strong>
</p>

O que foi construído

processamento de 12 sensores em 3 frequências de aquisição;

validação de estrutura, completude e domínio dos dados;

processamento de mais de 30 milhões de medições brutas;

feature engineering por ciclo com média, desvio-padrão, mínimo, máximo e percentil 95;

persistência em SQLite;

rastreabilidade das execuções do pipeline;

análises estatísticas das condições operacionais;

ranking de ciclos para investigação condicionado pelo estado operacional;

dashboard em Streamlit;

testes automatizados;

ambiente reproduzível com Docker.

O objetivo não é criar artificialmente um modelo preditivo, mas demonstrar uma cadeia de DataOps industrial, qualidade, transformação e analytics tecnicamente defensável.

<p>
  <a href="https://github.com/luizznelson/industrial-hydraulic-dataops">
    <img src="https://img.shields.io/badge/GitHub-Repositório-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://industrial-hydraulic-dataops.streamlit.app/">
    <img src="https://img.shields.io/badge/Live%20Demo-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Live Demo">
  </a>
</p>

Python Pandas NumPy SQL SQLite Streamlit Plotly Docker Pytest

Áreas de atuação

⚙️ Automação & Inteligência de Processos

Estruturo soluções a partir do entendimento do processo, e não da escolha prévia de uma tecnologia.

Experiência com:

levantamento de requisitos;

modelagem BPMN AS-IS / TO-BE;

identificação de gargalos e retrabalho;

definição de regras de negócio;

automação de atividades manuais;

integração de sistemas;

APIs REST;

critérios de aceite;

testes e homologação;

análise de viabilidade;

mensuração de resultados.

Python REST APIs JSON FastAPI n8n BPMN

📊 Dados & Analytics

Transformo dados operacionais em informação útil para investigação e tomada de decisão.

Experiência com:

extração e tratamento de dados;

Python e Pandas;

SQL;

PostgreSQL e SQLite;

análise exploratória;

estatística;

criação de métricas e KPIs;

Power BI;

Power Query e DAX;

dashboards;

qualidade de dados;

ETL e pipelines;

análise de tendências e comparação entre grupos.

Python Pandas SQL Power BI Power Query DAX Excel

🧠 IA Aplicada

Utilizo IA quando o problema realmente exige interpretação, contexto ou tratamento de informação não estruturada.

Experiência com:

LLMs via API;

LangChain;

prompts estruturados;

RAG;

classificação e sumarização;

extração de informações;

aplicações conversacionais;

integração de LLMs a dados e ferramentas;

avaliação de respostas;

Machine Learning aplicado.

Busco combinar métodos determinísticos e IA, evitando utilizar modelos onde regras ou métodos convencionais produzem uma solução mais simples, previsível e auditável.

LLMs LangChain RAG Prompt Engineering Gemini Groq Scikit-learn

Experiência profissional

VirteX Telecom

Analista de Inovação e Inteligência — Processos & Qualidade
06/2025 – 06/2026

Atuação em iniciativas conectando processos, dados, automação e IA, desde o diagnóstico da necessidade até a implementação e avaliação da solução.

Principais resultados:

desenvolvimento de automação para processo envolvendo aproximadamente 3.000 protocolos por mês;

redução do tempo operacional de aproximadamente 12 minutos para 1 minuto por protocolo;

ROI superior a 1.000% no primeiro ano;

automações e processamento de dados com Python;

integração entre sistemas através de APIs REST;

consultas e tratamento de dados utilizando SQL;

criação de indicadores e dashboards;

Power BI, Power Query, M e DAX;

levantamento de requisitos e regras de negócio;

modelagem BPMN AS-IS / TO-BE;

testes, homologação e acompanhamento pós-implantação;

desenvolvimento de solução corporativa utilizando LLM + LangChain para consulta de informações relacionadas aos processos internos.

Stack técnica

Área

Tecnologias

Automação & Integração

Python · REST APIs · JSON · FastAPI · n8n · OAuth

Dados & Analytics

Pandas · NumPy · SQL · PostgreSQL · SQLite · Power BI · Power Query · DAX

IA Aplicada

LangChain · LLMs · RAG · Prompt Engineering · Gemini · Groq · Scikit-learn

Data Engineering / DataOps

ETL · Docker · Git · CI/CD · Pytest

Processos

BPMN · AS-IS / TO-BE · Requirements Analysis · Business Rules

Estatística

Correlação · Regressão · ANOVA · Delineamento de Experimentos

Formação, docência & pesquisa

Mestrado em Ciência da Computação — Sistemas Distribuídos

Universidade Federal do Piauí — UFPI
2025 – 2028

Bacharelado em Sistemas de Informação

Universidade Federal do Piauí — UFPI
2020 – 2025

Estágio em Docência — Estatística

Universidade Federal do Piauí — UFPI
2026

Atuação no ensino de Estatística aplicada a Sistemas de Informação, incluindo:

Correlação Regressão Linear ANOVA Delineamento de Experimentos

Pesquisador — PASID/UFPI

2022 – atual

Pesquisa aplicada envolvendo:

sistemas distribuídos;

IoT e LoRaWAN;

redes de sensores;

telemetria;

tolerância a falhas;

avaliação de desempenho;

modelagem analítica;

experimentação e análise estatística.

20+ publicações científicas, incluindo trabalhos publicados em periódicos classificados nos estratos Qualis A1, A2, A3 e A4.

Como eu trabalho

Tenho maior interesse em problemas nos quais a solução ainda precisa ser estruturada.

Procuro compreender o contexto, identificar causas e restrições, definir evidências e só então decidir quais mecanismos técnicos fazem sentido.

<p align="center">
  <strong>Entender → Diagnosticar → Arquitetar → Construir → Medir → Melhorar</strong>
</p>

Meu objetivo é desenvolver soluções que não terminem no código, mas produzam melhoria operacional, informação para decisão e impacto mensurável.

<p align="center">
  <strong>Analista de Automação & Inteligência de Processos</strong>
</p>

<p align="center">
  Automação · Dados & Analytics · IA Aplicada
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/luiznelson">LinkedIn</a>
  ·
  <a href="https://luizznelson.github.io">Portfólio</a>
  ·
  <a href="mailto:luizznelsonpro@gmail.com">Email</a>
</p>
