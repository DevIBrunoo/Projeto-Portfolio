<div align="center">
  <img src="src/img/Icon-BrunoH-V2.png" width="120" style="border-radius: 50%; margin-bottom: 20px;">
  
  <h1>🚀 Portfólio - Bruno Henrique</h1>
  
  <p>
    <i>Desenvolvedor Front-end criando interfaces modernas e funcionais</i>
  </p>

  <p>
    <a href="https://ibrunodev.netlify.app/" target="_blank">
      <img src="https://img.shields.io/badge/Visite_o_Site-00d4ff?style=for-the-badge&logo=web&logoColor=black">
    </a>
    <a href="https://linkedin.com/in/brunocarus" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
    </a>
    <a href="https://github.com/DevIBrunoo" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
    </a>
  </p>

  <p>
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/DevIBrunoo/portfolio-normal?color=00d4ff&style=flat-square">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/DevIBrunoo/portfolio-normal?color=00d4ff&style=flat-square">
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/DevIBrunoo/portfolio-normal?color=00d4ff&style=flat-square">
  </p>

  <br>
</div>

---

## 📋 Índice

1. [Sobre o Projeto](#-sobre-o-projeto)
2. [Tecnologias Utilizadas](#-tecnologias-utilizadas)
3. [Funcionalidades](#-funcionalidades)
4. [Estrutura de Pastas](#-estrutura-de-pastas)
5. [Como Rodar o Projeto](#-como-rodar-o-projeto)
6. [Páginas do Portfólio](#-páginas-do-portfólio)
7. [Terminal de Navegação](#-terminal-de-navegação)
8. [Design e UX](#-design-e-ux)
9. [Autor](#-autor)
10. [Licença](#-licença)

---

## 🎯 Sobre o Projeto

Este é o portfólio profissional de **Bruno Henrique**, um desenvolvedor front-end focado em criar interfaces modernas, responsivas e com ótima experiência para o usuário. O projeto foi desenvolvido com tecnologias puras (Vanilla) e segue as melhores práticas de mercado.

<div align="center">
  <kbd>
    <img src="https://github.com/user-attachments/assets/ea94b0ae-169b-4bde-b946-47c2ad503428" alt="Preview do Portfólio" width="700" style="border-radius: 12px;">
  </kbd>
</div>

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Descrição |
| :--- | :---: | :--- |
| **HTML5** | - | Estrutura semântica e acessível |
| **CSS3** | - | Estilização avançada, variáveis, Flexbox, Grid |
| **JavaScript (ES6+)** | - | Lógica de interação e animações |
| **DevIcon** | Latest | Ícones de tecnologias |
| **Font Awesome** | 6.x | Ícones sociais e UI |
| **Google Fonts** | - | Fonte Inter (tipografia moderna) |

---

## ✨ Funcionalidades

### 🎨 Design & UI
- **Design Responsivo**: Funciona perfeitamente em celulares, tablets e desktops
- **Tema Escuro Moderno**: Estética clean com acentos em ciano (`#00d4ff`)
- **Animações de Scroll**: Elementos surgem suavemente com `Intersection Observer`
- **Scrollbar Customizada**: Estilizada para combinar com o tema
- **Microinterações**: Efeitos de hover em botões, cards e ícones
- **Loading Overlay**: Tela de carregamento suave entre as páginas

### 🎵 Player de Música
- Player fixo no canto inferior direito
- Persiste a reprodução e o tempo ao navegar entre páginas (usando `localStorage`)
- Controles de play/pause
- Design minimalista e harmonioso com o resto do site

### 🖥️ Terminal de Navegação
- Funcionalidade única e interativa
- Botões clicáveis para facilitar o uso
- Comandos por texto
- Animações e design profissional
- Disponível em **TODAS** as páginas

---

## 📁 Estrutura de Pastas

```bash
.
├── index.html              # Página Inicial (Hero + Skills + Terminal)
├── sobre.html              # Sobre Mim
├── carreira.html            # Trajetória Profissional/Acadêmica
├── projetos.html            # Galeria de Projetos
├── contato.html             # Formulário de Contato e Redes
├── meme.html                # Página secreta do gatinho dançante 🐱
├── src/
│   ├── css/
│   │   ├── root.css         # Variáveis globais, reset e estilos base
│   │   ├── index.css        # Estilos Home, Header, Footer e Terminal
│   │   ├── sobre.css        # Estilos exclusivos da página Sobre
│   │   ├── carreira.css     # Estilos exclusivos da página Carreira
│   │   ├── projetos.css     # Estilos exclusivos da página Projetos
│   │   └── contato.css      # Estilos exclusivos da página Contato
│   ├── js/
│   │   └── main.js          # Toda a lógica do site
│   ├── img/
│   │   ├── Icon-Bruno-Original.jpg
│   │   ├── Icon-BrunoH-V2.png
│   │   ├── Icon-BrunoH.png
│   │   └── Img-Projeto-*.png  # Prints dos projetos
│   ├── audio/
│   │   └── You're Alive.m4a
│   └── docs/
│       └── (CV) - Front End Bruno.pdf
└── README.md
```

---

## 🚀 Como Rodar o Projeto

Você tem duas maneiras de visualizar o projeto:

### Opção 1: Direto no navegador (simples!)
1. Baixe ou clone este repositório
2. Navegue até a pasta do projeto
3. Dê **duplo clique** no arquivo `index.html`
4. O site abrirá no seu navegador padrão!

### Opção 2: Servidor local (melhor experiência)
Recomendado para testar o player de música e funcionalidades que requerem servidor.

**Usando Live Server (VS Code):**
1. Instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
2. Abra o projeto no VS Code
3. Clique com o botão direito em `index.html` e selecione **Open with Live Server**
4. O site abrirá em `http://127.0.0.1:5500/`

**Usando Python (se você tiver):**
```bash
# Python 3
python3 -m http.server 8000

# Depois acesse http://localhost:8000
```

---

## 📄 Páginas do Portfólio

### 1. Página Inicial (`/index.html`)
- **Hero**: Apresentação principal, nome, título e botões de CTA
- **Skills**: Grid com as tecnologias que domino, ícones da biblioteca DevIcon
- **Terminal**: Funcionalidade de navegação interativa

### 2. Sobre Mim (`/sobre.html`)
- Foto e texto de apresentação
- Cards com informações como localização e especialidade
- Terminal de navegação no final

### 3. Carreira (`/carreira.html`)
- Timeline com a trajetória profissional e acadêmica
- Datas e descrições detalhadas
- Terminal de navegação

### 4. Projetos (`/projetos.html`)
- Galeria com os meus principais projetos
- Cada card tem: imagem, tags, descrição e botões para GitHub/Preview
- Projetos incluem: Legacy RP, Linktree, SkyPage, Portfólio, Limpeza, F1 Dev

### 5. Contato (`/contato.html`)
- Cards com redes sociais (GitHub, LinkedIn, E-mail)
- Ícones bonitos e intuitivos
- Terminal para navegar de volta rapidamente

### 6. Meme (secreta! 🐱) (`/meme.html`)
- Página divertida com um gatinho dançante animado
- Animações suaves
- Acessível apenas via comando `teste` no terminal!

---

## 🖥️ Terminal de Navegação

Este é um dos diferenciais do portfólio! Um terminal estiloso e funcional que permite navegar pelo site de maneira divertida e prática.

### 📜 Comandos Disponíveis

| Comando | Ação |
| :--- | :--- |
| `inicio` | Volta para a Página Inicial |
| `sobre` | Vai para Sobre Mim |
| `carreira` | Vai para Carreira |
| `projetos` | Vai para a galeria de Projetos |
| `contato` | Vai para Contato |
| `teste` | **Abre a página secreta do gatinho dançante!** 🐱 |
| `help` | Lista todos os comandos |

### 🎨 Design do Terminal
- Estética de terminal moderno
- Gradientes e efeito de glow em ciano
- Scanlines (linhas finas) para dar charme vintage
- Cursor piscante customizado
- Botões clicáveis grandes e intuitivos
- Scroll suave automaticamente para baixo ao enviar comandos

---

## 🎨 Design e UX

### Paleta de Cores
| Cor | Hex | Uso |
| :--- | :---: | :--- |
| Ciano (Principal) | `#00d4ff` | Destaques, ícones, botões |
| Azul Escuro | `#005f73` | Acentos secundários |
| Fundo Escuro | `#0a0a0a` | Background principal |
| Card | `#141414` | Background de cards e elementos |
| Texto Principal | `#ffffff` | Títulos e textos importantes |
| Texto Secundário | `#a0a0a0` | Parágrafos e legendas |

### Tipografia
- **Fonte Principal**: Inter (Google Fonts)
- **Fonte do Terminal**: Fira Code, Courier New (mono espaçada)
- Hierarquia clara: títulos em negrito, textos em regular

---

## 👨💻 Autor

<div align="center">
  <img src="src/img/Icon-BrunoH-V2.png" width="150" style="border-radius: 50%;">
  <h3>Bruno Henrique</h3>
  <p>Desenvolvedor Front-end</p>
  
  <p>
    <a href="mailto:bruninhoodev@gmail.com">
      <img src="https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=Gmail&logoColor=white">
    </a>
    <a href="https://github.com/DevIBrunoo">
      <img src="https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github">
    </a>
    <a href="https://linkedin.com/in/brunocarus">
      <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin">
    </a>
  </p>
</div>

---

## 📝 Licença

Este projeto é **privado e de propriedade exclusiva de Bruno Henrique**. Todos os direitos reservados.

---

<div align="center">
  <p>Feito com ❤️ e ☕ por Bruno Henrique</p>
  <p>© 2026 IBrunooDev. Todos os direitos reservados.</p>
</div>
