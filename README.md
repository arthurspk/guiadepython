<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="./images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Guia de Python</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadepython?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadepython?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadepython?style=flat-square" alt="Último commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadepython?style=flat-square" alt="Licença">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Guia completo de Python: trilhas, cursos, livros, canais, ferramentas e comunidades
> para você entrar e evoluir na área. Última revisão: setembro/2026.

## 🌍 Idiomas
🇧🇷 Português (você está aqui) · [🇺🇸 English](./translations/README.en.md)

## 📚 Sumário
- [🎯 Sobre este guia](#-sobre-este-guia)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Por onde começar](#-por-onde-começar)
- [🎓 Cursos gratuitos](#-cursos-gratuitos)
- [💰 Cursos pagos](#-cursos-pagos)
- [📖 Documentação e apostilas](#-documentação-e-apostilas)
- [📚 Livros](#-livros)
- [🎥 Canais no YouTube](#-canais-no-youtube)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs e newsletters](#-sites-blogs-e-newsletters)
- [🛠️ Ferramentas](#-ferramentas)
- [🧪 Projetos práticos e desafios](#-projetos-práticos-e-desafios)
- [🤖 IA na prática](#-ia-na-prática)
- [📜 Certificações](#-certificações)
- [💼 Carreira e vagas](#-carreira-e-vagas)
- [👥 Comunidades](#-comunidades)
- [🚨 Como contribuir](#-como-contribuir)
- [📄 Licença](#-licença)
- [💙 Apoie o projeto](#-apoie-o-projeto)

## 🎯 Sobre este guia
Python é uma linguagem de propósito geral, interpretada e de sintaxe limpa, criada por Guido van Rossum em 1991 e mantida pela Python Software Foundation. Hoje é a linguagem mais usada do GitHub e a linguagem padrão de ciência de dados, inteligência artificial, automação e back-end (Django, FastAPI). Ganha uma versão nova todo mês de outubro: a **3.13** (2024) trouxe o novo REPL e a primeira versão sem GIL, e a **3.14** (2025) trouxe t-strings, subinterpretadores e o free-threading oficial.

Este guia é para quem quer aprender Python do zero — mesmo sem nunca ter programado — e para quem já programa e quer se especializar em web, dados ou IA. Os recursos em **português e gratuitos** vêm primeiro em cada seção; 💰 marca conteúdo pago, 🇺🇸 conteúdo em inglês e 🆕 material publicado ou atualizado entre 2024 e 2026. Todo link foi verificado na data da última revisão.

## 🗺️ Roadmap
- [roadmap.sh — Python Developer Roadmap](https://roadmap.sh/python) — Roadmap visual e interativo da comunidade: o que estudar, em que ordem, com links por tópico. 🇺🇸
- [Python para quem está começando (Python Brasil)](https://python.org.br/introducao/) — Página da comunidade brasileira com o caminho sugerido para iniciantes, em português.
- [O Guia do Mochileiro para Python (PT-BR)](https://python-guide-pt-br.readthedocs.io/pt-br/latest/) — Tradução do Hitchhiker's Guide: instalação, ambientes, estrutura de projeto e boas práticas.
- [python-roadmap (Eduardo Mendes)](https://github.com/dunossauro/python-roadmap) — Roadmap em português mantido pelo criador da Live de Python, do básico ao avançado.
- [Python For Beginners (python.org)](https://www.python.org/about/gettingstarted/) — Ponto de partida oficial: instalar, escolher material e dar os primeiros passos. 🇺🇸
- [BeginnersGuide (wiki oficial)](https://wiki.python.org/moin/BeginnersGuide) — Guia oficial para iniciantes, com trilhas separadas para quem nunca programou e para quem já programa. 🇺🇸

**Trilha resumida** (siga na ordem; cada etapa tem recursos nas seções abaixo):

1. **Instalação e primeiro script** — Python 3 mais recente, VS Code ou Thonny, `python ola.py` no terminal.
2. **Fundamentos** — variáveis, tipos, `if`, `for`/`while`, funções, strings e f-strings, entrada e saída.
3. **Estruturas de dados** — listas, tuplas, dicionários, conjuntos, *comprehensions*, fatiamento, `enumerate`/`zip`.
4. **Módulos e ambientes** — importar da biblioteca padrão, `venv`, `pip`/`uv`, `pyproject.toml`, ler e escrever arquivos, JSON e CSV.
5. **Python intermediário** — orientação a objetos, exceções, *type hints*, geradores, decoradores, `dataclasses`, `pathlib`.
6. **Qualidade** — testes com `pytest`, formatação e lint com Ruff, verificação de tipos com mypy/Pyright, Git e GitHub.
7. **Especialização** — web (Django, FastAPI, Flask), dados (pandas, NumPy, Jupyter, Polars), automação (Requests, Playwright, Selenium) ou IA (PyTorch, scikit-learn, SDKs de LLM).
8. **Avançado** — `asyncio` e concorrência, empacotamento e publicação no PyPI, desempenho (perfil, free-threading), contribuição com projetos open source.

## 🚀 Por onde começar
1. **Instale o Python** pelo [site oficial](https://www.python.org/downloads/) (no Windows, marque "Add python.exe to PATH") e um editor: [VS Code com a extensão Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) ou o [Thonny](https://thonny.org/), feito para iniciantes.
2. **Experimente sem instalar nada** no [Google Colab](https://colab.research.google.com/) ou no [Online Python](https://www.programiz.com/python-programming/online-compiler/) — e use o [Python Tutor](https://pythontutor.com/) para ver o código executar passo a passo.
3. **Faça um curso em português:** o [Curso em Vídeo — Mundo 1](https://www.youtube.com/playlist?list=PLHz_AreHm4dlKP6QQCekuIPky1CiwmdI6) (Guanabara) ou o [Curso Completo de Python 2026](https://www.youtube.com/watch?v=WexDtLkN77k) (Hashtag Programação).
4. **Leia o tutorial oficial** — [O tutorial do Python](https://docs.python.org/pt-br/3/tutorial/index.html) está inteiro em português e cobre tudo que um curso cobre.
5. **Pratique todo dia:** os [Exercícios de Python 3 do Curso em Vídeo](https://www.youtube.com/playlist?list=PLHz_AreHm4dm6wYOIW20Nyg12TAjmMGT-), o [Practice Python](https://www.practicepython.org/) e os katas do [Codewars](https://www.codewars.com/?language=python).
6. **Aprofunde:** as lives do [Eduardo Mendes](https://www.youtube.com/playlist?list=PLOQgLBuj2-3Kc7PBT3BwiM-E99LQnjMln) e o livro gratuito [Python Fluente, 2ª edição](https://pythonfluente.com/2/) levam você do intermediário ao avançado.
7. **Escolha uma trilha:** web com o [FastAPI do Zero](https://fastapidozero.dunossauro.com/estavel/) ou [Django](https://www.youtube.com/playlist?list=PLbIBj8vQhvm2mpbtmubbG3-pPGnMxlaEq); dados com o [curso gratuito da Data Science Academy](https://www.datascienceacademy.com.br/course/fundamentos-de-linguagem-python-do-basico-a-aplicacoes-de-ia); IA com o [Hugging Face Learn](https://huggingface.co/learn).
8. **Construa e publique um projeto** no GitHub: um [pacote no PyPI](https://www.youtube.com/playlist?list=PLOQgLBuj2-3LiHhK1upnjpHiFzcJ472QS), uma [CLI](https://www.youtube.com/playlist?list=PLOQgLBuj2-3IvU8rfQdwfiAwf180Vr_o-) ou um dos [81 projetos do Big Book of Small Python Projects](https://inventwithpython.com/bigbookpython/).

Seu primeiro projeto em 30 segundos:

```bash
python3 --version               # precisa ser 3.10 ou superior
mkdir ola-python && cd ola-python
python3 -m venv .venv           # ambiente virtual isolado para o projeto
source .venv/bin/activate       # Windows: .venv\Scripts\activate
```

```python
# ola.py
def saudacao(nome: str) -> str:
    return f"Olá, {nome}!"

if __name__ == "__main__":
    print(saudacao("Guia Dev Brasil"))
```

```bash
python ola.py                   # executa
uv run ola.py                   # alternativa moderna: o uv cria o ambiente sozinho
```

## 🎓 Cursos gratuitos
### Em português
- [Curso de Python 3 — Mundo 1: Fundamentos (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dlKP6QQCekuIPky1CiwmdI6) — O curso de Python mais assistido do Brasil, com Gustavo Guanabara: lógica, variáveis, condições e repetições.
- [Curso de Python 3 — Mundo 2: Estruturas de Controle (Curso em Vídeo)](https://www.cursoemvideo.com/curso/python-3-mundo-2/) — Segunda etapa, com certificado gratuito no site: `if`, `while`, `for` e dezenas de exercícios.
- [Curso de Python 3 — Mundo 3: Estruturas Compostas (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dksnH2jVTIVNviIMBVYyFnH) — Tuplas, listas, dicionários, funções e módulos — fecha a trilha do Curso em Vídeo.
- [Curso Completo de Python 2026 (Iniciantes) + Exercícios (Hashtag Programação)](https://www.youtube.com/watch?v=WexDtLkN77k) — Aula única e recente para sair do zero, com exercícios resolvidos. 🆕
- [Curso de Python — Programação (Hashtag Programação)](https://www.youtube.com/playlist?list=PLpdAy0tYrnKyCZsE-ifaLV1xnkXBE9n7T) — Playlist com dezenas de aulas curtas, do básico a automações e análise de dados.
- [Aprenda Python — Curso COMPLETO para INICIANTES [2025] (Brenno Sullivan)](https://www.youtube.com/watch?v=EV7Idm_mkxo) — Curso em vídeo único publicado em 2025, direto ao ponto. 🆕
- [Python para iniciantes — aprenda do ZERO! (Asimov Academy)](https://www.youtube.com/playlist?list=PLuvoZvhxWzZCYMiKtkcMr-aYJ3KV47V0G) — Série gratuita da escola brasileira de Python e IA, pensada para quem nunca programou.
- [Curso Gratuito de Python para Dados (Asimov Academy)](https://www.asimov.academy/misc/complementares/cursos-gratuitos/dados/) — Curso gratuito na plataforma da Asimov, focado em Python para análise de dados.
- [Fundamentos de Linguagem Python — Do Básico a Aplicações de IA (Data Science Academy)](https://www.datascienceacademy.com.br/course/fundamentos-de-linguagem-python-do-basico-a-aplicacoes-de-ia) — Curso gratuito com certificado lançado em setembro de 2025, do zero até aplicações de IA. 🆕
- [Curso Python para Iniciantes Completo (Didática Tech)](https://www.youtube.com/playlist?list=PLyqOvdQmGdTSEPnO0DKgHlkXb8x3cyglD) — Curso completo e didático, muito usado por quem migra para dados.
- [Curso Python para Machine Learning e Análise de Dados (Didática Tech)](https://www.youtube.com/playlist?list=PLyqOvdQmGdTR46HUxDA6Ymv4DGsIjvTQ-) — Continuação natural: NumPy, pandas e primeiros modelos de machine learning.
- [Introdução à Ciência da Computação com Python (IME/USP — YouTube)](https://www.youtube.com/playlist?list=PLcoJJSvnDgcKpOi_UeneTNTIVOigRQwcn) — Aulas do professor Fabio Kon (USP): fundamentos de computação usando Python.
- [Introdução à Ciência da Computação com Python — Parte 1 (USP no Coursera)](https://www.coursera.org/learn/ciencia-computacao-python-conceitos) — Versão no Coursera do curso da USP, com exercícios corrigidos automaticamente (audite de graça).
- [Introdução à Ciência da Computação com Python — Parte 2 (USP no Coursera)](https://www.coursera.org/learn/ciencia-computacao-python-conceitos-2) — Segunda parte: dicionários, arquivos, orientação a objetos e recursão.
- [Playlist Python — Eduardo Mendes (Live de Python)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3Kc7PBT3BwiM-E99LQnjMln) — Centenas de lives semanais do Dunossauro sobre a linguagem, do básico a tópicos avançados — a maior referência gratuita em PT-BR. 🆕
- [Quer aprender Python? (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3LwyKrvIde88moVcFWAN2Xz) — Sequência introdutória para quem quer começar pelas lives do Dunossauro.
- [Orientação a objetos em Python (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3L_L6ahsBVA_SzuGtKre3OK) — Classes, herança, dunder methods e protocolos explicados com calma.
- [Curso de FastAPI 2025 (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3KT9ZWvPmaGFQ0KjIez0403) — Aulas síncronas de 2025 do curso FastAPI do Zero: API completa com testes, banco e autenticação JWT. 🆕
- [FastAPI do Zero (livro-curso gratuito)](https://fastapidozero.dunossauro.com/estavel/) — Material em texto do curso, atualizado a cada edição, com código no GitHub. 🆕
- [Curso de Type Hints no Python do Básico ao Avançado (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm04EuddtleOAoEmfU9vwQlN) — Anotações de tipo, `typing`, generics e verificação estática com mypy/Pyright.
- [Expressões Regulares em Python (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm1VnTa2Np5vDzCxVtyaYLMr) — O módulo `re` do zero, com exemplos práticos.
- [Programação concorrente em Python (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm0YZFsgLK4Fhc0a1kRxj_xx) — Threads, processos, `asyncio` e o GIL explicados na prática.
- [Django (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm2mpbtmubbG3-pPGnMxlaEq) — Playlist gratuita de Django, o framework web mais usado em Python no Brasil.
- [Curso de introdução ao desenvolvimento Web com Python 3 e Django (Rafael Zottesso)](https://www.youtube.com/playlist?list=PLjv17QYEBJPpd6nI-MXpIa4qR7prKfPQz) — Do zero a um site funcional com Django, passo a passo.
- [Aulas Python (Ignorância Zero)](https://www.youtube.com/playlist?list=PLfCKf0-awunOu2WyLe2pSD2fXUo795xRe) — Um dos cursos mais completos do YouTube brasileiro, com mais de 100 aulas.
- [Curso de Python (CFBCursos)](https://www.youtube.com/playlist?list=PLx4x_zx8csUhuVgWfy7keQQAy7t1J35TR) — Playlist com aulas curtas, um conceito por vídeo.
- [Curso de Programação com Python — Completo (Bóson Treinamentos)](https://www.youtube.com/playlist?list=PLucm8g_ezqNrrtduPx7s4BM8phepMn9I2) — Curso longo e bem organizado, com boa cobertura da biblioteca padrão.
- [Curso de Python (eXcript)](https://www.youtube.com/playlist?list=PLesCEcYj003QxPQ4vTXkt22-E11aQvoVj) — Curso clássico em português, muito didático para quem nunca programou.
- [Curso Python Básico (Solyd Offensive Security)](https://www.youtube.com/playlist?list=PLp95aw034Wn_WtEmlepaDrw8FU8R5azcm) — Python básico com viés de segurança da informação e automação.
- [Curso Completo de Python (Jefferson Lobato)](https://www.youtube.com/playlist?list=PLLVddSbilcul-1bAKtMKoL6wOCmDIPzFJ) — Curso completo em português com projetos ao longo das aulas.
- [O Melhor Curso de Python (Zurubabel)](https://www.youtube.com/playlist?list=PL4OAe-tL47sY8SGhtkGoP0eQd4le3badz) — Curso em português com foco em entender o porquê das coisas.
- [Curso de Python Orientado a Objetos (Portal Hugo Cursos)](https://www.youtube.com/playlist?list=PLxNM4ef1Bpxhm8AfK1nDMWPDYXtmVQN-z) — POO em Python: classes, herança, polimorfismo e encapsulamento.
- [Curso Python p/ Iniciantes (Refatorando)](https://www.youtube.com/playlist?list=PLj7gJIFoP7jdirAFg-fHe9HKOnGLGXSHZ) — Curso curto e objetivo para os primeiros passos.
- [Curso: Python Essencial para Data Science (xavecoding)](https://www.youtube.com/playlist?list=PL3ZslI15yo2qCEmnYOa2sq6VQOzQ2CFhj) — O essencial da linguagem para quem quer ir direto para ciência de dados.
- [Curso de Selenium com Python (Eduardo Mendes)](https://dunossauro.github.io/curso-python-selenium/) — Automação de navegador e testes web com Selenium, gratuito e em texto + vídeo.
- [Scientific Computing with Python — freeCodeCamp (PT-BR)](https://www.freecodecamp.org/portuguese/learn/scientific-computing-with-python) — Currículo interativo do freeCodeCamp traduzido, com projetos e certificado gratuito.
- [Learn Python — tutorial interativo (PT)](https://www.learnpython.org/pt/) — Tutorial interativo no navegador, em português: leia, rode o código e avance.
- [Introdução ao Python (Sololearn, PT)](https://www.sololearn.com/pt/learn/courses/python-introduction) — Curso em português no celular ou navegador, com exercícios curtos e comunidade.

### Em inglês
- [CS50's Introduction to Programming with Python (Harvard)](https://cs50.harvard.edu/python/) — O curso de Python de Harvard, gratuito, com problem sets corrigidos automaticamente. 🇺🇸
- [Python for Everybody (PY4E)](https://www.py4e.com/) — Curso completo do Dr. Chuck (Universidade de Michigan) com livro, vídeos e exercícios gratuitos. 🇺🇸
- [Python for Everybody — Specialization (Coursera)](https://www.coursera.org/specializations/python) — A mesma trilha no Coursera; audite gratuitamente ou pague pelo certificado. 🇺🇸
- [Google's Python Class](https://developers.google.com/edu/python) — Curso clássico do Google, com vídeos e exercícios, para quem já programa um pouco. 🇺🇸
- [Crash Course on Python (Google no Coursera)](https://www.coursera.org/learn/python-crash-course) — Primeiro curso do certificado Google IT Automation; audite de graça. 🇺🇸
- [MIT 6.100L — Introduction to CS and Programming Using Python (OCW)](https://ocw.mit.edu/courses/6-100l-introduction-to-cs-and-programming-using-python-fall-2022/) — Curso introdutório do MIT com aulas gravadas, slides e problem sets. 🇺🇸
- [Scientific Computing with Python (freeCodeCamp)](https://www.freecodecamp.org/learn/scientific-computing-with-python) — Versão original em inglês do currículo interativo do freeCodeCamp. 🇺🇸
- [Kaggle Learn — Python](https://www.kaggle.com/learn/python) — Curso rápido e prático em notebooks, ideal para quem vai para dados. 🇺🇸
- [Learn Python — Full Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=rfscVS0vtbw) — Vídeo único de 4 horas, um dos mais assistidos do YouTube sobre Python. 🇺🇸
- [Python Full Course for Beginners (Programming with Mosh)](https://www.youtube.com/watch?v=_uQrJ0TkZlc) — Curso de 6 horas com projetos de automação, dados e web. 🇺🇸
- [Python for Beginners (Microsoft Developer)](https://www.youtube.com/playlist?list=PLlrxD0HtieHhS8VzuMCfQD4uJ9yne1mE6) — Série oficial da Microsoft com vídeos curtos e código no GitHub. 🇺🇸
- [Python Tutorials (Corey Schafer)](https://www.youtube.com/playlist?list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU) — A playlist de referência para conceitos intermediários: geradores, decorators, POO, módulos. 🇺🇸
- [Intermediate Python Programming Course (freeCodeCamp)](https://www.youtube.com/watch?v=HGOBQPFzWKo) — Para quem já passou do básico: coleções, itertools, threading, logging, decorators. 🇺🇸
- [Advanced Python — Complete Course (Patrick Loeber)](https://www.youtube.com/playlist?list=PLqnslRFeH2UqLwzS0AwKDKLrpYBKzLBy2) — Tópicos avançados em vídeos curtos e bem explicados. 🇺🇸
- [Automate with Python — Full Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=PXMJ6FS7llk) — Automação de tarefas do dia a dia: planilhas, PDFs, e-mails, web. 🇺🇸
- [Data Structures and Algorithms in Python (freeCodeCamp)](https://www.youtube.com/watch?v=pkYVOmU3MgA) — Estruturas de dados e algoritmos implementados em Python, com exercícios. 🇺🇸
- [futurecoder](https://futurecoder.io/) — Curso interativo gratuito e open source, com depurador e dicas dentro do navegador. 🇺🇸
- [Learn Python (Codédex)](https://www.codedex.io/python) — Curso gamificado para iniciantes, com capítulos gratuitos. 🇺🇸
- [Intro to Python (Udacity)](https://www.udacity.com/course/introduction-to-python--ud1110) — Curso gratuito da Udacity para começar com a linguagem. 🇺🇸
- [Python for Data Science (IBM Cognitive Class)](https://cognitiveclass.ai/courses/python-for-data-science) — Curso gratuito da IBM com badge, voltado a dados. 🇺🇸
- [30 Days of Python](https://github.com/Asabeneh/30-Days-Of-Python) — Desafio de 30 dias no GitHub, com um tópico e exercícios por dia. 🇺🇸

## 💰 Cursos pagos
- [Formação Python (Alura)](https://www.alura.com.br/formacao-linguagem-python) — Trilha completa da Alura, da sintaxe à orientação a objetos, com certificado. 💰
- [Formação Data Science com Python (Alura)](https://www.alura.com.br/formacao-data-science-python) — Trilha da Alura para análise de dados com pandas, visualização e estatística. 💰
- [Curso de Python do Zero ao Avançado (Hashtag Treinamentos)](https://www.hashtagtreinamentos.com/curso-python) — Mais de 100 horas com foco em automação, dados e aplicações para o trabalho. 💰
- [Asimov Academy](https://www.asimov.academy/) — Escola brasileira de Python e IA, com trilhas de dados, web, automação e agentes. 💰
- [Python Academy (Vinicius Ramos)](https://pythonacademy.com.br/) — Cursos em português com foco em Python profissional e boas práticas. 💰
- [Cursos do Otávio Miranda](https://otaviomiranda.com.br/) — Site do professor Luiz Otávio Miranda, autor do curso de Python 3 do básico ao avançado (140+ horas). 💰
- [Talk Python Training](https://training.talkpython.fm/) — Cursos do criador do podcast Talk Python, muito práticos e atualizados. 💰 🇺🇸
- [Python Morsels](https://www.pythonmorsels.com/) — Exercícios semanais com correção detalhada, para escrever Python mais idiomático. 💰 🇺🇸
- [Hyperskill — Python (JetBrains)](https://hyperskill.org/courses/python) — Trilha baseada em projetos, integrada ao PyCharm. 💰 🇺🇸
- [Learn Python 3 (Codecademy)](https://www.codecademy.com/learn/learn-python-3) — Curso interativo no navegador; parte do conteúdo é gratuito, o restante no plano Pro. 💰 🇺🇸

## 📖 Documentação e apostilas
- [Documentação oficial do Python em português](https://docs.python.org/pt-br/3/) — A documentação oficial, traduzida pela comunidade brasileira e sempre na versão mais recente.
- [O tutorial do Python (oficial, PT-BR)](https://docs.python.org/pt-br/3/tutorial/index.html) — Tutorial oficial: o melhor lugar para aprender a sintaxe e os conceitos centrais.
- [A Biblioteca Padrão do Python (PT-BR)](https://docs.python.org/pt-br/3/library/index.html) — Referência de todos os módulos que já vêm com o Python ('baterias inclusas').
- [A Referência da Linguagem Python (PT-BR)](https://docs.python.org/pt-br/3/reference/index.html) — Especificação da sintaxe e semântica da linguagem.
- [Python HOWTOs (PT-BR)](https://docs.python.org/pt-br/3/howto/index.html) — Guias oficiais por tema: regex, logging, sorting, descritores, anotações, Unicode.
- [Perguntas Frequentes sobre Python (PT-BR)](https://docs.python.org/pt-br/3/faq/index.html) — FAQ oficial: dúvidas de design, programação e uso da linguagem.
- [Glossário oficial (PT-BR)](https://docs.python.org/pt-br/3/glossary.html) — Definições de termos como iterável, decorador, GIL, duck typing.
- [Configurações e Uso do Python (PT-BR)](https://docs.python.org/pt-br/3/using/index.html) — Como instalar e configurar o Python no Windows, macOS e Linux.
- [O que há de novo no Python 3.13 (PT-BR)](https://docs.python.org/pt-br/3/whatsnew/3.13.html) — Novidades de outubro de 2024: novo REPL interativo, build free-threaded experimental e JIT. 🆕
- [O que há de novo no Python 3.14 (PT-BR)](https://docs.python.org/pt-br/3/whatsnew/3.14.html) — Novidades de outubro de 2025: t-strings, avaliação adiada de anotações, subinterpretadores e free-threading oficial. 🆕
- [Suporte do Python para threads livres (HOWTO, PT-BR)](https://docs.python.org/pt-br/3/howto/free-threading-python.html) — Guia oficial sobre o Python sem GIL: como instalar e o que muda. 🆕
- [venv — Criação de ambientes virtuais (PT-BR)](https://docs.python.org/pt-br/3/library/venv.html) — Documentação do módulo que isola as dependências de cada projeto.
- [typing — Suporte para dicas de tipo (PT-BR)](https://docs.python.org/pt-br/3/library/typing.html) — Referência das anotações de tipo, base de mypy, Pyright e ty.
- [asyncio — E/S assíncrona (PT-BR)](https://docs.python.org/pt-br/3/library/asyncio.html) — Documentação oficial de programação assíncrona com `async`/`await`.
- [PEP 8 — Style Guide for Python Code](https://peps.python.org/pep-0008/) — O guia de estilo oficial: como formatar e nomear código Python. 🇺🇸
- [PEP 20 — The Zen of Python](https://peps.python.org/pep-0020/) — Os 19 princípios da linguagem (ou rode `import this`). 🇺🇸
- [Índice de PEPs](https://peps.python.org/) — Todas as propostas de melhoria do Python: é aqui que a linguagem evolui. 🇺🇸
- [PEP 703 — Making the GIL Optional in CPython](https://peps.python.org/pep-0703/) — A proposta que tornou o Python free-threaded possível. 🆕 🇺🇸
- [PEP 750 — Template Strings](https://peps.python.org/pep-0750/) — As t-strings do Python 3.14: strings-modelo processadas antes de virar texto. 🆕 🇺🇸
- [Python Packaging User Guide (PT-BR)](https://packaging.python.org/pt-br/latest/) — Guia oficial de empacotamento: `pyproject.toml`, build e publicação no PyPI.
- [Static Typing with Python (typing.python.org)](https://typing.python.org/en/latest/) — Documentação oficial da tipagem estática, com guias e especificação. 🇺🇸
- [Python Developer's Guide](https://devguide.python.org/) — Como o CPython é desenvolvido e como contribuir com a linguagem. 🇺🇸
- [The Hitchhiker's Guide to Python](https://docs.python-guide.org/) — Original em inglês do Guia do Mochileiro, com seções mais atualizadas. 🇺🇸
- [Python 3 Module of the Week (PyMOTW-3)](https://pymotw.com/3/) — Um tour pela biblioteca padrão, módulo a módulo, com exemplos. 🇺🇸
- [Learn X in Y minutes — Python (PT-BR)](https://learnxinyminutes.com/pt-br/python/) — A sintaxe inteira da linguagem num único arquivo comentado, em português.
- [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) — Guia de estilo usado no Google, complemento prático à PEP 8. 🇺🇸
- [Python em Windows para iniciantes (Microsoft Learn, PT-BR)](https://learn.microsoft.com/pt-br/windows/dev-environment/python) — Como configurar Python, VS Code e WSL no Windows.
- [free-programming-books — Python (PT-BR)](https://github.com/EbookFoundation/free-programming-books/blob/main/books/free-programming-books-pt_BR.md#python) — Lista mantida pela comunidade de livros e apostilas gratuitas de Python em português.

## 📚 Livros
- [Python Fluente, 2ª edição (Luciano Ramalho) — gratuito online](https://pythonfluente.com/2/) — A tradução oficial, liberada pelo autor, do livro mais respeitado sobre Python idiomático.
- [Pense em Python, 2ª edição (Allen Downey) — gratuito](https://penseallen.github.io/PensePython2e/) — Tradução em português de Think Python: introdução à programação usando Python.
- [Introdução à Programação com Python, 4ª edição (Nilo Ney Coutinho Menezes) — site do livro](https://python.nilo.pro.br/) — Site do autor com material de apoio do clássico brasileiro para iniciantes, atualizado para o Python 3.12. 🆕
- [Introdução à Programação com Python, 4ª edição (Novatec)](https://novatec.com.br/livros/introducao-python-4ed/) — Edição de 2024 do livro do Nilo Ney, o mais indicado em português para quem nunca programou. 🆕 💰
- [Automatize tarefas maçantes com Python, 3ª edição (Novatec)](https://novatec.com.br/livros/automatize-tarefas-macantes-com-python-3ed/) — Tradução de 2025 do best-seller de Al Sweigart: Python para automatizar o trabalho. 🆕 💰
- [Curso Intensivo de Python, 3ª edição (Novatec)](https://novatec.com.br/livros/curso-intensivo-python-3ed/) — Tradução de Python Crash Course: fundamentos e três projetos (jogo, dados e web). 💰
- [Black Hat Python, 2ª edição (Novatec)](https://novatec.com.br/livros/black-hat-python-2ed/) — Python aplicado a segurança ofensiva, edição de 2024 atualizada para Python 3. 🆕 💰
- [Python 3 (Casa do Código)](https://www.casadocodigo.com.br/products/livro-python-3) — Livro introdutório da Casa do Código, em português. 💰
- [Automate the Boring Stuff with Python, 3rd Edition — gratuito online](https://automatetheboringstuff.com/) — Edição de 2025 do livro do Al Sweigart, lida gratuitamente no site. 🆕 🇺🇸
- [Think Python, 3rd Edition — gratuito online](https://allendowney.github.io/ThinkPython/) — Edição de 2024 com notebooks Jupyter, para aprender programando. 🆕 🇺🇸
- [Beyond the Basic Stuff with Python — gratuito online](https://inventwithpython.com/beyond/) — O passo seguinte ao básico: boas práticas, ferramentas, POO e código limpo. 🇺🇸
- [A Byte of Python — gratuito](https://python.swaroopch.com/) — Livro curto e gratuito para iniciantes, traduzido para vários idiomas. 🇺🇸
- [Dive Into Python 3 — gratuito](https://diveintopython3.net/) — Clássico para quem já programa em outra linguagem e quer aprender Python 3 rápido. 🇺🇸
- [Python for Data Analysis, 3rd Edition (Wes McKinney) — gratuito online](https://wesmckinney.com/book/) — O livro do criador do pandas, aberto na íntegra no site do autor. 🇺🇸
- [Architecture Patterns with Python (cosmic python) — gratuito online](https://www.cosmicpython.com/) — Arquitetura, DDD, TDD e event-driven em Python, com o livro completo no site. 🇺🇸
- [Effective Python, 3rd Edition (Brett Slatkin)](https://effectivepython.com/) — Edição de 2024 com 125 formas específicas de escrever Python melhor. 🆕 💰 🇺🇸
- [Python Crash Course, 3rd Edition (No Starch Press)](https://nostarch.com/python-crash-course-3rd-edition) — O livro introdutório de Python mais vendido do mundo. 💰 🇺🇸
- [The Quick Python Book, 3rd Edition (Naomi Ceder)](https://www.manning.com/books/the-quick-python-book-third-edition) — Introdução concisa para quem já programa, por uma ex-presidente da PSF. 💰 🇺🇸
- [Learn Python the Hard Way (Zed Shaw)](https://learnpythonthehardway.org/) — Método baseado em digitar e rodar exercícios até fixar. 💰 🇺🇸
- [PythonBooks (wiki oficial)](https://wiki.python.org/moin/PythonBooks) — Lista oficial de livros de Python por nível e idioma. 🇺🇸

## 🎥 Canais no YouTube
### Em português
- [Curso em Vídeo](https://www.youtube.com/@CursoemVideo) — Canal do Gustavo Guanabara, casa do curso de Python mais popular do Brasil.
- [Eduardo Mendes (Dunossauro)](https://www.youtube.com/@Dunossauro) — Live de Python toda semana desde 2017, FastAPI do Zero e minisséries sobre a linguagem.
- [Otávio Miranda](https://www.youtube.com/@OtavioMiranda) — Cursos gratuitos completos: type hints, regex, concorrência, Django, LangChain.
- [Hashtag Programação](https://www.youtube.com/@HashtagProgramacao) — Python para automação, dados e aplicações do dia a dia, em linguagem simples.
- [Programação Dinâmica](https://www.youtube.com/@pgdinamica) — Kizzy Terra e Hallison Paz: Python, ciência de dados e IA com rigor e didática.
- [Código Fonte TV](https://www.youtube.com/@codigofontetv) — Gabriel e Vanessa explicam tecnologias (Python incluso) de forma leve e visual.
- [Didática Tech](https://www.youtube.com/@DidaticaTech) — Python, machine learning e dados com aulas completas e gratuitas.
- [Asimov Academy](https://www.youtube.com/@AsimovAcademy) — Canal da escola de Python e IA, com tutoriais gratuitos de agentes, dados e automação.
- [Let's Data](https://www.youtube.com/@LetsDataAI) — Ciência de dados e IA em português, com Python como ferramenta central.
- [Jornada de Dados (Luciano Vasconcelos)](https://www.youtube.com/@JornadadeDados) — Engenharia de dados com Python: pipelines, APIs, testes e boas práticas.
- [Dev Aprender (Jhonatan de Souza)](https://www.youtube.com/@DevAprender) — Python e desenvolvimento web explicados de forma prática para iniciantes.
- [Programador Lhama](https://www.youtube.com/@ProgramadorLhama) — Python, Django e carreira, com projetos completos.
- [CFBCursos](https://www.youtube.com/@cfbcursos) — Cursos gratuitos e organizados por playlist, incluindo Python.
- [Bóson Treinamentos](https://www.youtube.com/@bosontreinamentos) — Canal veterano com cursos completos de Python, bancos de dados e redes.
- [Python Brasil (oficial)](https://www.youtube.com/@pythonbrasiloficial) — Palestras e tutoriais gravados nas conferências Python Brasil.
- [Filipe Deschamps](https://www.youtube.com/@filipedeschamps) — Programação e carreira em geral, com vídeos didáticos que usam Python com frequência.

### Em inglês
- [Corey Schafer](https://www.youtube.com/@coreyms) — O canal de Python mais recomendado do mundo: tutoriais claros e atemporais. 🇺🇸
- [mCoding](https://www.youtube.com/@mCoding) — Python intermediário e avançado em vídeos curtos e precisos. 🇺🇸
- [ArjanCodes](https://www.youtube.com/@ArjanCodes) — Design de software, arquitetura e código limpo em Python. 🇺🇸
- [Tech With Tim](https://www.youtube.com/@TechWithTim) — Projetos completos e tutoriais para iniciantes e intermediários. 🇺🇸
- [freeCodeCamp.org](https://www.youtube.com/@freecodecamp) — Cursos completos de várias horas sobre Python e seu ecossistema. 🇺🇸
- [Real Python](https://www.youtube.com/@realpython) — Vídeos do site Real Python, com tutoriais e entrevistas. 🇺🇸
- [Indently](https://www.youtube.com/@Indently) — Dicas rápidas e truques de Python moderno. 🇺🇸
- [anthonywritescode](https://www.youtube.com/@anthonywritescode) — Anthony Sottile (pre-commit, pyupgrade) sobre ferramentas e internals do Python. 🇺🇸
- [sentdex](https://www.youtube.com/@sentdex) — Python aplicado a dados, machine learning e projetos criativos. 🇺🇸
- [Programming with Mosh](https://www.youtube.com/@programmingwithmosh) — Cursos de Python bem produzidos para iniciantes. 🇺🇸
- [PyCon US](https://www.youtube.com/@PyConUS) — Todas as palestras da maior conferência de Python do mundo. 🇺🇸
- [Python Software Foundation](https://www.youtube.com/@ThePSF) — Canal oficial da fundação que mantém o Python. 🇺🇸

## 🎙️ Podcasts
- [Hipsters Ponto Tech #122 — Python](https://www.hipsters.tech/python-hipsters-122/) — O episódio mais pedido do podcast: por que Python virou mania, dados, web e comunidade.
- [Hipsters Ponto Tech #179 — Python Fluente](https://www.hipsters.tech/python-fluente-hipsters-ponto-tech-179/) — Conversa com Luciano Ramalho sobre Python idiomático e o livro Python Fluente.
- [Hipsters Ponto Tech #387 — Ecossistema Python](https://www.hipsters.tech/ecossistema-python-hipsters-ponto-tech-387/) — Comunidade, tendências, frameworks e portas de entrada, com PyLadies e AfroPython.
- [Hipsters Ponto Tech #433 — Startups: Python e LLMs na talkd.ai](https://www.hipsters.tech/startups-pyton-e-llms-na-talkd-ai-hipsters-ponto-tech-433/) — Python em produção com LLMs numa startup brasileira. 🆕
- [Hipsters Ponto Tech — tag Python](https://www.hipsters.tech/tag/python/) — Todos os episódios do Hipsters que falam de Python.
- [Talk Python To Me](https://talkpython.fm/) — O podcast de Python mais ouvido do mundo, com entrevistas semanais. 🇺🇸
- [Python Bytes](https://pythonbytes.fm/) — Notícias do ecossistema Python em episódios curtos e semanais. 🇺🇸
- [Podcast.__init__](https://www.pythonpodcast.com/) — Arquivo de centenas de entrevistas com criadores de bibliotecas Python. 🇺🇸

## 📰 Sites, blogs e newsletters
- [Python Brasil](https://python.org.br/) — Site da comunidade brasileira: materiais, eventos, listas e comunidades locais.
- [Python Academy — blog](https://pythonacademy.com.br/blog/) — Artigos longos e práticos em português sobre a linguagem.
- [Alura — artigos sobre Python](https://www.alura.com.br/artigos/python) — Guia de introdução e artigos em português sobre Python.
- [Data Science Academy — blog (Linguagem Python)](https://blog.dsacademy.com.br/categoria/linguagem-python/) — Artigos em português sobre Python para dados e IA.
- [Programação Dinâmica — blog](https://blog.programacaodinamica.com.br/) — Textos em português sobre Python, dados e IA do canal Programação Dinâmica.
- [TabNews](https://www.tabnews.com.br/) — Comunidade brasileira de conteúdo técnico, com muitos posts sobre Python.
- [Real Python](https://realpython.com/) — Os tutoriais mais completos da web sobre Python; muitos gratuitos, com membership opcional. 🇺🇸
- [Python Insider (blog oficial)](https://pythoninsider.blogspot.com/) — Anúncios oficiais de lançamento de cada versão do Python. 🇺🇸
- [PSF News](https://pyfound.blogspot.com/) — Blog da Python Software Foundation: pesquisas, bolsas, eventos. 🇺🇸
- [PyCoder's Weekly](https://pycoders.com/) — Newsletter semanal com os melhores artigos, projetos e discussões. 🇺🇸
- [Python Weekly](https://www.pythonweekly.com/) — Newsletter semanal com notícias, artigos e vagas. 🇺🇸
- [Planet Python](https://planetpython.org/) — Agregador dos blogs da comunidade Python. 🇺🇸
- [awesome-python](https://github.com/vinta/awesome-python) — Lista definitiva de bibliotecas e recursos por área. 🇺🇸
- [Full Stack Python](https://www.fullstackpython.com/) — Guia sobre construir, implantar e operar aplicações Python. 🇺🇸
- [Mouse Vs Python](https://blog.pythonlibrary.org/) — Blog de Mike Driscoll com tutoriais e resenhas de livros. 🇺🇸
- [Python⇒Speed](https://pythonspeed.com/) — Artigos de Itamar Turner-Trauring sobre performance, memória e Docker com Python. 🇺🇸
- [Trey Hunner](https://treyhunner.com/) — Artigos sobre Python idiomático para quem quer sair do básico. 🇺🇸
- [Ned Batchelder](https://nedbatchelder.com/blog) — Blog do mantenedor do coverage.py, com textos clássicos sobre a linguagem. 🇺🇸
- [PyCharm Blog (JetBrains)](https://blog.jetbrains.com/pycharm/) — Notícias do ecossistema, pesquisas e tutoriais. 🇺🇸
- [dev.to — tag Python](https://dev.to/t/python) — Artigos da comunidade DEV sobre Python. 🇺🇸
- [Python Tutorial (pythontutorial.net)](https://www.pythontutorial.net/) — Tutoriais em texto, do básico a Tkinter, SQLite e concorrência. 🇺🇸
- [Programiz — Python](https://www.programiz.com/python-programming) — Tutorial em texto com exemplos e compilador online. 🇺🇸
- [W3Schools — Python](https://www.w3schools.com/python/) — Referência rápida com exemplos executáveis. 🇺🇸
- [GeeksforGeeks — Python](https://www.geeksforgeeks.org/python/python-programming-language-tutorial/) — Tutoriais e exercícios, bons para preparação de entrevistas. 🇺🇸

## 🛠️ Ferramentas
### Instalar, executar e gerenciar ambientes
- [Python.org — Downloads](https://www.python.org/downloads/) — Instalador oficial para Windows e macOS (no Linux, use o gerenciador de pacotes). 🇺🇸
- [pip](https://pip.pypa.io/en/stable/) — O instalador de pacotes padrão do Python. 🇺🇸
- [PyPI](https://pypi.org/) — O repositório oficial de pacotes Python. 🇺🇸
- [uv](https://docs.astral.sh/uv/) — Gerenciador de pacotes e projetos em Rust, extremamente rápido: substitui pip, venv, pyenv e Poetry. 🆕 🇺🇸
- [Poetry](https://python-poetry.org/) — Gerenciamento de dependências e empacotamento com `pyproject.toml`. 🇺🇸
- [pyenv](https://github.com/pyenv/pyenv) — Instale e alterne entre várias versões do Python. 🇺🇸
- [pipx](https://pipx.pypa.io/stable/) — Instale ferramentas de linha de comando Python em ambientes isolados. 🇺🇸
- [Google Colab](https://colab.research.google.com/) — Notebooks Jupyter gratuitos na nuvem, com GPU — nada para instalar. 🇺🇸
- [Project Jupyter](https://jupyter.org/) — Notebooks interativos, o ambiente padrão para dados e ensino. 🇺🇸
- [marimo](https://marimo.io/) — Notebook reativo e reprodutível, salvo como `.py` puro. 🆕 🇺🇸
- [Python Tutor](https://pythontutor.com/) — Visualize a execução do código passo a passo — ótimo para entender referências e recursão. 🇺🇸
- [Online Python (Programiz)](https://www.programiz.com/python-programming/online-compiler/) — Rode Python no navegador sem instalar nada. 🇺🇸
- [PyInstaller](https://pyinstaller.org/en/stable/) — Empacote seu programa como executável para Windows, macOS e Linux. 🇺🇸
- [PythonAnywhere](https://www.pythonanywhere.com/) — Hospede scripts e apps web Python na nuvem, com plano gratuito. 🇺🇸
- [PyPy](https://pypy.org/) — Implementação alternativa com JIT, muito mais rápida em código puro Python. 🇺🇸
- [MicroPython](https://micropython.org/) — Python para microcontroladores (ESP32, Raspberry Pi Pico). 🇺🇸

### Editores, qualidade de código e testes
- [Visual Studio Code — extensão Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) — Extensão oficial da Microsoft: IntelliSense, depuração, notebooks e testes. 🇺🇸
- [Getting Started with Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial) — Tutorial oficial para configurar o VS Code para Python. 🇺🇸
- [PyCharm](https://www.jetbrains.com/pycharm/) — A IDE mais completa para Python; a edição Community é gratuita. 🇺🇸
- [Thonny](https://thonny.org/) — IDE minimalista feita para iniciantes, com depurador visual. 🇺🇸
- [Mu](https://codewith.mu/) — Editor simples para quem está começando, com modos para MicroPython e pygame. 🇺🇸
- [Spyder](https://www.spyder-ide.org/) — IDE científica, familiar para quem vem do MATLAB/R. 🇺🇸
- [Ruff](https://docs.astral.sh/ruff/) — Linter e formatador em Rust, centenas de vezes mais rápido que Flake8 + Black. 🇺🇸
- [Black](https://black.readthedocs.io/en/stable/) — O formatador 'sem discussão' que padronizou o estilo de código Python. 🇺🇸
- [mypy](https://mypy.readthedocs.io/en/stable/) — O verificador de tipos estático de referência. 🇺🇸
- [Pyright](https://github.com/microsoft/pyright) — Verificador de tipos da Microsoft, base do Pylance no VS Code. 🇺🇸
- [ty](https://docs.astral.sh/ty/) — Verificador de tipos e language server em Rust da Astral (criadores do uv e Ruff), em preview. 🆕 🇺🇸
- [Pyrefly](https://pyrefly.org/) — Verificador de tipos em Rust da Meta, rápido e com IDE integrada. 🆕 🇺🇸
- [pytest](https://docs.pytest.org/en/stable/) — O framework de testes padrão de fato do ecossistema. 🇺🇸
- [unittest (PT-BR)](https://docs.python.org/pt-br/3/library/unittest.html) — Framework de testes da biblioteca padrão.
- [Coverage.py](https://coverage.readthedocs.io/en/latest/) — Mede quanto do seu código é coberto pelos testes. 🇺🇸
- [pre-commit](https://pre-commit.com/) — Rode Ruff, mypy e outros verificadores automaticamente antes de cada commit. 🇺🇸
- [pdb — O depurador do Python (PT-BR)](https://docs.python.org/pt-br/3/library/pdb.html) — Depurador da biblioteca padrão: `breakpoint()` e pronto.
- [logging (PT-BR)](https://docs.python.org/pt-br/3/library/logging.html) — Registro de eventos da biblioteca padrão — pare de usar `print` para depurar em produção.
- [regex101](https://regex101.com/) — Teste expressões regulares com explicação passo a passo (selecione o sabor Python). 🇺🇸

### Bibliotecas e frameworks essenciais
- [Django](https://www.djangoproject.com/) — Framework web completo: ORM, admin, autenticação e segurança inclusos. 🇺🇸
- [Documentação do Django 5.2 (PT-BR)](https://docs.djangoproject.com/pt-br/5.2/) — Documentação oficial da versão LTS de 2025, traduzida. 🆕
- [FastAPI (docs em PT)](https://fastapi.tiangolo.com/pt/) — Framework moderno para APIs, baseado em type hints, com documentação parcialmente em português.
- [Flask](https://flask.palletsprojects.com/en/stable/) — Microframework web minimalista, ótimo para aprender como a web funciona. 🇺🇸
- [Django Ninja](https://django-ninja.dev/) — APIs rápidas com Django usando type hints, no estilo FastAPI. 🇺🇸
- [Litestar](https://litestar.dev/) — Framework ASGI moderno e completo para APIs. 🇺🇸
- [Streamlit](https://streamlit.io/) — Crie apps de dados e dashboards só com Python, sem front-end. 🇺🇸
- [pandas](https://pandas.pydata.org/) — A biblioteca padrão para análise e manipulação de dados tabulares. 🇺🇸
- [NumPy](https://numpy.org/) — Arrays numéricos e álgebra linear — a base de todo o ecossistema científico. 🇺🇸
- [Polars](https://pola.rs/) — DataFrames em Rust, muito mais rápidos que o pandas em dados grandes; versão 1.0 em 2024. 🆕 🇺🇸
- [Matplotlib](https://matplotlib.org/) — A biblioteca clássica de gráficos. 🇺🇸
- [seaborn](https://seaborn.pydata.org/) — Gráficos estatísticos bonitos com poucas linhas, sobre o Matplotlib. 🇺🇸
- [Plotly (Python)](https://plotly.com/python/) — Gráficos interativos para web e notebooks. 🇺🇸
- [SciPy](https://scipy.org/) — Algoritmos científicos: otimização, integração, estatística, sinais. 🇺🇸
- [scikit-learn](https://scikit-learn.org/stable/) — Machine learning clássico com API consistente e documentação exemplar. 🇺🇸
- [PyTorch](https://pytorch.org/) — O framework de deep learning dominante em pesquisa e na indústria. 🇺🇸
- [Keras](https://keras.io/) — API de alto nível para deep learning, sobre JAX, TensorFlow ou PyTorch. 🇺🇸
- [Requests](https://requests.readthedocs.io/en/latest/) — HTTP para humanos: a forma mais simples de consumir APIs. 🇺🇸
- [HTTPX](https://www.python-httpx.org/) — Cliente HTTP moderno, com suporte a `async` e HTTP/2. 🇺🇸
- [Pydantic](https://docs.pydantic.dev/latest/) — Validação de dados com type hints; base do FastAPI e de muitos SDKs de IA. 🇺🇸
- [SQLAlchemy](https://www.sqlalchemy.org/) — O ORM e toolkit SQL mais usado em Python. 🇺🇸
- [Typer](https://typer.tiangolo.com/) — Crie CLIs com type hints, do criador do FastAPI. 🇺🇸
- [Rich](https://rich.readthedocs.io/en/stable/) — Texto formatado, tabelas, progresso e tracebacks bonitos no terminal. 🇺🇸
- [Textual](https://textual.textualize.io/) — Aplicações de terminal (TUI) com widgets e CSS. 🇺🇸
- [Playwright for Python](https://playwright.dev/python/) — Automação de navegador moderna e confiável, da Microsoft. 🇺🇸
- [Selenium](https://www.selenium.dev/documentation/) — Automação de navegador clássica, com muitos tutoriais em português. 🇺🇸
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) — Extraia dados de HTML de forma simples (web scraping). 🇺🇸
- [Scrapy](https://www.scrapy.org/) — Framework completo para web scraping em escala. 🇺🇸
- [Celery](https://docs.celeryq.dev/en/stable/) — Filas de tarefas assíncronas e agendamento distribuído. 🇺🇸
- [tkinter (PT-BR)](https://docs.python.org/pt-br/3/library/tkinter.html) — Interfaces gráficas com a biblioteca que já vem com o Python.
- [Qt for Python (PySide6)](https://doc.qt.io/qtforpython-6/) — Interfaces gráficas profissionais e multiplataforma com Qt. 🇺🇸
- [Kivy](https://kivy.org/) — Apps multiplataforma (inclusive Android/iOS) em Python. 🇺🇸
- [spaCy](https://spacy.io/) — Processamento de linguagem natural industrial, com modelo em português. 🇺🇸
- [NLTK](https://www.nltk.org/) — Toolkit clássico de PLN para ensino e pesquisa. 🇺🇸

## 🧪 Projetos práticos e desafios
- [Exercícios de Python 3 (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dm6wYOIW20Nyg12TAjmMGT-) — Mais de 100 exercícios resolvidos em vídeo pelo Guanabara — faça antes de ver a solução.
- [30 dias de Python (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3J6hIY4PZ13BWOqoJ9zDUq3) — Um desafio por dia, em português, para criar o hábito de programar.
- [Construindo um pacote Python do zero (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3LiHhK1upnjpHiFzcJ472QS) — Crie, teste, documente e publique sua própria biblioteca no PyPI.
- [CLIs — Interfaces de linha de comando com Python (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3IvU8rfQdwfiAwf180Vr_o-) — Ferramentas de terminal com argparse, Typer e Rich.
- [Web Scraping com Python (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3K2IUFOEF0YG6T9fEJwqhJo) — Colete dados de sites reais com Requests, Beautiful Soup e Selenium.
- [Estruturas de dados e algoritmos (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm0-RUXh2_sw-nnQUxndFZqU) — Pilhas, filas, listas ligadas, árvores e algoritmos clássicos em Python.
- [Padrões de Projeto — Design Patterns GoF (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm0VY5YrMrafWaQY2EnJ3j8H) — Os 23 padrões do GoF implementados em Python, um por vídeo.
- [Codewars — Python](https://www.codewars.com/?language=python) — Katas por nível de dificuldade, com soluções da comunidade para comparar. 🇺🇸
- [HackerRank — Python](https://www.hackerrank.com/domains/python) — Trilha de desafios específicos de Python, do básico a regex e XML. 🇺🇸
- [Advent of Code](https://adventofcode.com/) — 25 quebra-cabeças por dezembro, resolvidos por metade da comunidade em Python. 🇺🇸
- [Project Euler](https://projecteuler.net/) — Problemas matemáticos que exigem programação eficiente. 🇺🇸
- [CheckiO](https://checkio.org/) — Jogo de programação em que todos os desafios são resolvidos em Python. 🇺🇸
- [Practice Python](https://www.practicepython.org/) — Exercícios curtos para iniciantes, com soluções. 🇺🇸
- [Python Exercises (w3resource)](https://www.w3resource.com/python-exercises/) — Centenas de exercícios por tema (strings, listas, pandas, NumPy). 🇺🇸
- [Edabit — Python](https://edabit.com/challenges/python3) — Mais de 2.500 desafios curtos, do muito fácil ao expert. 🇺🇸
- [CodinGame](https://www.codingame.com/start/) — Aprenda resolvendo puzzles e jogos de programação, com Python entre as linguagens. 🇺🇸
- [Kaggle Competitions](https://www.kaggle.com/competitions) — Competições de dados e ML com notebooks públicos para aprender. 🇺🇸
- [The Big Book of Small Python Projects — gratuito online](https://inventwithpython.com/bigbookpython/) — 81 projetos pequenos e completos (jogos, simulações, utilitários) para digitar e modificar. 🇺🇸
- [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) — Todos os algoritmos clássicos implementados em Python, para estudo. 🇺🇸
- [learn-python (trekhleb)](https://github.com/trekhleb/learn-python) — Playground e cheatsheet: scripts organizados por tópico, com testes. 🇺🇸
- [geekcomputers/Python](https://github.com/geekcomputers/Python) — Centenas de scripts de exemplo da comunidade para se inspirar. 🇺🇸
- [Build your own X](https://github.com/codecrafters-io/build-your-own-x) — Recrie tecnologias (banco de dados, shell, interpretador) — muitos tutoriais em Python. 🇺🇸
- [project-based-learning — Python](https://github.com/practical-tutorials/project-based-learning) — Lista de tutoriais baseados em projetos, com seção grande de Python. 🇺🇸
- [app-ideas](https://github.com/florinpop17/app-ideas) — Ideias de aplicações por nível para praticar em qualquer linguagem. 🇺🇸
- [Pybites](https://pybit.es/) — Comunidade e plataforma de exercícios para virar desenvolvedor Python. 🇺🇸

## 🤖 IA na prática
Python é a linguagem em que a IA moderna é escrita — PyTorch, Transformers, LangChain e os SDKs de todos os grandes modelos são Python-first. Isso tem duas consequências para quem estuda: os assistentes de IA são **muito bons em Python** (é a linguagem com mais código de treinamento), e aprender Python é o caminho mais curto para *construir* com IA, não só usá-la.

**Para aprender**
- Cole um *traceback* inteiro (ex.: `TypeError: can only concatenate str (not "int") to str`) junto com o trecho de código e peça: *"explique a causa, mostre a correção e diga como evitar isso no futuro"*.
- Peça para reescrever um trecho seu de forma **pythônica** (*list comprehension*, `with`, `enumerate`, `pathlib`, f-strings) e para justificar cada mudança.
- Peça **exercícios com testes em pytest** sobre o tópico que está estudando: você escreve a solução, o teste diz se passou.
- Peça para adicionar *type hints* a uma função sua e depois rode `mypy` ou `ty` para ver se a IA acertou.
- Use o REPL ou um notebook para **conferir cada afirmação** da IA: `help(obj)`, `dir(obj)` e `type(x)` não mentem.

**Para trabalhar**
- Use [GitHub Copilot](https://github.com/features/copilot), [Cursor](https://cursor.com/) ou [Claude Code](https://code.claude.com/docs/en/overview) para: escrever testes pytest, gerar *docstrings*, migrar scripts para `pathlib`/`dataclasses`/`asyncio`, converter pandas em Polars, criar automações e explicar código legado.
- Depois de **cada** sugestão aceita, rode `ruff check`, `pytest` e o verificador de tipos. Se o código só funciona com `# type: ignore`, `except: pass` ou `eval`, a sugestão provavelmente está errada.
- Em notebooks, o [Jupyter AI](https://jupyter-ai.readthedocs.io/en/latest/) e o [Colab](https://colab.research.google.com/) já trazem assistente integrado para explicar erros e gerar células.

**Limites e boas práticas**
- IA **inventa funções e parâmetros** de bibliotecas (principalmente pandas, LangChain e SDKs que mudam rápido). Confirme na documentação oficial e na versão instalada (`pip show pacote`).
- IA **inventa nomes de pacotes**: nunca rode `pip install` num pacote sugerido sem conferir no [PyPI](https://pypi.org/) — pacotes falsos com nomes "alucinados" são um vetor real de ataque.
- Desconfie de `eval()`/`exec()`, `pickle` de fontes externas, SQL montado com f-strings e senhas no código: IA repete esses padrões inseguros com frequência.
- Não cole código proprietário, segredos ou dados de clientes em ferramentas sem a política da sua empresa.
- Entenda o que você aceita: em entrevista e em produção, o código é seu.

**Python é a linguagem da IA.** Aprender Python abre a porta para construir aplicações com LLMs e modelos de machine learning — as principais ferramentas e cursos:
- [Claude Code](https://code.claude.com/docs/en/overview) — Agente de código no terminal: escreve testes pytest, refatora e explica tracebacks. 🆕 🇺🇸
- [GitHub Copilot](https://github.com/features/copilot) — Autocomplete e chat com IA no editor; gratuito para estudantes e com plano free. 🇺🇸
- [Cursor](https://cursor.com/) — Editor baseado no VS Code com IA integrada ao fluxo de trabalho. 🇺🇸
- [Jupyter AI](https://jupyter-ai.readthedocs.io/en/latest/) — Assistente de IA dentro do JupyterLab, com o comando mágico `%%ai`. 🇺🇸
- [Anthropic Python SDK](https://github.com/anthropics/anthropic-sdk-python) — SDK oficial para usar os modelos Claude em Python. 🇺🇸
- [OpenAI Python SDK](https://github.com/openai/openai-python) — SDK oficial da OpenAI, com tipos e suporte a `async`. 🇺🇸
- [Google Gen AI Python SDK](https://github.com/googleapis/python-genai) — SDK oficial para os modelos Gemini. 🆕 🇺🇸
- [Ollama Python](https://github.com/ollama/ollama-python) — Rode modelos abertos localmente e use-os a partir do Python. 🆕 🇺🇸
- [LangChain (Python)](https://docs.langchain.com/oss/python/langchain/overview) — Framework para aplicações com LLMs: chains, RAG, ferramentas. 🇺🇸
- [LangGraph](https://docs.langchain.com/oss/python/langgraph/overview) — Agentes com estado e fluxos controlados, sobre o LangChain. 🆕 🇺🇸
- [LlamaIndex](https://developers.llamaindex.ai/python/framework/) — Framework para conectar LLMs aos seus dados (RAG). 🇺🇸
- [Pydantic AI](https://pydantic.dev/docs/ai/overview/) — Framework de agentes com saídas validadas por tipos, da equipe do Pydantic. 🆕 🇺🇸
- [CrewAI](https://docs.crewai.com/) — Orquestração de múltiplos agentes de IA em Python. 🆕 🇺🇸
- [smolagents (Hugging Face)](https://huggingface.co/docs/smolagents/index) — Agentes minimalistas que escrevem e executam código Python. 🆕 🇺🇸
- [Model Context Protocol — SDK Python](https://github.com/modelcontextprotocol/python-sdk) — Crie servidores MCP em Python para dar ferramentas a Claude, Cursor e outros agentes. 🆕 🇺🇸
- [browser-use](https://github.com/browser-use/browser-use) — Agentes que navegam na web, em Python sobre o Playwright. 🆕 🇺🇸
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index) — Milhares de modelos pré-treinados (texto, imagem, áudio) em poucas linhas. 🇺🇸
- [Gradio](https://gradio.app/) — Crie interfaces web para modelos de ML em minutos. 🇺🇸
- [LangChain e LangGraph com Python — curso completo (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm09IqqLYIwLF5dGrcbJzFZc) — Curso gratuito em português sobre construir aplicações e agentes com LLMs. 🆕
- [Anthropic Academy](https://anthropic.skilljar.com/) — Cursos gratuitos da Anthropic sobre a API, engenharia de prompts e agentes, com exemplos em Python. 🆕 🇺🇸
- [Anthropic Courses (GitHub)](https://github.com/anthropics/courses) — Notebooks Jupyter dos cursos da Anthropic: fundamentos da API, prompts, tool use. 🆕 🇺🇸
- [Hugging Face Learn](https://huggingface.co/learn) — Cursos gratuitos de LLMs, agentes, deep RL e visão, todos em Python. 🇺🇸
- [Generative AI for Beginners (Microsoft)](https://github.com/microsoft/generative-ai-for-beginners) — 21 lições com código Python para construir apps com IA generativa. 🆕 🇺🇸
- [ML for Beginners (Microsoft)](https://github.com/microsoft/ML-For-Beginners) — 12 semanas de machine learning clássico com scikit-learn. 🇺🇸
- [Practical Deep Learning for Coders (fast.ai)](https://course.fast.ai/) — Curso gratuito que ensina deep learning de cima para baixo, em Python e PyTorch. 🇺🇸
- [DeepLearning.AI — cursos](https://www.deeplearning.ai/courses) — Cursos curtos gratuitos de Andrew Ng e parceiros sobre LLMs, agentes e RAG. 🇺🇸
- [Machine Learning Crash Course (Google)](https://developers.google.com/machine-learning/crash-course) — Introdução prática a ML do Google, com exercícios em Python. 🇺🇸
- [Kaggle Learn — Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning) — Primeiro modelo de ML em algumas horas, com scikit-learn. 🇺🇸
- [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Tutoriais oficiais do PyTorch, do tensor ao modelo em produção. 🇺🇸
- [scikit-learn — User Guide](https://scikit-learn.org/stable/user_guide.html) — O guia oficial, que também é um ótimo curso de ML clássico. 🇺🇸
- [Neural Networks: Zero to Hero (Andrej Karpathy)](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) — Construa redes neurais e um GPT do zero em Python, com o ex-diretor de IA da Tesla. 🇺🇸

## 📜 Certificações
Não existe certificação oficial da Python Software Foundation. As mais reconhecidas são as do **OpenEDG Python Institute** (PCEP, PCAP, PCPP), aceitas internacionalmente. No Brasil, empregadores costumam valorizar mais **projetos publicados e domínio prático** do que certificados; os certificados de conclusão de curso abaixo ajudam no currículo, mas não substituem portfólio.
- [PCEP — Certified Entry-Level Python Programmer (Python Institute)](https://pythoninstitute.org/pcep) — Certificação de entrada, reconhecida internacionalmente, para fundamentos da linguagem. 💰 🇺🇸
- [PCAP — Certified Associate in Python Programming (Python Institute)](https://pythoninstitute.org/pcap) — Nível associado: POO, módulos, exceções, strings e biblioteca padrão. 💰 🇺🇸
- [PCPP1 — Certified Professional in Python Programming 1 (Python Institute)](https://pythoninstitute.org/pcpp1) — Nível profissional: POO avançada, GUI, redes, boas práticas. 💰 🇺🇸
- [Python Institute — trilhas de certificação](https://pythoninstitute.org/certification-tracks) — Visão geral de todas as certificações e exames do OpenEDG Python Institute. 🇺🇸
- [Google IT Automation with Python (Coursera)](https://www.coursera.org/professional-certificates/google-it-automation) — Certificado profissional do Google: Python, Git, automação e resolução de problemas. 💰 🇺🇸
- [Python for Data Science, AI & Development (IBM no Coursera)](https://www.coursera.org/learn/python-for-applied-data-science-ai) — Curso da IBM com certificado, parte de vários certificados profissionais de dados. 💰 🇺🇸
- [HackerRank — Python (Basic) Skills Certification](https://www.hackerrank.com/skills-verification/python_basic) — Teste gratuito de 90 minutos que gera um certificado para o perfil. 🇺🇸
- [Scientific Computing with Python — certificação freeCodeCamp](https://www.freecodecamp.org/learn/scientific-computing-with-python) — Certificação gratuita após concluir os cinco projetos do currículo. 🇺🇸
- [Curso em Vídeo — certificado gratuito de Python](https://www.cursoemvideo.com/curso/python-3-mundo-1/) — Certificado gratuito ao concluir cada Mundo do curso no site.
- [Data Science Academy — certificado gratuito](https://www.datascienceacademy.com.br/course/fundamentos-de-linguagem-python-do-basico-a-aplicacoes-de-ia) — Certificado de conclusão do curso gratuito de Python da DSA. 🆕
- [Formação Python (Alura) — com certificado](https://www.alura.com.br/formacao-linguagem-python) — Certificado da Alura, reconhecido por empresas brasileiras. 💰

## 💼 Carreira e vagas
Python aparece como requisito na maior parte das vagas de ciência e engenharia de dados, IA/machine learning, automação/DevOps e back-end (Django, FastAPI) no Brasil, além de ser a linguagem de entrada mais comum em processos de estágio e trainee. Dica: nos repositórios de vagas do GitHub abaixo, pesquise por "Python" nas issues abertas.
- [Python Developers Survey 2024 (PSF + JetBrains)](https://lp.jetbrains.com/python-developers-survey-2024/) — Pesquisa oficial com 30 mil devs: usos, ferramentas, versões e tendências. 🆕 🇺🇸
- [The State of Python 2024 (JetBrains)](https://blog.jetbrains.com/pycharm/2024/12/the-state-of-python/) — Análise dos dados da pesquisa: onde Python cresce e o que o mercado usa. 🆕 🇺🇸
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — Python segue entre as linguagens mais usadas e desejadas. 🆕 🇺🇸
- [TIOBE Index](https://www.tiobe.com/tiobe-index/) — Índice mensal de popularidade em que Python lidera desde 2021. 🇺🇸
- [Python Success Stories (python.org)](https://www.python.org/success-stories/) — Casos reais de empresas e projetos que usam Python. 🇺🇸
- [Python Job Board (python.org)](https://www.python.org/jobs/) — Quadro de vagas oficial da comunidade Python. 🇺🇸
- [Programathor — vagas Python](https://programathor.com.br/jobs-python) — Vagas de tecnologia no Brasil filtradas por Python.
- [GeekHunter](https://www.geekhunter.com/pt) — Plataforma brasileira onde empresas fazem propostas a devs.
- [Coodesh](https://coodesh.com/) — Vagas tech no Brasil com processos seletivos padronizados.
- [Remotar](https://remotar.com.br/) — Vagas 100% remotas para brasileiros.
- [backend-br/vagas](https://github.com/backend-br/vagas) — Vagas de back-end (muitas com Python/Django/FastAPI) publicadas como issues no GitHub.
- [datascience-br/vagas](https://github.com/datascience-br/vagas) — Vagas de ciência e engenharia de dados no GitHub — Python é o requisito número um.
- [DevOps-Brasil/Vagas](https://github.com/DevOps-Brasil/Vagas) — Vagas de DevOps/SRE, onde Python é a linguagem de automação padrão.
- [RemoteOK — vagas Python](https://remoteok.com/remote-python-jobs) — Vagas remotas internacionais com Python. 🇺🇸
- [Working Nomads — vagas Python](https://www.workingnomads.com/remote-python-jobs) — Outro agregador de vagas remotas com filtro de Python. 🇺🇸
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Preparação completa para entrevistas técnicas. 🇺🇸

## 👥 Comunidades
- [Python Brasil — comunidades locais](https://python.org.br/comunidades-locais/) — Lista dos GruPys, PyLadies e grupos regionais em todo o país.
- [Python Brasil no Telegram (grupo @pythonbr)](https://t.me/pythonbr) — Grupo de discussão da comunidade brasileira, com milhares de membros.
- [Python Brasil no Telegram (canal @pythonbrasil)](https://t.me/pythonbrasil) — Canal de avisos, eventos e conteúdo da comunidade.
- [Lista python-brasil (Google Groups)](https://groups.google.com/g/python-brasil) — Lista de discussão histórica da comunidade, ativa desde os anos 2000.
- [PyLadies Brasil](https://brasil.pyladies.com/) — Comunidade de mulheres na programação Python, com capítulos em dezenas de cidades.
- [Python Brasil 2025 (conferência)](https://2025.pythonbrasil.org.br/) — A conferência nacional da comunidade: tutoriais, palestras e sprints (São Paulo, outubro de 2025). 🆕
- [Python Nordeste 2026](https://2026.pythonnordeste.org/) — Conferência regional do Nordeste, uma das mais tradicionais do país. 🆕
- [Python Brasil no GitHub](https://github.com/pythonbrasil) — Organização com o site, os eventos e projetos da comunidade.
- [Python Discord](https://www.pythondiscord.com/) — O maior servidor de Python do Discord, com canais de ajuda e eventos. 🇺🇸
- [Discussions on Python.org](https://discuss.python.org/) — Fórum oficial: ajuda, ideias e discussões de desenvolvimento da linguagem. 🇺🇸
- [r/Python](https://www.reddit.com/r/Python/) — Subreddit principal, com notícias e projetos. 🇺🇸
- [r/learnpython](https://www.reddit.com/r/learnpython/) — Subreddit para tirar dúvidas de quem está aprendendo. 🇺🇸
- [Python Software Foundation](https://www.python.org/psf-landing/) — A fundação que mantém a linguagem; associe-se gratuitamente. 🇺🇸
- [PyCon US 2026](https://us.pycon.org/2026/) — A maior conferência de Python do mundo; palestras vão para o YouTube. 🆕 🇺🇸
- [PyLadies (global)](https://pyladies.com/locations/) — Todos os capítulos PyLadies no mundo. 🇺🇸
- [TabNews](https://www.tabnews.com.br/) — Comunidade brasileira de conteúdo técnico criada por Filipe Deschamps.
- [He4rt Developers](https://heartdevs.com/) — Comunidade brasileira open source com Discord ativo e projetos em várias linguagens.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Comunidade brasileira com dicas, cursos, mentoria e canal de Python.
- [DEV Community — devs brasileiros](https://dev.to/t/braziliandevs) — Tag com artigos em português da comunidade brasileira.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Diretório de grupos brasileiros no Telegram, incluindo vários de Python.

## 🚨 Como contribuir
Achou um link quebrado, um curso novo ou uma ferramenta que merece estar aqui? Abra uma issue usando os templates do repositório ou envie um pull request. Critérios: link funcionando, conteúdo legal e gratuito ou claramente marcado como pago, com uma linha de descrição. Detalhes em [CONTRIBUTING.md](./CONTRIBUTING.md).

## 📄 Licença
Este projeto está sob a licença [MIT](./LICENSE). Feito com 💙 por [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) e pela comunidade do [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil).

## 💙 Apoie o projeto
Dê uma ⭐ neste repositório e no [guia principal](https://github.com/arthurspk/guiadevbrasil), compartilhe com quem está começando e siga o projeto nas redes:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
