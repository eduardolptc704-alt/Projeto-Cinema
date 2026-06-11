# 🎬 Portal Cinema - Interface Responsiva

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Layout-Responsivo-00c853?style=for-the-badge" alt="Responsivo">
</p>

O **Portal Cinema** é uma plataforma web responsiva desenvolvida para simular a navegação de salas de cinema e detalhes de filmes em cartaz. O objetivo principal deste projeto foi consolidar conceitos de estruturação semântica avançada, design responsivo fluido e arquitetura de código CSS escalável sem o uso de frameworks ou bibliotecas externas.

---

## 🔗 Demonstração Ao Vivo

O projeto está totalmente online e disponível para testes através do GitHub Pages!
🚀 [Acesse o Portal Cinema funcionando na prática](https://eduardolptc704-alt.github.io/Projeto-Cinema/index.html)

---

## 🛠️ Recursos e Destaques Técnicos

### 1. Arquitetura CSS Organizada
- **Estilos Globais (`global.css`):** Centralização de resets, variáveis e componentes compartilhados (cabeçalho com lógica flexível, menu e rodapé), eliminando redundâncias.
- **Estilos Específicos (`style.css` e `style2.css`):** Separação de escopo para a página inicial e para o layout modularizado de 3 colunas das salas de cinema.

### 2. Componentes Inteligentes (Apenas CSS)
- **Menu Lateral Hambúrguer:** Desenvolvido de forma nativa utilizando a técnica de associação entre `<input type="checkbox">` e seletores irmãos (`~`), dispensando o uso de JavaScript para manipulação do DOM.
- **Barra de Busca Expansível:** Caixa de pesquisa com animação suave de transição ao focar (`:focus-within`) e ícone de lupa SVG injetado via propriedade `background-image`.

### 3. Layout Fluido e Navegação Integrada
- **Grids e Alinhamentos:** Uso de **CSS Grid** e **Flexbox** para garantir uma transição de visualização natural entre monitores e smartphones.
- **Navegação Cíclica e Centralizada:** Implementação de setas de paginação integradas ao título `<h1>` das salas que mantêm o alinhamento perfeito mesmo em telas menores, guiando o usuário de forma circular (do Cinema 1 ao 4).

---
