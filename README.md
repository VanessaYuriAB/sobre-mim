# Sobre Mim

> Este é o meu primeiro projeto independente do curso de Desenvolvimento Web na Triple Ten
> Brasil.

O objetivo foi criar uma **página web “Sobre Mim”** com a **mesma estrutura** da página
“Quatro Regras de Design” (projeto de estudo praticado anteriormente), alterando apenas
**conteúdo e imagens** para refletir informações pessoais e hobbies.

**OBS**: o repositório do projeto educacional "Quatro Regras de Design" pode ser acessado
[aqui](https://github.com/VanessaYuriAB/quatro-regras-design).

---

## 🎯 Objetivo do Projeto

- Recriar a estrutura do layout-base fornecido no curso
- Construir uma página com:
  - **Header** em tela cheia com imagem de fundo e sobreposição (overlay)
  - **Título principal** com fonte customizada
  - **Seção de conteúdo** com **4 cartões** (imagem + título + texto) em duas linhas
  - **Footer** com assinatura centralizada

---

## 🧩 Funcionalidades e Requisitos Implementados

- Layout com **estrutura semântica**: `<header>`, `<section>`, `<footer>`
- Header com:
  - imagem de fundo (`background-image`)
  - `overlay` semitransparente
  - título centralizado vertical e horizontalmente com `flex`
- Conteúdo com 4 cartões:
  - disposição em duas linhas usando `flex-wrap`
  - espaçamento com `justify-content: space-between`
  - estilos de sombra e `padding` conforme roteiro
- Rodapé com assinatura centralizada

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- Fonte customizada via `@font-face`

---

## 📁 Estrutura de Pastas

```Shell
sobre-mim/
├── fonts/
│   ├── Inter.ttf
│   ├── PermanentMarker.ttf
│   └── PermanentMarker.woff
├── images/
│   ├── card-image-amigos.jpg
│   ├── card-image-desenvolvedor-web.jpg
│   ├── card-image-familia.jpg
│   ├── card-image-musica.jpg
│   └── header-image.jpg
├── index.html
├── README.md
└── style.css
```

---

## ▶️ Como Executar o Projeto

1. Baixe/clone este repositório.
2. Abra o arquivo `index.html` no navegador.

**OBS**: se estiver usando `VS Code`, você pode instalar a extensão `Live Server` e abrir
com `Go Live` ou `Open with Live Server`.

---

## ✅ Checklist (Auto-verificação)

### Geral

- A página abre corretamente no _Chrome/Firefox_
- Não há rolagem horizontal em resolução de computador
- Imagens personalizadas estão na pasta `images/`
- Funcionalidade e layout seguem o roteiro
- Dimensões e espaçamentos seguem o design (variação máxima de `30px`)

### HTML

- Sem `div` para texto (uso correto de `<h1>…<h6>` e `<p>`)
- Elementos semânticos presentes: `<header>`, `<section>`, `<footer>`
- Todas as imagens dos cartões possuem `alt` descritivo
- Não foram usados valores negativos de `margin/padding`

### CSS

- Largura do bloco `.content` definida conforme o roteiro
- Cartões centralizados e organizados em duas linhas
- `height` usado apenas quando necessário (ex.: imagens dos cartões, se aplicado)
- Imagens ajustadas com `object-fit`, quando necessário, para padronização

---

## 🖼️ Conteúdo

A página apresenta quatro cartões com temas pessoais (hobbies/interesses), cada um
contendo:

- uma imagem
- um título
- uma descrição curta

> Você pode substituir os temas e as imagens livremente, mantendo a mesma estrutura.

---

👤 Autora

Vanessa Yuri A. Brito

Projeto desenvolvido como parte do curso da TripleTen.
