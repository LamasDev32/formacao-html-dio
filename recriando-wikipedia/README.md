# Recriando a Página da Wikipédia: Dragon Ball Z

Projeto desenvolvido para estudo prático de **estruturação semântica em HTML5** e **estilização com CSS3**, reproduzindo fielmente o layout, a hierarquia visual e os componentes clássicos da [Wikipédia](https://pt.wikipedia.org) tendo como tema o anime **Dragon Ball Z**.

---

## 🎯 Objetivos de Aprendizado

- Compreender a separação de responsabilidades entre **Estrutura (HTML)** e **Apresentação (CSS)**.
- Utilizar tags semânticas da especificação HTML5 (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<figure>`, `<footer>`).
- Estruturar dados tabulares acessíveis com `<table>`, `<thead>`, `<tbody>`, `<th>` (com atributos `scope="col"` e `scope="row"`), `<td>` e `<caption>`.
- Criar componentes canônicos da Wikipédia:
  - **Cabeçalho superior fixo** com busca e ações de usuário.
  - **Barra de navegação lateral (Sidebar)** com listas e links interativos.
  - **Infobox lateral flutuante** com ficha técnica, vetores SVG e dados estruturados.
  - **Sumário / Índice interativo (TOC)** com links âncora internos (`href="#id"`).
  - **Tabela comparativa de sagas (`wikitable`)** com cabeçalhos e efeito zebrado.
  - **Citações em bloco (`<blockquote>`) e notas de rodapé com referências sobrescritas (`<sup>`, `<ol>`)**.
  - **Caixa de categorias (`catlinks`)** e **rodapé MediaWiki**.
- Praticar **CSS Grid** e **Flexbox** para layouts modernos e responsivos (desktop, tablet e mobile).

---

## 📂 Estrutura de Arquivos

```text
recriando-wikipedia/
├── index.html       # Estrutura completa do documento HTML5
├── style.css        # Estilos, variáveis CSS, tipografia e responsividade
└── README.md        # Documentação e guia de estudo
```

---

## 🧱 Destaques da Estrutura HTML Semântica

1. **`<!DOCTYPE html>` e `<html lang="pt-BR">`**: Configuração correta de internacionalização e conformidade com padrões modernos.
2. **`<aside class="infobox">`**: Ficha técnica lateral que agrega metadados, gênero, episódios, autor e cronologia.
3. **`<nav class="toc">`**: Sumário com listas aninhadas ordenadas (`<ol>`) conectadas via âncoras locais.
4. **`<table class="wikitable">`**: Tabela semântica de arcos narrativos com escopo de cabeçalhos (`scope="col"` e `scope="row"`).
5. **`<figure>` e `<figcaption>`**: Agrupamento semântico da ilustração vetorial e sua respectiva legenda.
6. **`<sup>` e `<ol class="references">`**: Numeração e ancoragem de referências bibliográficas.
7. **`<mark>` e `<abbr>`**: Realce de termos-chave e expansão de siglas.

---

## 🎨 Destaques do CSS3

- **CSS Custom Properties (Variáveis)**: Centralização da paleta de cores clássica da Wikipédia (`#202122`, `#3366cc`, `#a2a9b1`, `#f8f9fa`).
- **Tipografia**: Combinação da fonte com serifa *Linux Libertine / Georgia* para títulos (`h1`, `h2`) com fontes sem serifa modernas no corpo de texto.
- **Layout com CSS Grid**: Divisão em duas colunas (`220px 1fr`) para a barra lateral e o artigo principal.
- **Flutuação (`float: right;`) e Limpeza (`clear`)**: Demonstração de layout tradicional para infoboxes em páginas de texto longo.
- **Media Queries Responsivas**: Ajuste fluido para telas menores que 960px e 600px.

---

## 🚀 Como Visualizar

1. Abra o arquivo `index.html` diretamente em qualquer navegador moderno (Google Chrome, Edge, Firefox, etc.).
2. Ou utilize extensões como o **Live Server** no VS Code para recarregamento em tempo real.

