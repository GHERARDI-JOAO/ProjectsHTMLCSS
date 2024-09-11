# **HTML**

### **Cabeçalhos (H1, H2, H3, etc.)**

- O elemento `<h1>` é usado para o cabeçalho principal de uma página da web.
- Os elementos de `<h1>` a `<h6>` são usados para classificar cabeçalhos em ordem de importância, sendo `<h1>` o mais importante e `<h6>` o menos importante.
- Usar somente **um** `<h1>` por página.

Exemplo:

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <h2>Cat Photos</h2>
    <p>See more cat photos in our gallery.</p>
  </body>
</html>

```

---

### **Parágrafo**

- O elemento `<p>` é usado para criar parágrafos de texto.

Exemplo:

```html
<p>Este é um parágrafo.</p>

```

---

### **Comentários**

- Para adicionar comentários no código HTML, usa-se `<!-- comentário -->`.

Exemplo:

```html
<!-- TODO: Adicionar link para fotos de gatos -->

```

---

### **Elemento `<main>`**

- O elemento `<main>` é usado para indicar a área principal do conteúdo de uma página.

Exemplo:

```html
<main>
  <h1>CatPhotoApp</h1>
  <p>Conteúdo principal aqui.</p>
</main>

```

---

### **Indentação**

- Elementos aninhados devem ser indentados com **dois espaços** para melhorar a legibilidade do código.

---

### **Imagens (`<img>`)**

- O elemento `<img>` é usado para adicionar imagens. Ele é auto-fechado (não precisa de tag de fechamento).
- Atributo `src`: especifica o URL da imagem.
- Atributo `alt`: adiciona uma descrição alternativa à imagem.

Exemplo:

```html
<img src="url-da-imagem.jpg" alt="Descrição da imagem">

```

---

### **Links (`<a>`)**

- O elemento `<a>` cria links para outras páginas.
- O texto do link é colocado entre as tags de abertura e fechamento de `<a>`.
- Atributo `href`: define o destino do link.
- Atributo `target="_blank"`: abre o link em uma nova aba.

Exemplo:

```html
<a href="<https://www.exemplo.com>" target="_blank">Visite nosso site</a>

```

---

### **Imagens como Links**

- Imagens também podem ser transformadas em links.

Exemplo:

```html
<a href="url-da-pagina">
  <img src="url-da-imagem.jpg" alt="Descrição da imagem">
</a>

```

---

### **Elemento `<section>`**

- O `<section>` define seções em um documento, ajudando na estruturação do conteúdo.

Exemplo:

```html
<section>
  <h2>Título da Seção</h2>
  <p>Conteúdo da seção.</p>
</section>

```

---

### **Listas**

- **Listas não ordenadas**: criadas com o elemento `<ul>`.
- **Listas ordenadas**: criadas com o elemento `<ol>`.

Exemplos:

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>

<ol>
  <li>Item 1</li>
  <li>Item 2</li>
</ol>

```

---

### **Elemento `<figure>`**

- Usado para associar imagens com legendas.
- O `<figcaption>` adiciona uma legenda à imagem.

Exemplo:

```html
<figure>
  <img src="url-da-imagem.jpg" alt="Descrição da imagem">
  <figcaption>Legenda da imagem.</figcaption>
</figure>

```

---

### **Destaque de Texto**

- **Itálico**: usa-se o elemento `<em>`.
- **Negrito**: usa-se o elemento `<strong>`.

Exemplos:

```html
<em>Texto em itálico</em>
<strong>Texto em negrito</strong>

```

---

### **Formulários (`<form>`)**

- O elemento `<form>` cria um formulário.
- Atributo `action`: define o destino do formulário.

Exemplo:

```html
<form action="<https://www.exemplo.com/enviar>">
  <input type="text" name="nome">
</form>

```

---

### **Input e Placeholder**

- O elemento `<input>` cria campos para entrada de dados.
- Atributo `placeholder`: sugere o que deve ser inserido no campo.
- Atributo `required`: torna o campo obrigatório.

Exemplo:

```html
<input type="text" placeholder="Insira seu nome" required>

```

---

### **Botão (`<button>`)**

- O elemento `<button>` cria um botão clicável.

Exemplo:

```html
<button type="submit">Enviar</button>

```

---

### **Labels e Radio Buttons**

- O elemento `<label>` associa um rótulo a um campo `<input>`.
- O atributo `id` deve ser único por página.

Exemplo:

```html
<label for="email">Email:</label>
<input id="email" type="email">

```

---

### **Fieldsets e Legendas**

- O elemento `<fieldset>` agrupa campos relacionados.
- O `<legend>` adiciona uma legenda ao conjunto de campos.

Exemplo:

```html
<fieldset>
  <legend>Tipo de Gato</legend>
  <label><input type="radio" name="gato" value="indoor"> Indoor</label>
</fieldset>

```

---

### **Rodapé (`<footer>`)**

- O `<footer>` é usado para definir o rodapé de um documento, normalmente contendo informações de copyright, links, etc.

Exemplo:

```html
<footer>
  <p>&copy; 2024 CatPhotoApp</p>
</footer>

```

---

### **Cabeçalho da Página (`<head>`)**

- O elemento `<head>` contém metadados, como o título da página e links para folhas de estilo.
- Toda página deve começar com `<!DOCTYPE html>` para indicar ao navegador que se trata de um documento HTML5.

Exemplo:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>CatPhotoApp</title>
  </head>
  <body>
    <h1>Bem-vindo ao CatPhotoApp!</h1>
  </body>
</html>

```
