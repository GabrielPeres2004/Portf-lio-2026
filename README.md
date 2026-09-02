# Portfólio — Gabriel Peres

Site de portfólio pessoal, construído do zero com HTML, CSS e JavaScript puros (sem framework, sem build step). Apresenta quem eu sou, os projetos que desenvolvi, minha formação e cursos, e formas de contato.

🔗 **Site no ar:** [gabrielperes2004.github.io](https://gabrielperes2004.github.io)

## Sobre

Este é o portfólio que uso pra me apresentar em processos seletivos de estágio e vaga júnior. Reúne meus projetos principais, um resumo da minha formação em Análise e Desenvolvimento de Sistemas, os cursos que fiz e um jeito rápido de entrar em contato (e-mail, WhatsApp, LinkedIn, GitHub).

## Funcionalidades

- **Tema claro/escuro** com alternância por botão, salvo no `localStorage` do navegador
- **Menu responsivo**, com versão mobile em overlay
- **Animações de entrada ao rolar a página**, usando `IntersectionObserver` (sem bibliotecas externas)
- **Scroll suave** para navegação por âncoras
- **Download do currículo em PDF** direto pelo menu
- Seções: Sobre, Projetos, Formação, Cursos & Certificações, Contato

## Stack

- HTML5 semântico
- CSS3 (custom properties para o sistema de tema, Grid e Flexbox para o layout)
- JavaScript vanilla (sem dependências, sem bundler)
- Fonte: [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) + [Outfit](https://fonts.google.com/specimen/Outfit), via Google Fonts

## Estrutura

```
├── index.html      → estrutura e conteúdo do site
├── style.css        → estilos, tema (claro/escuro) e responsividade
├── script.js         → tema, menu mobile, scroll suave e animações de entrada
└── assets/
    ├── Gabriel.jpeg               → foto de perfil
    └── Curriculo_Gabriel_Peres.pdf → currículo para download
```

## Como rodar localmente

Não precisa de build nem de instalar nada — é só abrir o `index.html` no navegador, ou, se preferir um servidor local (recomendado, pra evitar bloqueios de CORS em alguns navegadores):

```bash
npx serve .
```

ou, com Python:

```bash
python3 -m http.server 8000
```

## Projetos em destaque

- **[Food Explorer](https://github.com/GabrielPeres2004/Web-Food-Explorer)** — cardápio digital full stack (React + Node.js/Express + MySQL + JWT)
- **[Loja Virtual API](https://github.com/GabrielPeres2004/Loja-Virtual)** — API REST de e-commerce (Java + Spring Boot + Spring Security + JWT)

## Contato

- E-mail: gperes020@gmail.com
- LinkedIn: [linkedin.com/in/gabriel-peres](https://www.linkedin.com/in/gabriel-peres-70a3042b1/)
- GitHub: [github.com/GabrielPeres2004](https://github.com/GabrielPeres2004)
