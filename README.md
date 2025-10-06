# ALU Alarm Simulator 🚨

<div align="center">

**Demonstração Interativa de ULA (Unidade Lógica e Aritmética)**

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-3.0.2-000000?style=flat&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

[Demonstração](#demonstração) • [Instalação](#instalação) • [Uso](#uso) • [Tecnologias](#tecnologias)

</div>

---

## 📋 Sobre o Projeto

Aplicação web educacional desenvolvida em Python + Flask para demonstrar o funcionamento de uma **ULA (Unidade Lógica e Aritmética)** através de um sistema de alarme interativo.

O projeto foi criado para ministrar aulas de programação web e arquitetura de computadores nas turmas de **Análise e Desenvolvimento de Sistemas (ADS)** da Faculdade Anhanguera de Sobral em abril/2024.

### Funcionalidades

- ✅ Simulação de portas lógicas (OR, AND, NAND, NOT, NOR)
- ✅ Interface web interativa com validação de formulários
- ✅ Demonstração visual do resultado com animação de alarme
- ✅ Sistema de entrada binária (0 ou 1)
- ✅ Tratamento de erros personalizado

## 🖼️ Demonstração

### Turma do 1º Semestre - ADS Anhanguera Sobral

<div align="center">
  <img src="images/ads anhanguera turma 1 semestre.jpeg" alt="Turma 1º semestre ADS" width="700"/>

[📸 Ver no LinkedIn](https://www.linkedin.com/posts/antonio-albuquerque-loiola_turma-do-1%C2%BA-semestre-do-curso-de-ads-an%C3%A1lise-activity-7189652650450173954-MjY5?utm_source=share&utm_medium=member_desktop)

</div>

### Turma do 2º Semestre - ADS Anhanguera Sobral

<div align="center">
  <img src="images/ads anhanguera turma 2 e 3 semestre.jpeg" alt="Turma 2º/3º semestre ADS" width="700"/>
  <img src="images/ads anhanguera turma 2 e 3 semestre2.jpeg" alt="Turma 2º/3º semestre ADS - Foto 2" width="700"/>

[📸 Ver no LinkedIn](https://www.linkedin.com/posts/antonio-albuquerque-loiola_turma-do-2%C2%BA-e-3%C2%BA-semestre-do-curso-de-ads-activity-7189651583679295488-lV2P?utm_source=share&utm_medium=member_desktop)

</div>

## 🚀 Instalação

### Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

### Passo a Passo

1. **Clone o repositório**

```bash
git clone https://github.com/Romiro13/aula-anhanguera-ula-alarme.git
cd aula-anhanguera-ula-alarme
```

2. **Crie o ambiente virtual**

```bash
python -m venv .venv
```

3. **Ative o ambiente virtual**

**Linux/macOS:**

```bash
source .venv/bin/activate
```

**Windows (PowerShell):**

```powershell
.venv\Scripts\activate
```

**Windows (CMD):**

```cmd
.venv\Scripts\activate.bat
```

4. **Instale as dependências**

```bash
pip install -r requirements.txt
```

## 💻 Uso

### Método 1: Usando Flask CLI (Recomendado)

**Linux/macOS:**

```bash
export FLASK_ENV="development"
export FLASK_APP=main.py
export FLASK_DEBUG=True
flask run
```

**Windows (PowerShell):**

```powershell
$Env:FLASK_ENV="development"
$Env:FLASK_APP="main.py"
$Env:FLASK_DEBUG="True"
flask run
```

### Método 2: Execução Direta

```bash
python main.py
```

A aplicação estará disponível em: **http://127.0.0.1:5000/**

## 🛠️ Tecnologias

- **[Python 3.x](https://www.python.org/)** - Linguagem de programação
- **[Flask 3.0.2](https://flask.palletsprojects.com/)** - Framework web
- **[Flask-WTF 1.2.1](https://flask-wtf.readthedocs.io/)** - Formulários e validação
- **[WTForms 3.1.2](https://wtforms.readthedocs.io/)** - Validação de dados
- **[Bootstrap 5](https://getbootstrap.com/)** - Framework CSS
- **[Jinja2 3.1.3](https://jinja.palletsprojects.com/)** - Template engine

## 📁 Estrutura do Projeto

```
aula-anhanguera-ula-alarme/
├── main.py                 # Aplicação Flask principal
├── requirements.txt        # Dependências do projeto
├── templates/              # Templates HTML
│   ├── base.html           # Template base
│   ├── index.html          # Página principal
│   ├── navbar.html         # Barra de navegação
│   └── error_handler.html  # Página de erros
├── static/                 # Arquivos estáticos
│   ├── css.css             # Estilos customizados
│   ├── js.js               # Scripts JavaScript
│   └── images/             # Imagens
└── images/                 # Fotos das turmas
```

## 🎓 Contexto Acadêmico

Este projeto foi desenvolvido como material didático para demonstrar:

- Conceitos de **Arquitetura de Computadores** (ULA)
- **Desenvolvimento Web** com Python e Flask
- **Lógica de Programação** através de portas lógicas
- **Validação de formulários** e tratamento de dados
- **Boas práticas** de desenvolvimento web

## 👨‍🏫 Autor

**Antonio Albuquerque Loiola**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/antonio-albuquerque-loiola)

## 📝 Licença

Este projeto é de código aberto e está disponível para fins educacionais.

---

<div align="center">
  Desenvolvido com ❤️ para os alunos de ADS da Anhanguera Sobral
</div>
