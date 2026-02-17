# 📘 Guia Essencial de HTML

Este guia contém apenas as **tags e atributos mais utilizados no desenvolvimento web moderno**.

---

# 🥇 1. Estrutura Básica do Documento

| Tag | Descrição | Exemplo |
|------|------------|----------|
| `<!DOCTYPE html>` | Define o documento como HTML5 | `<!DOCTYPE html>` |
| `<html>` | Elemento raiz da página | `<html lang="pt-BR">` |
| `<head>` | Metadados da página | `<head>...</head>` |
| `<title>` | Título da aba do navegador | `<title>Minha Página</title>` |
| `<meta>` | Configurações como charset e responsividade | `<meta charset="UTF-8">` |
| `<link>` | Importa CSS externo | `<link rel="stylesheet" href="style.css">` |
| `<script>` | Importa ou escreve JavaScript | `<script src="app.js"></script>` |
| `<body>` | Conteúdo visível da página | `<body>...</body>` |

---

# 🥈 2. Estrutura Semântica

| Tag | Descrição |
|------|------------|
| `<header>` | Cabeçalho da página ou seção |
| `<nav>` | Menu de navegação |
| `<main>` | Conteúdo principal |
| `<section>` | Seção de conteúdo |
| `<article>` | Conteúdo independente |
| `<footer>` | Rodapé |

---

# 🥉 3. Texto e Conteúdo

| Tag | Descrição |
|------|------------|
| `<h1>` até `<h6>` | Títulos |
| `<p>` | Parágrafo |
| `<strong>` | Destaque importante (semântico) |
| `<em>` | Ênfase |
| `<br>` | Quebra de linha |
| `<hr>` | Linha divisória |
| `<code>` | Código inline |
| `<pre>` | Bloco de código |

---

# 🔗 4. Links e Mídia

| Tag | Descrição |
|------|------------|
| `<a>` | Link |
| `<img>` | Imagem |
| `<video>` | Vídeo |
| `<iframe>` | Incorporação externa |

---

# 📋 5. Listas

| Tag | Descrição |
|------|------------|
| `<ul>` | Lista não ordenada |
| `<ol>` | Lista ordenada |
| `<li>` | Item da lista |

---

# 📊 6. Tabelas

| Tag | Descrição |
|------|------------|
| `<table>` | Tabela |
| `<tr>` | Linha |
| `<th>` | Célula de cabeçalho |
| `<td>` | Célula |

---

# 📝 7. Formulários

| Tag | Descrição |
|------|------------|
| `<form>` | Formulário |
| `<input>` | Campo de entrada |
| `<textarea>` | Área de texto |
| `<button>` | Botão |
| `<label>` | Rótulo |
| `<select>` | Lista suspensa |
| `<option>` | Opção da lista |

---

# 🧱 8. Containers

| Tag | Descrição |
|------|------------|
| `<div>` | Container em bloco |
| `<span>` | Container inline |

---

# 📌 Atributos Essenciais

## Globais

| Atributo | Função | Exemplo |
|-----------|--------|----------|
| `class` | Classe para CSS/JS | `<div class="container">` |
| `id` | Identificador único | `<section id="sobre">` |
| `lang` | Idioma da página | `<html lang="pt-BR">` |

---

## Links (`<a>`)

| Atributo | Função | Exemplo |
|-----------|--------|----------|
| `href` | Destino do link | `<a href="/contato">` |
| `target` | Onde abrir o link | `<a target="_blank">` |
| `rel` | Segurança para `_blank` | `<a rel="noopener noreferrer">` |

---

## Imagens (`<img>`)

| Atributo | Função | Exemplo |
|-----------|--------|----------|
| `src` | Caminho da imagem | `<img src="foto.jpg">` |
| `alt` | Descrição da imagem | `<img alt="Produto">` |

---

## Formulários

| Atributo | Função | Exemplo |
|-----------|--------|----------|
| `type` | Tipo do input | `<input type="email">` |
| `name` | Nome enviado ao backend | `<input name="email">` |
| `placeholder` | Texto de ajuda | `<input placeholder="Digite seu email">` |
| `required` | Campo obrigatório | `<input required>` |

---

## Vídeo

| Atributo | Função | Exemplo |
|-----------|--------|----------|
| `controls` | Mostra controles | `<video controls>` |
| `muted` | Inicia sem som | `<video muted>` |

---

📎 Versão focada apenas no que realmente é utilizado em projetos reais.


# 🎨 CSS — GUIA COMPLETO E ORGANIZADO

---

# 📌 1. Fundamentos do CSS

| Conceito | Função | Exemplo |
|-----------|--------|----------|
| Cascata | A última regra pode sobrescrever a anterior | `p { color: blue; } p { color: red; }` |
| Especificidade | Seletores mais específicos têm prioridade | `#id { color: red; }` |
| Box Model | Controla tamanho e espaçamento | `div { margin: 10px; }` |
| Herança | Elementos filhos herdam propriedades | `body { color: gray; }` |

