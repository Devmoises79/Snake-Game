# 🐍 Snake Game — JavaScript Vanilla

📌 Visão Geral

Este projeto é uma implementação do clássico Snake Game, desenvolvido com JavaScript puro (Vanilla JS), HTML e CSS. O objetivo é demonstrar domínio de lógica de programação aplicada, manipulação do DOM e controle de estado em tempo real no navegador.

A aplicação é executada diretamente no browser e possui integração com localStorage para persistência de pontuação.

# ⚙️ Funcionalidades

- Controle da cobra via teclado (setas)
- Sistema de colisão com bordas e corpo
- Geração dinâmica de comida em grid
- Crescimento progressivo da cobra
- Sistema de pontuação em tempo real
- High score persistente via localStorage
- Controles também via interface mobile (ícones)

# 🧠 Conceitos Aplicados (Engenharia Front-end)

# 🎮 Lógica de Jogo (Game Development Basics)

- Loop de atualização com setInterval
- Controle de estado do jogo em tempo real
- Detecção de colisão (bordas e auto-colisão)
- Atualização incremental de coordenadas em grid

# 🧩 Manipulação de DOM

- Renderização dinâmica com innerHTML
- Atualização de elementos em tempo real
- Uso de querySelector e eventos de teclado

# 📦 Estado e Persistência

- Controle de estado via variáveis globais
- Persistência de dados com localStorage
- Gerenciamento de score e high score

# ⌨️ Event Handling
- Captura de eventos de teclado (keydown)
- Controle alternativo via eventos de clique
- Sincronização entre input físico e UI

# 🎨 CSS Grid System

- Utilização de grid para simulação de ambiente 2D
- Posicionamento dinâmico via grid-area
- Estilização de elementos do jogo em tempo real

# 🧩 Arquitetura do Projeto

O projeto segue uma estrutura simples, porém eficiente para aplicações front-end puras:

- index.html → estrutura base da aplicação
- style.css → estilização e grid do jogo
- script.js → lógica principal do jogo (engine)

# ⚠️ Pontos Técnicos Relevantes
O projeto utiliza loop contínuo com setInterval, o que é adequado para jogos simples, mas pode ser substituído futuramente por requestAnimationFrame para melhor performance.
A lógica está centralizada em um único script, o que funciona bem para projetos pequenos, mas pode ser refatorado para arquitetura modular em versões futuras.
Uso de location.reload() para reinício do jogo — solução simples, porém não escalável.

#  🚀 Tecnologias Utilizadas

- HTML5
- CSS3 (Grid Layout)
- JavaScript (ES6+)
- LocalStorage API

# 📊 Diferenciais Técnicos

- Implementação de lógica de jogo sem frameworks
- Controle de estado manual (sem engine externa)
- Persistência de dados no navegador
- Experiência interativa completa no front-end puro

# 👨‍💻 Objetivo do Projeto

Este projeto foi desenvolvido com foco em:

- Fortalecer lógica de programação aplicada
- Entender manipulação de estado em tempo real
- Praticar interação com DOM em aplicações dinâmicas
- Simular fundamentos de game loop e colisões

# 📌 Resultado

 Uma aplicação leve, funcional e com boa base técnica para evolução futura em:

- Game development com JavaScript
- Frameworks como Phaser.js
- Arquiteturas front-end mais complexas

