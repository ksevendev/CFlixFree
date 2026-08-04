# 🚀 CineFlix

<p align="center">
  <img src="https://img.shields.io/badge/Status-Online-cyan?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/PWA-Supported-blueviolet?style=for-the-badge" alt="PWA">
  <img src="https://img.shields.io/badge/Powered%20by-SuperFlix%20API-orange?style=for-the-badge" alt="SuperFlix">
</p>

O **CineFlix** é uma plataforma de streaming web moderna, leve e responsiva, desenvolvida inteiramente com HTML5, Tailwind CSS e JavaScript puro (AJAX). O projeto consome dinamicamente dados de séries, animes, doramas e filmes cadastrados em um arquivo **JSON externo** e integra-se diretamente com a **SuperFlix API** para reprodução de conteúdos.

---

## ✨ Recursos Principais

- 📱 **PWA Nativo (Android & iOS)**: Instale o aplicativo diretamente na tela inicial do seu celular para abri-lo em modo tela cheia, como um aplicativo nativo.
- 🎬 **Catálogo Dinâmico via JSON**: Adicione ou remova filmes, séries, animes e doramas facilmente editando apenas o arquivo `catalogo.json`.
- 🔄 **Seletor de Temporadas e Episódios**: Navegação fluida integrada para conteúdos com múltiplos episódios.
- ⚡ **Hospedagem Gratuita**: Pronta para rodar direto no **GitHub Pages** sem necessidade de servidores backend.

---

## 📁 Estrutura de Arquivos

Organize os arquivos na raiz do seu repositório GitHub da seguinte forma:

```text
📦 kseven-stream/
 ┣ 📜 index.html        # Interface principal do player, catálogo e registro PWA
 ┣ 📜 catalogo.json     # Banco de dados externo com as mídias e temporadas
 ┣ 📜 manifest.json     # Configurações do Progressive Web App (PWA)
 ┣ 📜 sw.js             # Service Worker para cache e suporte offline
 ┗ 📜 README.md         # Documentação do projeto