---

# 📌 2. Seletores Mais Utilizados

| Tipo | Exemplo CSS | Uso |
|------|--------------|------|
| Classe | `.box {}` | Organização principal |
| ID | `#menu {}` | Elemento único |
| Descendente | `div p {}` | Seleciona `p` dentro de `div` |
| Filho direto | `div > p {}` | Apenas filhos imediatos |
| Pseudo-classe | `a:hover {}` | Estado do elemento |
| Tag | `p {}` | Seleção direta |

---

# 📌 3. Box Model

| Propriedade | Função | Exemplo |
|-------------|--------|----------|
| width | Largura | `width: 200px;` |
| height | Altura | `height: 100px;` |
| padding | Espaço interno | `padding: 20px;` |
| border | Borda | `border: 1px solid black;` |
| margin | Espaço externo | `margin: 10px;` |
| box-sizing | Cálculo do tamanho | `box-sizing: border-box;` |

---

# 📌 4. Layout

| Propriedade | Função | Exemplo |
|-------------|--------|----------|
| display | Tipo de layout | `display: flex;` |
| position | Tipo de posicionamento | `position: relative;` |
| overflow | Controle de excesso | `overflow: hidden;` |

---

# 📌 5. Display

| Tipo | Função | Exemplo |
|------|--------|----------|
| block | Ocupa linha inteira | `display: block;` |
| inline | Apenas conteúdo | `display: inline;` |
| flex | Layout flexível | `display: flex;` |
| grid | Layout em grade | `display: grid;` |
| none | Remove elemento | `display: none;` |

---

# 📌 6. Flexbox

| Propriedade | Função | Exemplo |
|-------------|--------|----------|
| justify-content | Alinha horizontalmente | `justify-content: center;` |
| align-items | Alinha verticalmente | `align-items: center;` |
| flex-direction | Linha ou coluna | `flex-direction: column;` |
| gap | Espaço entre itens | `gap: 10px;` |
| flex-wrap | Quebra linha | `flex-wrap: wrap;` |

---

# 📌 7. Grid

| Propriedade | Função | Exemplo |
|-------------|--------|----------|
| grid-template-columns | Define colunas | `grid-template-columns: 1fr 1fr;` |
| grid-template-rows | Define linhas | `grid-template-rows: auto;` |
| gap | Espaçamento | `gap: 20px;` |

---

# 📌 8. Tipografia

| Propriedade | Função | Exemplo |
|-------------|--------|----------|
| font-size | Tamanho da fonte | `font-size: 16px;` |
| font-family | Tipo da fonte | `font-family: Arial;` |
| font-weight | Peso da fonte | `font-weight: bold;` |
| line-height | Altura da linha | `line-height: 1.5;` |
| text-align | Alinhamento | `text-align: center;` |

---

# 📌 9. Cores e Aparência

| Propriedade | Função | Exemplo |
|-------------|--------|----------|
| color | Cor do texto | `color: red;` |
| background | Fundo | `background: #f5f5f5;` |
| border-radius | Arredondamento | `border-radius: 8px;` |
| box-shadow | Sombra | `box-shadow: 0 4px 8px #0003;` |

---

# 📌 10. Unidades

| Unidade | Tipo | Exemplo |
|----------|------|----------|
| px | Fixa | `width: 200px;` |
| % | Relativa ao pai | `width: 50%;` |
| rem | Relativa ao root | `font-size: 1.5rem;` |
| vw | Relativa à tela | `width: 100vw;` |

---

# 📌 11. Pseudo-classes

| Pseudo-classe | Uso | Exemplo |
|---------------|------|----------|
| :hover | Interação com mouse | `button:hover {}` |
| :focus | Elemento ativo | `input:focus {}` |
| :active | Clique | `a:active {}` |
| :nth-child() | Seleção específica | `li:nth-child(2) {}` |

---

# 📌 12. Responsividade

| Recurso | Função | Exemplo |
|----------|--------|----------|
| Media Query | Regras por tela | `@media (max-width: 768px) {}` |
| Mobile First | Começa pelo mobile | `min-width` |
| Flexbox | Layout adaptável | `display: flex;` |

---

# 📌 13. Animações

| Propriedade | Função | Exemplo |
|-------------|--------|----------|
| transition | Transição suave | `transition: 0.3s;` |
| transform | Movimento/escala | `transform: scale(1.1);` |
| animation | Animação | `animation: fade 1s;` |

---

# 📌 14. Position

| Tipo | Função | Exemplo |
|------|--------|----------|
| relative | Base para posicionamento | `position: relative;` |
| absolute | Posicionamento livre | `position: absolute;` |
| fixed | Fixo na tela | `position: fixed;` |
| sticky | Fixo condicional | `position: sticky;` |

---
