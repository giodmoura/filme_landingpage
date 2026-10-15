# 🎬 MovieCity - Landing Page

[![React](https://img.shields.io/badge/React-19.0-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-7.0-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![CSS3](https://img.shields.io/badge/CSS-Pure%20%2F%20Vanilla-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Uma *landing page* responsiva e moderna de um serviço de streaming fictício, desenvolvida com **React 19** e **Vite 7**.

Este projeto foi construído como um exercício prático focado em **componentização**, **estilização com CSS puro** (sem bibliotecas de UI de terceiros) e **design responsivo avançado** adaptável a múltiplos tamanhos de tela.

---

## 📌 Sumário

- [Sobre o Projeto](#-sobre-o-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Pré-requisitos](#-pré-requisitos)
- [Como Executar o Projeto](#-como-executar-o-projeto)
- [Estrutura de Pastas](#-estrutura-de-pastas)
- [Arquitetura e Fluxo de Dados](#-arquitetura-e-fluxo-de-dados)
- [Responsividade](#-responsividade)
- [Scripts Disponíveis](#-scripts-disponíveis)
- [Próximos Passos](#-próximos-passos)

---

## 📖 Sobre o Projeto

A *landing page* da MovieCity é dividida em duas áreas principais:

1. **Header (Cabeçalho):**
   - Logótipo da marca (`MovieCity`).
   - Menu de navegação dinâmico (*Filmes*, *Categoria*, *Sobre*, *Contato*).
   - Botão de acesso rápido (*Login*).
   - Menu hambúrguer interativo para dispositivos móveis.

2. **Main (Conteúdo Principal):**
   - **Coluna de Chamada:** Título impactante, descrição sumária e botão de ação (*Mais*).
   - **Coluna de Conteúdo (Grid):** Exibição em grelha de 6 cartões de filmes (*Afterlife*, *Transformers*, *Mowgli*, *Shift*, *Round 6* e *Harry Potter*).

### 📱 Comportamento Responsivo
- Em ecrãs de menor dimensão, o layout adapta-se de forma inteligente: as colunas do topo empilham-se, a grelha de cartões ajusta-se dinamicamente para 2 colunas e o menu de navegação é recolhido num **menu hambúrguer interativo**.

---

## 🛠 Tecnologias Utilizadas

Nenhuma biblioteca de UI externa (como Tailwind, Bootstrap ou Styled Components) foi utilizada, com o objetivo de praticar CSS puro de raiz.

| Tecnologia | Finalidade |
| :--- | :--- |
| **React 19** | Biblioteca principal para construção da interface baseada em componentes. |
| **Vite 7** | *Bundler* de produção e servidor de desenvolvimento ultra-rápido com HMR. |
| **JavaScript (ESM)** | Linguagem base do projeto e gestão de módulos nativos. |
| **CSS3 Puro** | Estilização global, layout Flexbox/Grid e *media queries* para responsividade. |
| **ESLint** | Ferramenta para análise estática e padronização da qualidade do código. |

---

## 📋 Pré-requisitos

Antes de iniciar, certifique-se de que tem instaladas as seguintes ferramentas na sua máquina:

- **Node.js**: Versão `20.19+` ou `22.12+` *(exigido pelo Vite 7)*
- **npm** (incluído com o Node.js), **yarn** ou **pnpm**
- Editor de código (ex: [VS Code](https://code.visualstudio.com/))

Para verificar as versões instaladas, execute:
```bash
node -v
npm -v
