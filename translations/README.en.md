<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="../images/guia.png" alt="Guia Dev Brasil" width="160" height="160">
  </a>
  <h1 align="center">Python Guide</h1>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/arthurspk/guiadepython?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/arthurspk/guiadepython?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/last-commit/arthurspk/guiadepython?style=flat-square" alt="Last commit">
  <img src="https://img.shields.io/github/license/arthurspk/guiadepython?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs Welcome">
</p>

> Complete Python guide: learning paths, courses, books, channels, tools and communities
> to get into the field and grow. Last review: September 2026.
>
> This is a translation of the Brazilian Portuguese guide. Resources are curated for the Brazilian community, so many are in Portuguese; 🇺🇸 marks English-language content.

## 🌍 Languages
[🇧🇷 Português](../README.md) · 🇺🇸 English (you are here)

## 📚 Table of contents
- [🎯 About this guide](#-about-this-guide)
- [🗺️ Roadmap](#-roadmap)
- [🚀 Where to start](#-where-to-start)
- [🎓 Free courses](#-free-courses)
- [💰 Paid courses](#-paid-courses)
- [📖 Documentation](#-documentation)
- [📚 Books](#-books)
- [🎥 YouTube channels](#-youtube-channels)
- [🎙️ Podcasts](#-podcasts)
- [📰 Sites, blogs and newsletters](#-sites-blogs-and-newsletters)
- [🛠️ Tools](#-tools)
- [🧪 Hands-on projects and challenges](#-hands-on-projects-and-challenges)
- [🤖 AI in practice](#-ai-in-practice)
- [📜 Certifications](#-certifications)
- [💼 Career and jobs](#-career-and-jobs)
- [👥 Communities](#-communities)
- [🚨 How to contribute](#-how-to-contribute)
- [📄 License](#-license)
- [💙 Support the project](#-support-the-project)

## 🎯 About this guide
Python is a general-purpose, interpreted language with clean syntax, created by Guido van Rossum in 1991 and maintained by the Python Software Foundation. Today it is the most used language on GitHub and the default language of data science, artificial intelligence, automation and back-end development (Django, FastAPI). It gets a new version every October: **3.13** (2024) brought the new REPL and the first GIL-free build, and **3.14** (2025) brought t-strings, subinterpreters and official free-threading.

This guide is for people who want to learn Python from scratch — even without ever having programmed — and for programmers who want to specialize in web, data or AI. **Portuguese and free** resources come first in every section; 💰 marks paid content, 🇺🇸 English-language content and 🆕 material published or updated between 2024 and 2026. Every link was verified on the date of the last review.

## 🗺️ Roadmap
- [roadmap.sh — Python Developer Roadmap](https://roadmap.sh/python) — Community-made visual, interactive roadmap: what to study, in which order, with links per topic. 🇺🇸
- [Python para quem está começando (Python Brasil)](https://python.org.br/introducao/) — Brazilian community page with the suggested path for beginners, in Portuguese.
- [O Guia do Mochileiro para Python (PT-BR)](https://python-guide-pt-br.readthedocs.io/pt-br/latest/) — Translation of the Hitchhiker's Guide: installation, environments, project structure and good practices.
- [python-roadmap (Eduardo Mendes)](https://github.com/dunossauro/python-roadmap) — Portuguese roadmap maintained by the creator of Live de Python, from basics to advanced.
- [Python For Beginners (python.org)](https://www.python.org/about/gettingstarted/) — Official starting point: install, pick learning material and take the first steps. 🇺🇸
- [BeginnersGuide (wiki oficial)](https://wiki.python.org/moin/BeginnersGuide) — Official beginner's guide, with separate tracks for people who never programmed and for programmers. 🇺🇸

**Summary path** (follow in order; each step has resources in the sections below):

1. **Installation and first script** — latest Python 3, VS Code or Thonny, `python hello.py` in the terminal.
2. **Fundamentals** — variables, types, `if`, `for`/`while`, functions, strings and f-strings, input and output.
3. **Data structures** — lists, tuples, dictionaries, sets, comprehensions, slicing, `enumerate`/`zip`.
4. **Modules and environments** — importing from the standard library, `venv`, `pip`/`uv`, `pyproject.toml`, reading and writing files, JSON and CSV.
5. **Intermediate Python** — object orientation, exceptions, type hints, generators, decorators, `dataclasses`, `pathlib`.
6. **Quality** — testing with `pytest`, formatting and linting with Ruff, type checking with mypy/Pyright, Git and GitHub.
7. **Specialization** — web (Django, FastAPI, Flask), data (pandas, NumPy, Jupyter, Polars), automation (Requests, Playwright, Selenium) or AI (PyTorch, scikit-learn, LLM SDKs).
8. **Advanced** — `asyncio` and concurrency, packaging and publishing to PyPI, performance (profiling, free-threading), contributing to open-source projects.

## 🚀 Where to start
1. **Install Python** from the [official site](https://www.python.org/downloads/) (on Windows, tick "Add python.exe to PATH") and an editor: [VS Code with the Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) or [Thonny](https://thonny.org/), built for beginners.
2. **Try it without installing anything** on [Google Colab](https://colab.research.google.com/) or [Online Python](https://www.programiz.com/python-programming/online-compiler/) — and use [Python Tutor](https://pythontutor.com/) to watch the code run step by step.
3. **Take a course in Portuguese:** [Curso em Vídeo — Mundo 1](https://www.youtube.com/playlist?list=PLHz_AreHm4dlKP6QQCekuIPky1CiwmdI6) (Guanabara) or [Curso Completo de Python 2026](https://www.youtube.com/watch?v=WexDtLkN77k) (Hashtag Programação).
4. **Read the official tutorial** — [The Python Tutorial](https://docs.python.org/pt-br/3/tutorial/index.html) is fully translated to Portuguese and covers everything a course covers.
5. **Practice every day:** the [Curso em Vídeo Python 3 exercises](https://www.youtube.com/playlist?list=PLHz_AreHm4dm6wYOIW20Nyg12TAjmMGT-), [Practice Python](https://www.practicepython.org/) and [Codewars](https://www.codewars.com/?language=python) katas.
6. **Go deeper:** [Eduardo Mendes' livestreams](https://www.youtube.com/playlist?list=PLOQgLBuj2-3Kc7PBT3BwiM-E99LQnjMln) and the free book [Python Fluente, 2nd edition](https://pythonfluente.com/2/) take you from intermediate to advanced.
7. **Pick a track:** web with [FastAPI do Zero](https://fastapidozero.dunossauro.com/estavel/) or [Django](https://www.youtube.com/playlist?list=PLbIBj8vQhvm2mpbtmubbG3-pPGnMxlaEq); data with the [free Data Science Academy course](https://www.datascienceacademy.com.br/course/fundamentos-de-linguagem-python-do-basico-a-aplicacoes-de-ia); AI with [Hugging Face Learn](https://huggingface.co/learn).
8. **Build and publish a project** on GitHub: a [package on PyPI](https://www.youtube.com/playlist?list=PLOQgLBuj2-3LiHhK1upnjpHiFzcJ472QS), a [CLI](https://www.youtube.com/playlist?list=PLOQgLBuj2-3IvU8rfQdwfiAwf180Vr_o-) or one of the [81 projects in The Big Book of Small Python Projects](https://inventwithpython.com/bigbookpython/).

Your first project in 30 seconds:

```bash
python3 --version               # must be 3.10 or newer
mkdir hello-python && cd hello-python
python3 -m venv .venv           # isolated virtual environment for the project
source .venv/bin/activate       # Windows: .venv\Scripts\activate
```

```python
# hello.py
def greeting(name: str) -> str:
    return f"Hello, {name}!"

if __name__ == "__main__":
    print(greeting("Guia Dev Brasil"))
```

```bash
python hello.py                 # run it
uv run hello.py                 # modern alternative: uv creates the environment for you
```

## 🎓 Free courses
### In Portuguese
- [Curso de Python 3 — Mundo 1: Fundamentos (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dlKP6QQCekuIPky1CiwmdI6) — Brazil's most-watched Python course, with Gustavo Guanabara: logic, variables, conditions and loops.
- [Curso de Python 3 — Mundo 2: Estruturas de Controle (Curso em Vídeo)](https://www.cursoemvideo.com/curso/python-3-mundo-2/) — Second stage, with a free certificate on the site: `if`, `while`, `for` and dozens of exercises.
- [Curso de Python 3 — Mundo 3: Estruturas Compostas (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dksnH2jVTIVNviIMBVYyFnH) — Tuples, lists, dictionaries, functions and modules — closes the Curso em Vídeo track.
- [Curso Completo de Python 2026 (Iniciantes) + Exercícios (Hashtag Programação)](https://www.youtube.com/watch?v=WexDtLkN77k) — Single, recent lesson to start from scratch, with solved exercises. 🆕
- [Curso de Python — Programação (Hashtag Programação)](https://www.youtube.com/playlist?list=PLpdAy0tYrnKyCZsE-ifaLV1xnkXBE9n7T) — Playlist with dozens of short lessons, from basics to automation and data analysis.
- [Aprenda Python — Curso COMPLETO para INICIANTES [2025] (Brenno Sullivan)](https://www.youtube.com/watch?v=EV7Idm_mkxo) — Single-video course published in 2025, straight to the point. 🆕
- [Python para iniciantes — aprenda do ZERO! (Asimov Academy)](https://www.youtube.com/playlist?list=PLuvoZvhxWzZCYMiKtkcMr-aYJ3KV47V0G) — Free series from the Brazilian Python and AI school, designed for people who never programmed.
- [Curso Gratuito de Python para Dados (Asimov Academy)](https://www.asimov.academy/misc/complementares/cursos-gratuitos/dados/) — Free course on the Asimov platform, focused on Python for data analysis.
- [Fundamentos de Linguagem Python — Do Básico a Aplicações de IA (Data Science Academy)](https://www.datascienceacademy.com.br/course/fundamentos-de-linguagem-python-do-basico-a-aplicacoes-de-ia) — Free course with certificate launched in September 2025, from zero to AI applications. 🆕
- [Curso Python para Iniciantes Completo (Didática Tech)](https://www.youtube.com/playlist?list=PLyqOvdQmGdTSEPnO0DKgHlkXb8x3cyglD) — Complete, didactic course, popular with people moving into data.
- [Curso Python para Machine Learning e Análise de Dados (Didática Tech)](https://www.youtube.com/playlist?list=PLyqOvdQmGdTR46HUxDA6Ymv4DGsIjvTQ-) — Natural follow-up: NumPy, pandas and first machine learning models.
- [Introdução à Ciência da Computação com Python (IME/USP — YouTube)](https://www.youtube.com/playlist?list=PLcoJJSvnDgcKpOi_UeneTNTIVOigRQwcn) — Lessons by professor Fabio Kon (USP): computing fundamentals using Python.
- [Introdução à Ciência da Computação com Python — Parte 1 (USP no Coursera)](https://www.coursera.org/learn/ciencia-computacao-python-conceitos) — Coursera version of the USP course, with auto-graded exercises (audit for free).
- [Introdução à Ciência da Computação com Python — Parte 2 (USP no Coursera)](https://www.coursera.org/learn/ciencia-computacao-python-conceitos-2) — Second part: dictionaries, files, object orientation and recursion.
- [Playlist Python — Eduardo Mendes (Live de Python)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3Kc7PBT3BwiM-E99LQnjMln) — Hundreds of Dunossauro's weekly livestreams about the language, from basics to advanced topics — the biggest free reference in Portuguese. 🆕
- [Quer aprender Python? (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3LwyKrvIde88moVcFWAN2Xz) — Introductory sequence for people who want to start with Dunossauro's livestreams.
- [Orientação a objetos em Python (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3L_L6ahsBVA_SzuGtKre3OK) — Classes, inheritance, dunder methods and protocols explained patiently.
- [Curso de FastAPI 2025 (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3KT9ZWvPmaGFQ0KjIez0403) — 2025 live lessons of the FastAPI do Zero course: complete API with tests, database and JWT auth. 🆕
- [FastAPI do Zero (livro-curso gratuito)](https://fastapidozero.dunossauro.com/estavel/) — Text material of the course, updated every edition, with code on GitHub. 🆕
- [Curso de Type Hints no Python do Básico ao Avançado (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm04EuddtleOAoEmfU9vwQlN) — Type annotations, `typing`, generics and static checking with mypy/Pyright.
- [Expressões Regulares em Python (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm1VnTa2Np5vDzCxVtyaYLMr) — The `re` module from scratch, with practical examples.
- [Programação concorrente em Python (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm0YZFsgLK4Fhc0a1kRxj_xx) — Threads, processes, `asyncio` and the GIL explained in practice.
- [Django (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm2mpbtmubbG3-pPGnMxlaEq) — Free Django playlist, the most used Python web framework in Brazil.
- [Curso de introdução ao desenvolvimento Web com Python 3 e Django (Rafael Zottesso)](https://www.youtube.com/playlist?list=PLjv17QYEBJPpd6nI-MXpIa4qR7prKfPQz) — From zero to a working website with Django, step by step.
- [Aulas Python (Ignorância Zero)](https://www.youtube.com/playlist?list=PLfCKf0-awunOu2WyLe2pSD2fXUo795xRe) — One of the most complete courses on Brazilian YouTube, with 100+ lessons.
- [Curso de Python (CFBCursos)](https://www.youtube.com/playlist?list=PLx4x_zx8csUhuVgWfy7keQQAy7t1J35TR) — Playlist with short lessons, one concept per video.
- [Curso de Programação com Python — Completo (Bóson Treinamentos)](https://www.youtube.com/playlist?list=PLucm8g_ezqNrrtduPx7s4BM8phepMn9I2) — Long, well-organized course with good coverage of the standard library.
- [Curso de Python (eXcript)](https://www.youtube.com/playlist?list=PLesCEcYj003QxPQ4vTXkt22-E11aQvoVj) — Classic Portuguese course, very didactic for people who never programmed.
- [Curso Python Básico (Solyd Offensive Security)](https://www.youtube.com/playlist?list=PLp95aw034Wn_WtEmlepaDrw8FU8R5azcm) — Basic Python with an information security and automation slant.
- [Curso Completo de Python (Jefferson Lobato)](https://www.youtube.com/playlist?list=PLLVddSbilcul-1bAKtMKoL6wOCmDIPzFJ) — Complete Portuguese course with projects along the way.
- [O Melhor Curso de Python (Zurubabel)](https://www.youtube.com/playlist?list=PL4OAe-tL47sY8SGhtkGoP0eQd4le3badz) — Portuguese course focused on understanding the why of things.
- [Curso de Python Orientado a Objetos (Portal Hugo Cursos)](https://www.youtube.com/playlist?list=PLxNM4ef1Bpxhm8AfK1nDMWPDYXtmVQN-z) — OOP in Python: classes, inheritance, polymorphism and encapsulation.
- [Curso Python p/ Iniciantes (Refatorando)](https://www.youtube.com/playlist?list=PLj7gJIFoP7jdirAFg-fHe9HKOnGLGXSHZ) — Short, objective course for the first steps.
- [Curso: Python Essencial para Data Science (xavecoding)](https://www.youtube.com/playlist?list=PL3ZslI15yo2qCEmnYOa2sq6VQOzQ2CFhj) — The essentials of the language for people going straight into data science.
- [Curso de Selenium com Python (Eduardo Mendes)](https://dunossauro.github.io/curso-python-selenium/) — Browser automation and web testing with Selenium, free, in text + video.
- [Scientific Computing with Python — freeCodeCamp (PT-BR)](https://www.freecodecamp.org/portuguese/learn/scientific-computing-with-python) — freeCodeCamp's interactive curriculum translated to Portuguese, with projects and free certificate.
- [Learn Python — tutorial interativo (PT)](https://www.learnpython.org/pt/) — Interactive in-browser tutorial in Portuguese: read, run the code and move on.
- [Introdução ao Python (Sololearn, PT)](https://www.sololearn.com/pt/learn/courses/python-introduction) — Portuguese course on phone or browser, with short exercises and a community.

### In English
- [CS50's Introduction to Programming with Python (Harvard)](https://cs50.harvard.edu/python/) — Harvard's Python course, free, with auto-graded problem sets. 🇺🇸
- [Python for Everybody (PY4E)](https://www.py4e.com/) — Dr. Chuck's (University of Michigan) complete course with free book, videos and exercises. 🇺🇸
- [Python for Everybody — Specialization (Coursera)](https://www.coursera.org/specializations/python) — The same track on Coursera; audit for free or pay for the certificate. 🇺🇸
- [Google's Python Class](https://developers.google.com/edu/python) — Google's classic course, with videos and exercises, for people with some programming experience. 🇺🇸
- [Crash Course on Python (Google no Coursera)](https://www.coursera.org/learn/python-crash-course) — First course of the Google IT Automation certificate; audit for free. 🇺🇸
- [MIT 6.100L — Introduction to CS and Programming Using Python (OCW)](https://ocw.mit.edu/courses/6-100l-introduction-to-cs-and-programming-using-python-fall-2022/) — MIT's intro course with recorded lectures, slides and problem sets. 🇺🇸
- [Scientific Computing with Python (freeCodeCamp)](https://www.freecodecamp.org/learn/scientific-computing-with-python) — Original English version of freeCodeCamp's interactive curriculum. 🇺🇸
- [Kaggle Learn — Python](https://www.kaggle.com/learn/python) — Quick, hands-on course in notebooks, ideal for people heading into data. 🇺🇸
- [Learn Python — Full Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=rfscVS0vtbw) — Single 4-hour video, one of YouTube's most-watched Python courses. 🇺🇸
- [Python Full Course for Beginners (Programming with Mosh)](https://www.youtube.com/watch?v=_uQrJ0TkZlc) — 6-hour course with automation, data and web projects. 🇺🇸
- [Python for Beginners (Microsoft Developer)](https://www.youtube.com/playlist?list=PLlrxD0HtieHhS8VzuMCfQD4uJ9yne1mE6) — Microsoft's official series with short videos and code on GitHub. 🇺🇸
- [Python Tutorials (Corey Schafer)](https://www.youtube.com/playlist?list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU) — The reference playlist for intermediate concepts: generators, decorators, OOP, modules. 🇺🇸
- [Intermediate Python Programming Course (freeCodeCamp)](https://www.youtube.com/watch?v=HGOBQPFzWKo) — For people past the basics: collections, itertools, threading, logging, decorators. 🇺🇸
- [Advanced Python — Complete Course (Patrick Loeber)](https://www.youtube.com/playlist?list=PLqnslRFeH2UqLwzS0AwKDKLrpYBKzLBy2) — Advanced topics in short, well-explained videos. 🇺🇸
- [Automate with Python — Full Course for Beginners (freeCodeCamp)](https://www.youtube.com/watch?v=PXMJ6FS7llk) — Everyday task automation: spreadsheets, PDFs, e-mails, web. 🇺🇸
- [Data Structures and Algorithms in Python (freeCodeCamp)](https://www.youtube.com/watch?v=pkYVOmU3MgA) — Data structures and algorithms implemented in Python, with exercises. 🇺🇸
- [futurecoder](https://futurecoder.io/) — Free, open-source interactive course with a debugger and hints in the browser. 🇺🇸
- [Learn Python (Codédex)](https://www.codedex.io/python) — Gamified course for beginners, with free chapters. 🇺🇸
- [Intro to Python (Udacity)](https://www.udacity.com/course/introduction-to-python--ud1110) — Free Udacity course to get started with the language. 🇺🇸
- [Python for Data Science (IBM Cognitive Class)](https://cognitiveclass.ai/courses/python-for-data-science) — Free IBM course with badge, aimed at data. 🇺🇸
- [30 Days of Python](https://github.com/Asabeneh/30-Days-Of-Python) — 30-day challenge on GitHub, with one topic and exercises per day. 🇺🇸

## 💰 Paid courses
- [Formação Python (Alura)](https://www.alura.com.br/formacao-linguagem-python) — Alura's complete track, from syntax to object orientation, with certificate. 💰
- [Formação Data Science com Python (Alura)](https://www.alura.com.br/formacao-data-science-python) — Alura track for data analysis with pandas, visualization and statistics. 💰
- [Curso de Python do Zero ao Avançado (Hashtag Treinamentos)](https://www.hashtagtreinamentos.com/curso-python) — 100+ hours focused on automation, data and workplace applications. 💰
- [Asimov Academy](https://www.asimov.academy/) — Brazilian Python and AI school, with tracks in data, web, automation and agents. 💰
- [Python Academy (Vinicius Ramos)](https://pythonacademy.com.br/) — Portuguese courses focused on professional Python and good practices. 💰
- [Cursos do Otávio Miranda](https://otaviomiranda.com.br/) — Site of teacher Luiz Otávio Miranda, author of the Python 3 basic-to-advanced course (140+ hours). 💰
- [Talk Python Training](https://training.talkpython.fm/) — Courses by the creator of the Talk Python podcast, very hands-on and up to date. 💰 🇺🇸
- [Python Morsels](https://www.pythonmorsels.com/) — Weekly exercises with detailed feedback, to write more idiomatic Python. 💰 🇺🇸
- [Hyperskill — Python (JetBrains)](https://hyperskill.org/courses/python) — Project-based track, integrated with PyCharm. 💰 🇺🇸
- [Learn Python 3 (Codecademy)](https://www.codecademy.com/learn/learn-python-3) — Interactive in-browser course; part of the content is free, the rest in the Pro plan. 💰 🇺🇸

## 📖 Documentation
- [Documentação oficial do Python em português](https://docs.python.org/pt-br/3/) — The official documentation, translated by the Brazilian community and always on the latest version.
- [O tutorial do Python (oficial, PT-BR)](https://docs.python.org/pt-br/3/tutorial/index.html) — Official tutorial: the best place to learn the syntax and core concepts.
- [A Biblioteca Padrão do Python (PT-BR)](https://docs.python.org/pt-br/3/library/index.html) — Reference for every module that ships with Python ('batteries included').
- [A Referência da Linguagem Python (PT-BR)](https://docs.python.org/pt-br/3/reference/index.html) — Specification of the language's syntax and semantics.
- [Python HOWTOs (PT-BR)](https://docs.python.org/pt-br/3/howto/index.html) — Official topic guides: regex, logging, sorting, descriptors, annotations, Unicode.
- [Perguntas Frequentes sobre Python (PT-BR)](https://docs.python.org/pt-br/3/faq/index.html) — Official FAQ: design, programming and usage questions.
- [Glossário oficial (PT-BR)](https://docs.python.org/pt-br/3/glossary.html) — Definitions of terms such as iterable, decorator, GIL, duck typing.
- [Configurações e Uso do Python (PT-BR)](https://docs.python.org/pt-br/3/using/index.html) — How to install and configure Python on Windows, macOS and Linux.
- [O que há de novo no Python 3.13 (PT-BR)](https://docs.python.org/pt-br/3/whatsnew/3.13.html) — October 2024 news: new interactive REPL, experimental free-threaded build and JIT. 🆕
- [O que há de novo no Python 3.14 (PT-BR)](https://docs.python.org/pt-br/3/whatsnew/3.14.html) — October 2025 news: t-strings, deferred evaluation of annotations, subinterpreters and official free-threading. 🆕
- [Suporte do Python para threads livres (HOWTO, PT-BR)](https://docs.python.org/pt-br/3/howto/free-threading-python.html) — Official guide to GIL-less Python: how to install it and what changes. 🆕
- [venv — Criação de ambientes virtuais (PT-BR)](https://docs.python.org/pt-br/3/library/venv.html) — Documentation of the module that isolates each project's dependencies.
- [typing — Suporte para dicas de tipo (PT-BR)](https://docs.python.org/pt-br/3/library/typing.html) — Reference for type annotations, the foundation of mypy, Pyright and ty.
- [asyncio — E/S assíncrona (PT-BR)](https://docs.python.org/pt-br/3/library/asyncio.html) — Official documentation of asynchronous programming with `async`/`await`.
- [PEP 8 — Style Guide for Python Code](https://peps.python.org/pep-0008/) — The official style guide: how to format and name Python code. 🇺🇸
- [PEP 20 — The Zen of Python](https://peps.python.org/pep-0020/) — The language's 19 guiding principles (or run `import this`). 🇺🇸
- [Índice de PEPs](https://peps.python.org/) — Every Python Enhancement Proposal: this is where the language evolves. 🇺🇸
- [PEP 703 — Making the GIL Optional in CPython](https://peps.python.org/pep-0703/) — The proposal that made free-threaded Python possible. 🆕 🇺🇸
- [PEP 750 — Template Strings](https://peps.python.org/pep-0750/) — Python 3.14's t-strings: template strings processed before becoming text. 🆕 🇺🇸
- [Python Packaging User Guide (PT-BR)](https://packaging.python.org/pt-br/latest/) — Official packaging guide: `pyproject.toml`, build and publishing to PyPI.
- [Static Typing with Python (typing.python.org)](https://typing.python.org/en/latest/) — Official static typing documentation, with guides and the spec. 🇺🇸
- [Python Developer's Guide](https://devguide.python.org/) — How CPython is developed and how to contribute to the language. 🇺🇸
- [The Hitchhiker's Guide to Python](https://docs.python-guide.org/) — English original of the Hitchhiker's Guide, with more up-to-date sections. 🇺🇸
- [Python 3 Module of the Week (PyMOTW-3)](https://pymotw.com/3/) — A tour of the standard library, module by module, with examples. 🇺🇸
- [Learn X in Y minutes — Python (PT-BR)](https://learnxinyminutes.com/pt-br/python/) — The whole language syntax in a single commented file, in Portuguese.
- [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) — Style guide used at Google, a practical complement to PEP 8. 🇺🇸
- [Python em Windows para iniciantes (Microsoft Learn, PT-BR)](https://learn.microsoft.com/pt-br/windows/dev-environment/python) — How to set up Python, VS Code and WSL on Windows.
- [free-programming-books — Python (PT-BR)](https://github.com/EbookFoundation/free-programming-books/blob/main/books/free-programming-books-pt_BR.md#python) — Community-maintained list of free Python books and handouts in Portuguese.

## 📚 Books
- [Python Fluente, 2ª edição (Luciano Ramalho) — gratuito online](https://pythonfluente.com/2/) — The official translation, released by the author, of the most respected book on idiomatic Python.
- [Pense em Python, 2ª edição (Allen Downey) — gratuito](https://penseallen.github.io/PensePython2e/) — Portuguese translation of Think Python: an introduction to programming using Python.
- [Introdução à Programação com Python, 4ª edição (Nilo Ney Coutinho Menezes) — site do livro](https://python.nilo.pro.br/) — Author's site with support material for the Brazilian classic for beginners, updated for Python 3.12. 🆕
- [Introdução à Programação com Python, 4ª edição (Novatec)](https://novatec.com.br/livros/introducao-python-4ed/) — 2024 edition of Nilo Ney's book, the most recommended in Portuguese for people who never programmed. 🆕 💰
- [Automatize tarefas maçantes com Python, 3ª edição (Novatec)](https://novatec.com.br/livros/automatize-tarefas-macantes-com-python-3ed/) — 2025 translation of Al Sweigart's best-seller: Python to automate your work. 🆕 💰
- [Curso Intensivo de Python, 3ª edição (Novatec)](https://novatec.com.br/livros/curso-intensivo-python-3ed/) — Translation of Python Crash Course: fundamentals and three projects (game, data and web). 💰
- [Black Hat Python, 2ª edição (Novatec)](https://novatec.com.br/livros/black-hat-python-2ed/) — Python applied to offensive security, 2024 edition updated for Python 3. 🆕 💰
- [Python 3 (Casa do Código)](https://www.casadocodigo.com.br/products/livro-python-3) — Introductory book from Casa do Código, in Portuguese. 💰
- [Automate the Boring Stuff with Python, 3rd Edition — gratuito online](https://automatetheboringstuff.com/) — 2025 edition of Al Sweigart's book, free to read on the site. 🆕 🇺🇸
- [Think Python, 3rd Edition — gratuito online](https://allendowney.github.io/ThinkPython/) — 2024 edition with Jupyter notebooks, to learn by programming. 🆕 🇺🇸
- [Beyond the Basic Stuff with Python — gratuito online](https://inventwithpython.com/beyond/) — The step after the basics: good practices, tools, OOP and clean code. 🇺🇸
- [A Byte of Python — gratuito](https://python.swaroopch.com/) — Short, free book for beginners, translated into many languages. 🇺🇸
- [Dive Into Python 3 — gratuito](https://diveintopython3.net/) — Classic for people who already program in another language and want to learn Python 3 fast. 🇺🇸
- [Python for Data Analysis, 3rd Edition (Wes McKinney) — gratuito online](https://wesmckinney.com/book/) — The pandas creator's book, fully open on the author's site. 🇺🇸
- [Architecture Patterns with Python (cosmic python) — gratuito online](https://www.cosmicpython.com/) — Architecture, DDD, TDD and event-driven design in Python, with the full book on the site. 🇺🇸
- [Effective Python, 3rd Edition (Brett Slatkin)](https://effectivepython.com/) — 2024 edition with 125 specific ways to write better Python. 🆕 💰 🇺🇸
- [Python Crash Course, 3rd Edition (No Starch Press)](https://nostarch.com/python-crash-course-3rd-edition) — The world's best-selling introductory Python book. 💰 🇺🇸
- [The Quick Python Book, 3rd Edition (Naomi Ceder)](https://www.manning.com/books/the-quick-python-book-third-edition) — Concise introduction for programmers, by a former PSF chair. 💰 🇺🇸
- [Learn Python the Hard Way (Zed Shaw)](https://learnpythonthehardway.org/) — Method based on typing and running exercises until they stick. 💰 🇺🇸
- [PythonBooks (wiki oficial)](https://wiki.python.org/moin/PythonBooks) — Official list of Python books by level and language. 🇺🇸

## 🎥 YouTube channels
### In Portuguese
- [Curso em Vídeo](https://www.youtube.com/@CursoemVideo) — Gustavo Guanabara's channel, home of Brazil's most popular Python course.
- [Eduardo Mendes (Dunossauro)](https://www.youtube.com/@Dunossauro) — Live de Python every week since 2017, FastAPI do Zero and mini-series about the language.
- [Otávio Miranda](https://www.youtube.com/@OtavioMiranda) — Complete free courses: type hints, regex, concurrency, Django, LangChain.
- [Hashtag Programação](https://www.youtube.com/@HashtagProgramacao) — Python for automation, data and everyday applications, in simple language.
- [Programação Dinâmica](https://www.youtube.com/@pgdinamica) — Kizzy Terra and Hallison Paz: Python, data science and AI with rigor and didactics.
- [Código Fonte TV](https://www.youtube.com/@codigofontetv) — Gabriel and Vanessa explain technologies (Python included) in a light, visual way.
- [Didática Tech](https://www.youtube.com/@DidaticaTech) — Python, machine learning and data with complete free lessons.
- [Asimov Academy](https://www.youtube.com/@AsimovAcademy) — Channel of the Python and AI school, with free tutorials on agents, data and automation.
- [Let's Data](https://www.youtube.com/@LetsDataAI) — Data science and AI in Portuguese, with Python as the central tool.
- [Jornada de Dados (Luciano Vasconcelos)](https://www.youtube.com/@JornadadeDados) — Data engineering with Python: pipelines, APIs, tests and good practices.
- [Dev Aprender (Jhonatan de Souza)](https://www.youtube.com/@DevAprender) — Python and web development explained practically for beginners.
- [Programador Lhama](https://www.youtube.com/@ProgramadorLhama) — Python, Django and career, with complete projects.
- [CFBCursos](https://www.youtube.com/@cfbcursos) — Free courses organized by playlist, including Python.
- [Bóson Treinamentos](https://www.youtube.com/@bosontreinamentos) — Veteran channel with complete courses on Python, databases and networking.
- [Python Brasil (oficial)](https://www.youtube.com/@pythonbrasiloficial) — Talks and tutorials recorded at the Python Brasil conferences.
- [Filipe Deschamps](https://www.youtube.com/@filipedeschamps) — Programming and career in general, with didactic videos that frequently use Python.

### In English
- [Corey Schafer](https://www.youtube.com/@coreyms) — The world's most recommended Python channel: clear, timeless tutorials. 🇺🇸
- [mCoding](https://www.youtube.com/@mCoding) — Intermediate and advanced Python in short, precise videos. 🇺🇸
- [ArjanCodes](https://www.youtube.com/@ArjanCodes) — Software design, architecture and clean code in Python. 🇺🇸
- [Tech With Tim](https://www.youtube.com/@TechWithTim) — Complete projects and tutorials for beginners and intermediates. 🇺🇸
- [freeCodeCamp.org](https://www.youtube.com/@freecodecamp) — Multi-hour full courses on Python and its ecosystem. 🇺🇸
- [Real Python](https://www.youtube.com/@realpython) — Videos from the Real Python site, with tutorials and interviews. 🇺🇸
- [Indently](https://www.youtube.com/@Indently) — Quick tips and tricks of modern Python. 🇺🇸
- [anthonywritescode](https://www.youtube.com/@anthonywritescode) — Anthony Sottile (pre-commit, pyupgrade) on Python tooling and internals. 🇺🇸
- [sentdex](https://www.youtube.com/@sentdex) — Python applied to data, machine learning and creative projects. 🇺🇸
- [Programming with Mosh](https://www.youtube.com/@programmingwithmosh) — Well-produced Python courses for beginners. 🇺🇸
- [PyCon US](https://www.youtube.com/@PyConUS) — Every talk from the world's largest Python conference. 🇺🇸
- [Python Software Foundation](https://www.youtube.com/@ThePSF) — Official channel of the foundation that maintains Python. 🇺🇸

## 🎙️ Podcasts
- [Hipsters Ponto Tech #122 — Python](https://www.hipsters.tech/python-hipsters-122/) — The podcast's most requested episode: why Python became a craze, data, web and community.
- [Hipsters Ponto Tech #179 — Python Fluente](https://www.hipsters.tech/python-fluente-hipsters-ponto-tech-179/) — Conversation with Luciano Ramalho about idiomatic Python and the Python Fluente book.
- [Hipsters Ponto Tech #387 — Ecossistema Python](https://www.hipsters.tech/ecossistema-python-hipsters-ponto-tech-387/) — Community, trends, frameworks and entry points, with PyLadies and AfroPython.
- [Hipsters Ponto Tech #433 — Startups: Python e LLMs na talkd.ai](https://www.hipsters.tech/startups-pyton-e-llms-na-talkd-ai-hipsters-ponto-tech-433/) — Python in production with LLMs at a Brazilian startup. 🆕
- [Hipsters Ponto Tech — tag Python](https://www.hipsters.tech/tag/python/) — Every Hipsters episode about Python.
- [Talk Python To Me](https://talkpython.fm/) — The world's most listened-to Python podcast, with weekly interviews. 🇺🇸
- [Python Bytes](https://pythonbytes.fm/) — Python ecosystem news in short weekly episodes. 🇺🇸
- [Podcast.__init__](https://www.pythonpodcast.com/) — Archive of hundreds of interviews with Python library authors. 🇺🇸

## 📰 Sites, blogs and newsletters
- [Python Brasil](https://python.org.br/) — The Brazilian community's site: materials, events, mailing lists and local groups.
- [Python Academy — blog](https://pythonacademy.com.br/blog/) — Long, practical articles in Portuguese about the language.
- [Alura — artigos sobre Python](https://www.alura.com.br/artigos/python) — Introductory guide and Portuguese articles about Python.
- [Data Science Academy — blog (Linguagem Python)](https://blog.dsacademy.com.br/categoria/linguagem-python/) — Portuguese articles about Python for data and AI.
- [Programação Dinâmica — blog](https://blog.programacaodinamica.com.br/) — Portuguese texts about Python, data and AI from the Programação Dinâmica channel.
- [TabNews](https://www.tabnews.com.br/) — Brazilian technical content community, with many Python posts.
- [Real Python](https://realpython.com/) — The web's most complete Python tutorials; many free, with optional membership. 🇺🇸
- [Python Insider (blog oficial)](https://pythoninsider.blogspot.com/) — Official release announcements for every Python version. 🇺🇸
- [PSF News](https://pyfound.blogspot.com/) — Python Software Foundation blog: surveys, grants, events. 🇺🇸
- [PyCoder's Weekly](https://pycoders.com/) — Weekly newsletter with the best articles, projects and discussions. 🇺🇸
- [Python Weekly](https://www.pythonweekly.com/) — Weekly newsletter with news, articles and jobs. 🇺🇸
- [Planet Python](https://planetpython.org/) — Aggregator of Python community blogs. 🇺🇸
- [awesome-python](https://github.com/vinta/awesome-python) — The definitive list of libraries and resources by area. 🇺🇸
- [Full Stack Python](https://www.fullstackpython.com/) — Guide to building, deploying and operating Python applications. 🇺🇸
- [Mouse Vs Python](https://blog.pythonlibrary.org/) — Mike Driscoll's blog with tutorials and book reviews. 🇺🇸
- [Python⇒Speed](https://pythonspeed.com/) — Itamar Turner-Trauring's articles on performance, memory and Docker with Python. 🇺🇸
- [Trey Hunner](https://treyhunner.com/) — Articles on idiomatic Python for people leaving the basics. 🇺🇸
- [Ned Batchelder](https://nedbatchelder.com/blog) — Blog of the coverage.py maintainer, with classic texts about the language. 🇺🇸
- [PyCharm Blog (JetBrains)](https://blog.jetbrains.com/pycharm/) — Ecosystem news, surveys and tutorials. 🇺🇸
- [dev.to — tag Python](https://dev.to/t/python) — DEV community articles about Python. 🇺🇸
- [Python Tutorial (pythontutorial.net)](https://www.pythontutorial.net/) — Text tutorials, from basics to Tkinter, SQLite and concurrency. 🇺🇸
- [Programiz — Python](https://www.programiz.com/python-programming) — Text tutorial with examples and an online compiler. 🇺🇸
- [W3Schools — Python](https://www.w3schools.com/python/) — Quick reference with runnable examples. 🇺🇸
- [GeeksforGeeks — Python](https://www.geeksforgeeks.org/python/python-programming-language-tutorial/) — Tutorials and exercises, good for interview preparation. 🇺🇸

## 🛠️ Tools
### Install, run and manage environments
- [Python.org — Downloads](https://www.python.org/downloads/) — Official installer for Windows and macOS (on Linux, use the package manager). 🇺🇸
- [pip](https://pip.pypa.io/en/stable/) — Python's standard package installer. 🇺🇸
- [PyPI](https://pypi.org/) — The official Python package repository. 🇺🇸
- [uv](https://docs.astral.sh/uv/) — Extremely fast Rust-based package and project manager: replaces pip, venv, pyenv and Poetry. 🆕 🇺🇸
- [Poetry](https://python-poetry.org/) — Dependency management and packaging with `pyproject.toml`. 🇺🇸
- [pyenv](https://github.com/pyenv/pyenv) — Install and switch between multiple Python versions. 🇺🇸
- [pipx](https://pipx.pypa.io/stable/) — Install Python command-line tools in isolated environments. 🇺🇸
- [Google Colab](https://colab.research.google.com/) — Free cloud Jupyter notebooks with GPU — nothing to install. 🇺🇸
- [Project Jupyter](https://jupyter.org/) — Interactive notebooks, the standard environment for data and teaching. 🇺🇸
- [marimo](https://marimo.io/) — Reactive, reproducible notebook, saved as plain `.py`. 🆕 🇺🇸
- [Python Tutor](https://pythontutor.com/) — Visualize code execution step by step — great for understanding references and recursion. 🇺🇸
- [Online Python (Programiz)](https://www.programiz.com/python-programming/online-compiler/) — Run Python in the browser without installing anything. 🇺🇸
- [PyInstaller](https://pyinstaller.org/en/stable/) — Package your program as an executable for Windows, macOS and Linux. 🇺🇸
- [PythonAnywhere](https://www.pythonanywhere.com/) — Host Python scripts and web apps in the cloud, with a free plan. 🇺🇸
- [PyPy](https://pypy.org/) — Alternative implementation with a JIT, much faster on pure Python code. 🇺🇸
- [MicroPython](https://micropython.org/) — Python for microcontrollers (ESP32, Raspberry Pi Pico). 🇺🇸

### Editors, code quality and testing
- [Visual Studio Code — extensão Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) — Microsoft's official extension: IntelliSense, debugging, notebooks and tests. 🇺🇸
- [Getting Started with Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial) — Official tutorial to set up VS Code for Python. 🇺🇸
- [PyCharm](https://www.jetbrains.com/pycharm/) — The most complete Python IDE; the Community edition is free. 🇺🇸
- [Thonny](https://thonny.org/) — Minimalist IDE built for beginners, with a visual debugger. 🇺🇸
- [Mu](https://codewith.mu/) — Simple editor for beginners, with MicroPython and pygame modes. 🇺🇸
- [Spyder](https://www.spyder-ide.org/) — Scientific IDE, familiar to people coming from MATLAB/R. 🇺🇸
- [Ruff](https://docs.astral.sh/ruff/) — Rust-based linter and formatter, hundreds of times faster than Flake8 + Black. 🇺🇸
- [Black](https://black.readthedocs.io/en/stable/) — The 'uncompromising' formatter that standardized Python code style. 🇺🇸
- [mypy](https://mypy.readthedocs.io/en/stable/) — The reference static type checker. 🇺🇸
- [Pyright](https://github.com/microsoft/pyright) — Microsoft's type checker, the engine behind Pylance in VS Code. 🇺🇸
- [ty](https://docs.astral.sh/ty/) — Rust-based type checker and language server by Astral (makers of uv and Ruff), in preview. 🆕 🇺🇸
- [Pyrefly](https://pyrefly.org/) — Meta's Rust-based type checker, fast and with IDE integration. 🆕 🇺🇸
- [pytest](https://docs.pytest.org/en/stable/) — The ecosystem's de facto standard testing framework. 🇺🇸
- [unittest (PT-BR)](https://docs.python.org/pt-br/3/library/unittest.html) — The standard library's testing framework.
- [Coverage.py](https://coverage.readthedocs.io/en/latest/) — Measures how much of your code is covered by tests. 🇺🇸
- [pre-commit](https://pre-commit.com/) — Run Ruff, mypy and other checkers automatically before every commit. 🇺🇸
- [pdb — O depurador do Python (PT-BR)](https://docs.python.org/pt-br/3/library/pdb.html) — Standard library debugger: `breakpoint()` and go.
- [logging (PT-BR)](https://docs.python.org/pt-br/3/library/logging.html) — Standard library logging — stop using `print` for debugging in production.
- [regex101](https://regex101.com/) — Test regular expressions with step-by-step explanation (select the Python flavor). 🇺🇸

### Essential libraries and frameworks
- [Django](https://www.djangoproject.com/) — Full-featured web framework: ORM, admin, auth and security included. 🇺🇸
- [Documentação do Django 5.2 (PT-BR)](https://docs.djangoproject.com/pt-br/5.2/) — Official documentation of the 2025 LTS version, translated. 🆕
- [FastAPI (docs em PT)](https://fastapi.tiangolo.com/pt/) — Modern API framework based on type hints, with documentation partly in Portuguese.
- [Flask](https://flask.palletsprojects.com/en/stable/) — Minimalist web microframework, great for learning how the web works. 🇺🇸
- [Django Ninja](https://django-ninja.dev/) — Fast APIs with Django using type hints, FastAPI style. 🇺🇸
- [Litestar](https://litestar.dev/) — Modern, full-featured ASGI framework for APIs. 🇺🇸
- [Streamlit](https://streamlit.io/) — Build data apps and dashboards with Python only, no front-end. 🇺🇸
- [pandas](https://pandas.pydata.org/) — The standard library for tabular data analysis and manipulation. 🇺🇸
- [NumPy](https://numpy.org/) — Numeric arrays and linear algebra — the foundation of the whole scientific ecosystem. 🇺🇸
- [Polars](https://pola.rs/) — Rust-based DataFrames, much faster than pandas on large data; 1.0 released in 2024. 🆕 🇺🇸
- [Matplotlib](https://matplotlib.org/) — The classic plotting library. 🇺🇸
- [seaborn](https://seaborn.pydata.org/) — Beautiful statistical plots in a few lines, on top of Matplotlib. 🇺🇸
- [Plotly (Python)](https://plotly.com/python/) — Interactive charts for the web and notebooks. 🇺🇸
- [SciPy](https://scipy.org/) — Scientific algorithms: optimization, integration, statistics, signals. 🇺🇸
- [scikit-learn](https://scikit-learn.org/stable/) — Classic machine learning with a consistent API and exemplary documentation. 🇺🇸
- [PyTorch](https://pytorch.org/) — The dominant deep learning framework in research and industry. 🇺🇸
- [Keras](https://keras.io/) — High-level deep learning API on top of JAX, TensorFlow or PyTorch. 🇺🇸
- [Requests](https://requests.readthedocs.io/en/latest/) — HTTP for humans: the simplest way to consume APIs. 🇺🇸
- [HTTPX](https://www.python-httpx.org/) — Modern HTTP client with `async` and HTTP/2 support. 🇺🇸
- [Pydantic](https://docs.pydantic.dev/latest/) — Data validation with type hints; foundation of FastAPI and many AI SDKs. 🇺🇸
- [SQLAlchemy](https://www.sqlalchemy.org/) — Python's most used ORM and SQL toolkit. 🇺🇸
- [Typer](https://typer.tiangolo.com/) — Build CLIs with type hints, by the creator of FastAPI. 🇺🇸
- [Rich](https://rich.readthedocs.io/en/stable/) — Formatted text, tables, progress bars and pretty tracebacks in the terminal. 🇺🇸
- [Textual](https://textual.textualize.io/) — Terminal (TUI) applications with widgets and CSS. 🇺🇸
- [Playwright for Python](https://playwright.dev/python/) — Modern, reliable browser automation, by Microsoft. 🇺🇸
- [Selenium](https://www.selenium.dev/documentation/) — Classic browser automation, with plenty of Portuguese tutorials. 🇺🇸
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) — Extract data from HTML simply (web scraping). 🇺🇸
- [Scrapy](https://www.scrapy.org/) — Complete framework for web scraping at scale. 🇺🇸
- [Celery](https://docs.celeryq.dev/en/stable/) — Asynchronous task queues and distributed scheduling. 🇺🇸
- [tkinter (PT-BR)](https://docs.python.org/pt-br/3/library/tkinter.html) — Graphical interfaces with the library that ships with Python.
- [Qt for Python (PySide6)](https://doc.qt.io/qtforpython-6/) — Professional, cross-platform graphical interfaces with Qt. 🇺🇸
- [Kivy](https://kivy.org/) — Cross-platform apps (including Android/iOS) in Python. 🇺🇸
- [spaCy](https://spacy.io/) — Industrial-strength natural language processing, with a Portuguese model. 🇺🇸
- [NLTK](https://www.nltk.org/) — Classic NLP toolkit for teaching and research. 🇺🇸

## 🧪 Hands-on projects and challenges
- [Exercícios de Python 3 (Curso em Vídeo)](https://www.youtube.com/playlist?list=PLHz_AreHm4dm6wYOIW20Nyg12TAjmMGT-) — 100+ exercises solved on video by Guanabara — do them before watching the solution.
- [30 dias de Python (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3J6hIY4PZ13BWOqoJ9zDUq3) — One challenge per day, in Portuguese, to build the programming habit.
- [Construindo um pacote Python do zero (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3LiHhK1upnjpHiFzcJ472QS) — Create, test, document and publish your own library on PyPI.
- [CLIs — Interfaces de linha de comando com Python (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3IvU8rfQdwfiAwf180Vr_o-) — Terminal tools with argparse, Typer and Rich.
- [Web Scraping com Python (Eduardo Mendes)](https://www.youtube.com/playlist?list=PLOQgLBuj2-3K2IUFOEF0YG6T9fEJwqhJo) — Collect data from real sites with Requests, Beautiful Soup and Selenium.
- [Estruturas de dados e algoritmos (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm0-RUXh2_sw-nnQUxndFZqU) — Stacks, queues, linked lists, trees and classic algorithms in Python.
- [Padrões de Projeto — Design Patterns GoF (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm0VY5YrMrafWaQY2EnJ3j8H) — The 23 GoF patterns implemented in Python, one per video.
- [Codewars — Python](https://www.codewars.com/?language=python) — Katas by difficulty level, with community solutions to compare. 🇺🇸
- [HackerRank — Python](https://www.hackerrank.com/domains/python) — Track of Python-specific challenges, from basics to regex and XML. 🇺🇸
- [Advent of Code](https://adventofcode.com/) — 25 puzzles every December, solved by half the community in Python. 🇺🇸
- [Project Euler](https://projecteuler.net/) — Math problems that require efficient programming. 🇺🇸
- [CheckiO](https://checkio.org/) — Programming game where every challenge is solved in Python. 🇺🇸
- [Practice Python](https://www.practicepython.org/) — Short exercises for beginners, with solutions. 🇺🇸
- [Python Exercises (w3resource)](https://www.w3resource.com/python-exercises/) — Hundreds of exercises by topic (strings, lists, pandas, NumPy). 🇺🇸
- [Edabit — Python](https://edabit.com/challenges/python3) — 2,500+ short challenges, from very easy to expert. 🇺🇸
- [CodinGame](https://www.codingame.com/start/) — Learn by solving programming puzzles and games, with Python among the languages. 🇺🇸
- [Kaggle Competitions](https://www.kaggle.com/competitions) — Data and ML competitions with public notebooks to learn from. 🇺🇸
- [The Big Book of Small Python Projects — gratuito online](https://inventwithpython.com/bigbookpython/) — 81 small, complete projects (games, simulations, utilities) to type and modify. 🇺🇸
- [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) — Every classic algorithm implemented in Python, for study. 🇺🇸
- [learn-python (trekhleb)](https://github.com/trekhleb/learn-python) — Playground and cheatsheet: scripts organized by topic, with tests. 🇺🇸
- [geekcomputers/Python](https://github.com/geekcomputers/Python) — Hundreds of community example scripts for inspiration. 🇺🇸
- [Build your own X](https://github.com/codecrafters-io/build-your-own-x) — Recreate technologies (database, shell, interpreter) — many tutorials in Python. 🇺🇸
- [project-based-learning — Python](https://github.com/practical-tutorials/project-based-learning) — List of project-based tutorials, with a large Python section. 🇺🇸
- [app-ideas](https://github.com/florinpop17/app-ideas) — Application ideas by level to practice in any language. 🇺🇸
- [Pybites](https://pybit.es/) — Community and exercise platform for becoming a Python developer. 🇺🇸

## 🤖 AI in practice
Python is the language modern AI is written in — PyTorch, Transformers, LangChain and the SDKs of every major model are Python-first. That has two consequences for learners: AI assistants are **very good at Python** (it is the language with the most training code), and learning Python is the shortest path to *building* with AI, not just using it.

**For learning**
- Paste a whole traceback (e.g. `TypeError: can only concatenate str (not "int") to str`) together with the code snippet and ask: *"explain the cause, show the fix and tell me how to avoid it in the future"*.
- Ask it to rewrite one of your snippets in a **Pythonic** way (list comprehension, `with`, `enumerate`, `pathlib`, f-strings) and to justify each change.
- Ask for **exercises with pytest tests** on the topic you are studying: you write the solution, the test tells you whether it passed.
- Ask it to add type hints to one of your functions, then run `mypy` or `ty` to see whether the AI got it right.
- Use the REPL or a notebook to **check every claim** the AI makes: `help(obj)`, `dir(obj)` and `type(x)` do not lie.

**For work**
- Use [GitHub Copilot](https://github.com/features/copilot), [Cursor](https://cursor.com/) or [Claude Code](https://code.claude.com/docs/en/overview) to: write pytest tests, generate docstrings, migrate scripts to `pathlib`/`dataclasses`/`asyncio`, convert pandas to Polars, create automations and explain legacy code.
- After **every** accepted suggestion, run `ruff check`, `pytest` and the type checker. If the code only works with `# type: ignore`, `except: pass` or `eval`, the suggestion is probably wrong.
- In notebooks, [Jupyter AI](https://jupyter-ai.readthedocs.io/en/latest/) and [Colab](https://colab.research.google.com/) already ship an integrated assistant to explain errors and generate cells.

**Limits and good practices**
- AI **makes up library functions and parameters** (especially for pandas, LangChain and fast-moving SDKs). Confirm in the official docs and in the installed version (`pip show package`).
- AI **makes up package names**: never `pip install` a suggested package without checking it on [PyPI](https://pypi.org/) — fake packages with "hallucinated" names are a real attack vector.
- Be suspicious of `eval()`/`exec()`, `pickle` from external sources, SQL built with f-strings and passwords in code: AI repeats these insecure patterns often.
- Do not paste proprietary code, secrets or customer data into tools without your company's policy.
- Understand what you accept: in interviews and in production, the code is yours.

**Python is the language of AI.** Learning Python opens the door to building applications with LLMs and machine learning models — the main tools and courses:
- [Claude Code](https://code.claude.com/docs/en/overview) — Terminal coding agent: writes pytest tests, refactors and explains tracebacks. 🆕 🇺🇸
- [GitHub Copilot](https://github.com/features/copilot) — AI autocomplete and chat in the editor; free for students and with a free plan. 🇺🇸
- [Cursor](https://cursor.com/) — VS Code-based editor with AI built into the workflow. 🇺🇸
- [Jupyter AI](https://jupyter-ai.readthedocs.io/en/latest/) — AI assistant inside JupyterLab, with the `%%ai` magic command. 🇺🇸
- [Anthropic Python SDK](https://github.com/anthropics/anthropic-sdk-python) — Official SDK for using Claude models in Python. 🇺🇸
- [OpenAI Python SDK](https://github.com/openai/openai-python) — OpenAI's official SDK, typed and with `async` support. 🇺🇸
- [Google Gen AI Python SDK](https://github.com/googleapis/python-genai) — Official SDK for the Gemini models. 🆕 🇺🇸
- [Ollama Python](https://github.com/ollama/ollama-python) — Run open models locally and use them from Python. 🆕 🇺🇸
- [LangChain (Python)](https://docs.langchain.com/oss/python/langchain/overview) — Framework for LLM applications: chains, RAG, tools. 🇺🇸
- [LangGraph](https://docs.langchain.com/oss/python/langgraph/overview) — Stateful agents and controlled flows, on top of LangChain. 🆕 🇺🇸
- [LlamaIndex](https://developers.llamaindex.ai/python/framework/) — Framework for connecting LLMs to your data (RAG). 🇺🇸
- [Pydantic AI](https://pydantic.dev/docs/ai/overview/) — Agent framework with type-validated outputs, by the Pydantic team. 🆕 🇺🇸
- [CrewAI](https://docs.crewai.com/) — Orchestration of multiple AI agents in Python. 🆕 🇺🇸
- [smolagents (Hugging Face)](https://huggingface.co/docs/smolagents/index) — Minimalist agents that write and run Python code. 🆕 🇺🇸
- [Model Context Protocol — SDK Python](https://github.com/modelcontextprotocol/python-sdk) — Build MCP servers in Python to give tools to Claude, Cursor and other agents. 🆕 🇺🇸
- [browser-use](https://github.com/browser-use/browser-use) — Web-browsing agents, in Python on top of Playwright. 🆕 🇺🇸
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index) — Thousands of pre-trained models (text, image, audio) in a few lines. 🇺🇸
- [Gradio](https://gradio.app/) — Build web interfaces for ML models in minutes. 🇺🇸
- [LangChain e LangGraph com Python — curso completo (Otávio Miranda)](https://www.youtube.com/playlist?list=PLbIBj8vQhvm09IqqLYIwLF5dGrcbJzFZc) — Free Portuguese course on building LLM applications and agents. 🆕
- [Anthropic Academy](https://anthropic.skilljar.com/) — Anthropic's free courses on the API, prompt engineering and agents, with Python examples. 🆕 🇺🇸
- [Anthropic Courses (GitHub)](https://github.com/anthropics/courses) — Jupyter notebooks of Anthropic's courses: API fundamentals, prompting, tool use. 🆕 🇺🇸
- [Hugging Face Learn](https://huggingface.co/learn) — Free courses on LLMs, agents, deep RL and vision, all in Python. 🇺🇸
- [Generative AI for Beginners (Microsoft)](https://github.com/microsoft/generative-ai-for-beginners) — 21 lessons with Python code to build generative AI apps. 🆕 🇺🇸
- [ML for Beginners (Microsoft)](https://github.com/microsoft/ML-For-Beginners) — 12 weeks of classic machine learning with scikit-learn. 🇺🇸
- [Practical Deep Learning for Coders (fast.ai)](https://course.fast.ai/) — Free course that teaches deep learning top-down, in Python and PyTorch. 🇺🇸
- [DeepLearning.AI — cursos](https://www.deeplearning.ai/courses) — Free short courses by Andrew Ng and partners on LLMs, agents and RAG. 🇺🇸
- [Machine Learning Crash Course (Google)](https://developers.google.com/machine-learning/crash-course) — Google's hands-on intro to ML, with Python exercises. 🇺🇸
- [Kaggle Learn — Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning) — First ML model in a few hours, with scikit-learn. 🇺🇸
- [PyTorch Tutorials](https://docs.pytorch.org/tutorials/) — Official PyTorch tutorials, from tensors to models in production. 🇺🇸
- [scikit-learn — User Guide](https://scikit-learn.org/stable/user_guide.html) — The official guide, which is also a great classic ML course. 🇺🇸
- [Neural Networks: Zero to Hero (Andrej Karpathy)](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) — Build neural networks and a GPT from scratch in Python, with Tesla's former AI director. 🇺🇸

## 📜 Certifications
There is no official Python Software Foundation certification. The most recognized ones are from the **OpenEDG Python Institute** (PCEP, PCAP, PCPP), accepted internationally. In Brazil, employers tend to value **published projects and hands-on skill** more than certificates; the course-completion certificates below help on a résumé but do not replace a portfolio.
- [PCEP — Certified Entry-Level Python Programmer (Python Institute)](https://pythoninstitute.org/pcep) — Internationally recognized entry-level certification for language fundamentals. 💰 🇺🇸
- [PCAP — Certified Associate in Python Programming (Python Institute)](https://pythoninstitute.org/pcap) — Associate level: OOP, modules, exceptions, strings and the standard library. 💰 🇺🇸
- [PCPP1 — Certified Professional in Python Programming 1 (Python Institute)](https://pythoninstitute.org/pcpp1) — Professional level: advanced OOP, GUI, networking, good practices. 💰 🇺🇸
- [Python Institute — trilhas de certificação](https://pythoninstitute.org/certification-tracks) — Overview of every OpenEDG Python Institute certification and exam. 🇺🇸
- [Google IT Automation with Python (Coursera)](https://www.coursera.org/professional-certificates/google-it-automation) — Google professional certificate: Python, Git, automation and troubleshooting. 💰 🇺🇸
- [Python for Data Science, AI & Development (IBM no Coursera)](https://www.coursera.org/learn/python-for-applied-data-science-ai) — IBM course with certificate, part of several data professional certificates. 💰 🇺🇸
- [HackerRank — Python (Basic) Skills Certification](https://www.hackerrank.com/skills-verification/python_basic) — Free 90-minute test that issues a certificate for your profile. 🇺🇸
- [Scientific Computing with Python — certificação freeCodeCamp](https://www.freecodecamp.org/learn/scientific-computing-with-python) — Free certification after completing the curriculum's five projects. 🇺🇸
- [Curso em Vídeo — certificado gratuito de Python](https://www.cursoemvideo.com/curso/python-3-mundo-1/) — Free certificate upon completing each Mundo of the course on the site.
- [Data Science Academy — certificado gratuito](https://www.datascienceacademy.com.br/course/fundamentos-de-linguagem-python-do-basico-a-aplicacoes-de-ia) — Completion certificate for DSA's free Python course. 🆕
- [Formação Python (Alura) — com certificado](https://www.alura.com.br/formacao-linguagem-python) — Alura certificate, recognized by Brazilian companies. 💰

## 💼 Career and jobs
Python is a requirement in most data science and data engineering, AI/machine learning, automation/DevOps and back-end (Django, FastAPI) job posts in Brazil, and it is the most common entry language in internship and trainee programs. Tip: in the GitHub job repositories below, search open issues for "Python".
- [Python Developers Survey 2024 (PSF + JetBrains)](https://lp.jetbrains.com/python-developers-survey-2024/) — Official survey of 30k developers: uses, tools, versions and trends. 🆕 🇺🇸
- [The State of Python 2024 (JetBrains)](https://blog.jetbrains.com/pycharm/2024/12/the-state-of-python/) — Analysis of the survey data: where Python is growing and what the market uses. 🆕 🇺🇸
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — Python remains among the most used and wanted languages. 🆕 🇺🇸
- [TIOBE Index](https://www.tiobe.com/tiobe-index/) — Monthly popularity index that Python has led since 2021. 🇺🇸
- [Python Success Stories (python.org)](https://www.python.org/success-stories/) — Real cases of companies and projects using Python. 🇺🇸
- [Python Job Board (python.org)](https://www.python.org/jobs/) — The Python community's official job board. 🇺🇸
- [Programathor — vagas Python](https://programathor.com.br/jobs-python) — Tech jobs in Brazil filtered by Python.
- [GeekHunter](https://www.geekhunter.com/pt) — Brazilian platform where companies make offers to developers.
- [Coodesh](https://coodesh.com/) — Tech jobs in Brazil with standardized hiring processes.
- [Remotar](https://remotar.com.br/) — 100% remote jobs for Brazilians.
- [backend-br/vagas](https://github.com/backend-br/vagas) — Back-end jobs (many with Python/Django/FastAPI) posted as GitHub issues.
- [datascience-br/vagas](https://github.com/datascience-br/vagas) — Data science and engineering jobs on GitHub — Python is requirement number one.
- [DevOps-Brasil/Vagas](https://github.com/DevOps-Brasil/Vagas) — DevOps/SRE jobs, where Python is the default automation language.
- [RemoteOK — vagas Python](https://remoteok.com/remote-python-jobs) — International remote Python jobs. 🇺🇸
- [Working Nomads — vagas Python](https://www.workingnomads.com/remote-python-jobs) — Another remote job aggregator with a Python filter. 🇺🇸
- [Tech Interview Handbook](https://www.techinterviewhandbook.org/) — Complete preparation for technical interviews. 🇺🇸

## 👥 Communities
- [Python Brasil — comunidades locais](https://python.org.br/comunidades-locais/) — List of GruPys, PyLadies and regional groups across the country.
- [Python Brasil no Telegram (grupo @pythonbr)](https://t.me/pythonbr) — The Brazilian community's discussion group, with thousands of members.
- [Python Brasil no Telegram (canal @pythonbrasil)](https://t.me/pythonbrasil) — Announcements, events and content channel of the community.
- [Lista python-brasil (Google Groups)](https://groups.google.com/g/python-brasil) — The community's historic mailing list, active since the 2000s.
- [PyLadies Brasil](https://brasil.pyladies.com/) — Community of women in Python programming, with chapters in dozens of cities.
- [Python Brasil 2025 (conferência)](https://2025.pythonbrasil.org.br/) — The community's national conference: tutorials, talks and sprints (São Paulo, October 2025). 🆕
- [Python Nordeste 2026](https://2026.pythonnordeste.org/) — The Northeast's regional conference, one of the country's most traditional. 🆕
- [Python Brasil no GitHub](https://github.com/pythonbrasil) — Organization with the community's site, events and projects.
- [Python Discord](https://www.pythondiscord.com/) — The largest Python server on Discord, with help channels and events. 🇺🇸
- [Discussions on Python.org](https://discuss.python.org/) — Official forum: help, ideas and language development discussions. 🇺🇸
- [r/Python](https://www.reddit.com/r/Python/) — Main subreddit, with news and projects. 🇺🇸
- [r/learnpython](https://www.reddit.com/r/learnpython/) — Subreddit for learners' questions. 🇺🇸
- [Python Software Foundation](https://www.python.org/psf-landing/) — The foundation that maintains the language; join for free. 🇺🇸
- [PyCon US 2026](https://us.pycon.org/2026/) — The world's largest Python conference; talks go to YouTube. 🆕 🇺🇸
- [PyLadies (global)](https://pyladies.com/locations/) — Every PyLadies chapter worldwide. 🇺🇸
- [TabNews](https://www.tabnews.com.br/) — Brazilian technical content community created by Filipe Deschamps.
- [He4rt Developers](https://heartdevs.com/) — Brazilian open-source community with an active Discord and multi-language projects.
- [Desenvolvedores Brasil (Discord)](https://discord.com/invite/t3vYGUuK6P) — Brazilian community with tips, courses, mentoring and a Python channel.
- [DEV Community — devs brasileiros](https://dev.to/t/braziliandevs) — Tag with Portuguese articles from the Brazilian community.
- [Lista de grupos de tecnologia no Telegram (TI-Brasil)](https://github.com/TI-Brasil/lista-telegram-brasil) — Directory of Brazilian Telegram groups, including several Python ones.

## 🚨 How to contribute
Found a broken link, a new course or a tool that deserves to be here? Open an issue using the repository templates or send a pull request. Criteria: working link, legal content that is free or clearly marked as paid, with a one-line description. Details in [CONTRIBUTING.md](../CONTRIBUTING.md).

## 📄 License
This project is under the [MIT](../LICENSE) license. Made with 💙 by [Arthur Coutinho (@arthurspk)](https://github.com/arthurspk) and the [Guia Dev Brasil](https://github.com/arthurspk/guiadevbrasil) community.

## 💙 Support the project
Star this repository and the [main guide](https://github.com/arthurspk/guiadevbrasil), share it with someone who is starting out and follow the project on social media:

[<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">](https://github.com/arthurspk)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/arthurspk/)
[<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)">](https://x.com/manotoquinho)
[<img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">](https://www.instagram.com/arthurspk/)
[<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">](https://www.facebook.com/seixasqlc/)
