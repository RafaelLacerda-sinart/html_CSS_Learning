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

| Conceito | Função |
|-----------|--------|
| Cascata | Define qual regra vence em caso de conflito |
| Especificidade | Determina prioridade entre seletores |
| Box Model | Controla tamanho e espaçamento dos elementos |
| Herança | Permite que propriedades sejam herdadas |

---

# 📌 2. Seletores Mais Utilizados

| Tipo | Exemplo | Uso |
|------|----------|------|
| Classe | `.container` | Organização principal do CSS |
| ID | `#header` | Elemento único |
| Descendente | `div p` | Seleciona elementos dentro de outro |
| Filho direto | `div > p` | Apenas filhos imediatos |
| Pseudo-classe | `:hover` | Estados do elemento |
| Tag | `p` | Seleção direta por elemento |

---

# 📌 3. Box Model

| Propriedade | Função |
|-------------|--------|
| width / height | Define dimensões |
| padding | Espaço interno |
| border | Borda do elemento |
| margin | Espaço externo |
| box-sizing | Controla cálculo do tamanho |

---

# 📌 4. Layout (Estrutura)

| Propriedade | Função |
|-------------|--------|
| display | Define tipo de layout |
| position | Controle de posicionamento |
| width / height | Dimensões |
| margin | Espaçamento externo |
| padding | Espaçamento interno |
| overflow | Controla excesso de conteúdo |

---

# 📌 5. Display Mais Importantes

| Tipo | Função |
|------|--------|
| block | Ocupa linha inteira |
| inline | Apenas conteúdo |
| flex | Layout flexível |
| grid | Layout em grade |
| none | Remove da renderização |

---

# 📌 6. Flexbox (Essencial)

| Propriedade | Função |
|-------------|--------|
| display: flex | Ativa o Flexbox |
| justify-content | Alinhamento horizontal |
| align-items | Alinhamento vertical |
| flex-direction | Linha ou coluna |
| gap | Espaço entre itens |
| flex-wrap | Quebra de linha |

---

# 📌 7. Grid (Estrutura Avançada)

| Propriedade | Função |
|-------------|--------|
| display: grid | Ativa o Grid |
| grid-template-columns | Define colunas |
| grid-template-rows | Define linhas |
| gap | Espaçamento entre células |

---

# 📌 8. Tipografia

| Propriedade | Função |
|-------------|--------|
| font-size | Tamanho da fonte |
| font-family | Tipo da fonte |
| font-weight | Peso da fonte |
| line-height | Altura da linha |
| text-align | Alinhamento do texto |

---

# 📌 9. Cores e Aparência

| Propriedade | Função |
|-------------|--------|
| color | Cor do texto |
| background | Fundo |
| border | Borda |
| border-radius | Arredondamento |
| box-shadow | Sombra |

---

# 📌 10. Unidades Mais Usadas

| Unidade | Tipo |
|----------|------|
| px | Fixa |
| % | Relativa ao elemento pai |
| rem | Relativa ao root |
| vw | Relativa à largura da tela |

---

# 📌 11. Pseudo-classes Essenciais

| Pseudo-classe | Uso |
|---------------|------|
| :hover | Interação com mouse |
| :focus | Elemento ativo |
| :active | Clique |
| :nth-child() | Seleção específica |

---

# 📌 12. Responsividade

| Recurso | Função |
|----------|--------|
| Media Queries | Regras por tamanho de tela |
| Flexbox | Ajuste automático |
| Grid | Estrutura adaptável |
| Mobile First | Estratégia responsiva |

---

# 📌 13. Animações Básicas

| Propriedade | Função |
|-------------|--------|
| transition | Transições suaves |
| transform | Movimentos e escala |
| animation | Animações |

---

# 📌 14. Position

| Tipo | Função |
|------|--------|
| relative | Base para posicionamento |
| absolute | Posicionamento livre |
| fixed | Fixo na tela |
| sticky | Fixo condicional |

---



