
# 🧠 HTML - Seu Primeiro Código (Capítulo 04 - Aula 02)

📅 Criado em: **14 de julho de 2025**  
📚 Matéria: **Programação Web (HTML5 e CSS3)**  
✍️ Autor: **Marco**

---

## ✨ TEMA: Introdução ao HTML e meu primeiro código!

> Esse é um resumo que fiz enquanto aprendia HTML. Escrevi com uma linguagem mais simples porque quero revisar no futuro e entender com clareza o que eu mesmo estudei. 😄

---

## 📌 O que é HTML?

- HTML significa **HyperText Markup Language** (em português: Linguagem de Marcação de Hipertexto).
- É a **base de qualquer página web**.
- Não é uma linguagem de programação, e sim de **marcação** – a gente usa "tags" pra estruturar o conteúdo.
- O HTML é responsável por organizar **textos, imagens, links, vídeos** e mais.

---

## 🧱 Estrutura Básica de um Documento HTML

Todo arquivo HTML segue uma estrutura padrão. Aqui vai o esqueleto básico:

```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Primeira Página HTML</title>
  </head>
  <body>
    <h1>Olá, Mundo!</h1>
    <p>Esta é a minha primeira página web.</p>
    <p>Estou aprendendo HTML!</p>
  </body>
</html>
```

---

### 🔍 Explicando parte por parte:

| Tag | Função |
|-----|--------|
| `<!DOCTYPE html>` | Diz ao navegador que estamos usando **HTML5** |
| `<html lang="pt-br">` | Começa o documento HTML e define o **idioma (Português do Brasil)** |
| `<head>` | Guarda informações "invisíveis" (metadados) como o título e configuração de codificação |
| `<meta charset="UTF-8">` | Faz com que acentos e símbolos apareçam corretamente |
| `<meta name="viewport"...>` | Deixa a página adaptável a celulares e tablets (design responsivo) |
| `<title>` | Título que aparece na aba do navegador |
| `<body>` | Tudo que aparece na tela: textos, imagens, links, etc |

---

## 🏷️ Como funcionam as tags HTML?

- A maioria das tags tem **abertura** e **fechamento**:
  ```html
  <p>Este é um parágrafo.</p>
  ```
- Algumas são **autofechantes** (ou "void"):
  ```html
  <br>  <!-- quebra de linha -->
  <img src="imagem.jpg" alt="Descrição da imagem">  <!-- imagem -->
  ```

---

## ⚙️ Atributos

Os **atributos** servem pra passar informações extras. Exemplo:

```html
<a href="https://www.google.com">Ir para o Google</a>
```

- `href="..."` é o atributo que define o **endereço do link**.

---

## 💻 Como visualizar seu código HTML

1. Abra um editor de texto simples (Notepad, VS Code, etc).
2. Digite o código HTML.
3. Salve com a extensão `.html`, exemplo: `index.html`
4. Dê dois cliques no arquivo ou abra com o navegador.

---

## 🧠 Dicas para memorizar:

- **HTML = Estrutura do site**.
- Tudo começa com `<!DOCTYPE html>` e a tag `<html>`.
- O que está em `<head>` são informações para o navegador (como o título).
- O que está em `<body>` é o que o usuário vê.
- Sempre use `<meta charset="UTF-8">` para evitar erros com acentos.
- O `viewport` é essencial para sites responsivos.
- O `<title>` ajuda em SEO e deixa sua aba com nome.

---

### 🚀 Bora continuar?

Se você também está aprendendo HTML, me segue por aqui ou dá um ⭐️ nesse repositório!
