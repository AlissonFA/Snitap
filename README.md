<h1 align="center">🛼 Snitap</h1>

<p align="center">
  <a href="#o-projeto">O Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#layout">Layout</a>
</p>

<p align="center">
  <img src="./assets/images/preview.png" width="100%">
</p>

## 💻 O Projeto <a id="o-projeto"></a>

Snitap é uma landing page para uma marca fictícia de patins, desenvolvida como exercício do módulo de **CSS Animations & Transitions** da formação Full-Stack da Rocketseat. O projeto explora animações complexas, transições e responsividade, com foco em criar uma experiência visual dinâmica e fluida.

Os principais destaques do desenvolvimento incluem:

1. **Animação de texto rotativo no Hero:** Implementação de um slideUp cíclico com keyframes que simula "pulos" físicos ao trocar as palavras, com versões distintas para desktop (`5rem` de altura) e mobile (`2.5rem`), garantindo proporção visual em cada breakpoint.
2. **Banner com gradiente animado em loop:** Combinação de `animation-timeline` com `background-position` em `400% 400%` para criar uma transição contínua entre as cores da marca sem cortes perceptíveis.
3. **Galeria com scroll-driven animation:** As figuras da galeria entram com `translateY` conforme o scroll utilizando `animation-timeline: view()` e `animation-range`, com atraso configurável via `data-delay` para criar entrada escalonada.
4. **Responsividade como desafio:** O layout desktop foi fornecido pelo professor — a adaptação mobile foi um desafio cumprido inteiramente por mim, reorganizando o Hero em `column-reverse`, ajustando tipografia, espaçamentos e direções de flex para telas até `48em`.

## 🚀 Tecnologias <a id="tecnologias"></a>

* **HTML5:** Estrutura semântica da página com uso de `<section>`, `<figure>`, `<figcaption>` e `<footer>`.
* **CSS3:** Animações com `@keyframes`, transições, CSS Grid para a galeria com `grid-template-areas`, scroll-driven animations com `animation-timeline: view()`, gradiente animado e CSS Nesting.
* **CSS Modular com `@import`:** Estilos organizados em arquivos separados por componente (`header`, `hero`, `banner`, `gallery`, `footer`) e importados via `index.css`.
* **Google Fonts:** Famílias **Syne** (títulos), **Montserrat** (corpo) e **Inter** (badge do carrinho) carregadas via CDN.
* **Git & GitHub:** Versionamento e deploy da aplicação.
* **Figma**

## 🔖 Layout <a id="layout"></a>

Você pode visualizar e interagir com o projeto através dos links abaixo:

* 📲 **[Acesse o layout original do projeto aqui](https://www.figma.com/community/file/1379866810042169871)**
* 👉 **[Acesse o site funcionando aqui](https://alissonfa.github.io/Snitap/)**

**Para rodar no seu computador (Local):**
1. Faça o download ou clone o repositório.
2. Certifique-se de que a estrutura de pastas está correta.
3. Dê um duplo clique no arquivo `index.html` ou abra através da extensão *Live Server* no seu editor de código.

---

Feito com 💜 por **[AlissonFA](https://www.linkedin.com/in/alissonfa/)**