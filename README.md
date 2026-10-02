<h1 align="center">Pedro Henrique 👋</h1>

<h3 align="center">
  Data Engineering • Python • SQL • AI
</h3>

<p align="center">
  Desenvolvedor focado em Engenharia de Dados, construção de pipelines, processamento de dados e automação.
  <br>
  Formado em Análise e Desenvolvimento de Sistemas e atualmente cursando Ciência da Computação.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/pedro-ramoss/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

## 👨‍💻 Sobre mim

- 🎓 Graduado em Análise e Desenvolvimento de Sistemas
- 🎓 Cursando Ciência da Computação
- 📊 Foco atual em Engenharia de Dados
- 🤖 Interesse em Inteligência Artificial e Machine Learning
- 🐧 Utilizo Linux como ambiente principal de desenvolvimento
- 🏗️ Desenvolvendo projetos de Data Engineering de ponta a ponta
- 📚 Estudando arquitetura de dados, pipelines, bancos de dados, testes e automação

---

## 🚀 Projeto em destaque

### 🎬 Movie Data Warehouse

Pipeline de Engenharia de Dados desenvolvido para coletar, processar, armazenar e transformar dados de filmes utilizando dados da TMDB.

Arquitetura planejada:

```text
TMDB API
   ↓
Python / Requests
   ↓
Bronze Layer
Raw JSON
   ↓
PostgreSQL
   ↓
Silver Layer
dbt
   ↓
Gold Layer
Dimensional Model
   ↓
Analytics
