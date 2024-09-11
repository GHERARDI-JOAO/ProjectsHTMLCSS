## CSS

### 1. Adicionar o Elemento `style`
Você pode adicionar estilo a um elemento, especificando-o no elemento `style` e definindo uma propriedade para ele assim:

```html
<style>
  h1 {
    text-align: center;
  }
</style>
```

### 2. Vincular o Arquivo `styles.css`
Para que os estilos sejam aplicados, adicione um elemento `link` dentro do elemento `head` com os seguintes atributos:

```html
<link rel="stylesheet" href="styles.css" />
```

### 3. Adicionar o Meta Tag para Responsividade
Adicione um elemento `meta` com o atributo especial `content` para garantir que a página seja exibida corretamente em diferentes dispositivos:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

### 4. Alterar o Fundo da Página
Para definir a cor de fundo do `body`, adicione a propriedade `background-color`:

```css
body {
  background-color: brown;
}
```

### 5. Usar o Elemento `div` para Layout
O elemento `div` é usado principalmente para layout. Adicione um elemento `div` dentro do `body` e mova todos os outros elementos para dentro dele:

```html
<div id="menu">
  <main>
    <h1>CAMPER CAFE</h1>
    <p>Est. 2020</p>
    <section>
      <h2>Coffee</h2>
    </section>
  </main>
</div>
```

### 6. Definir Largura da `div`
Para fazer com que a `div` não ocupe toda a largura da página, use a propriedade `width`:

```css
#menu {
  width: 300px;
}
```

### 7. Centralizar a `div`
Centralize o elemento `#menu` horizontalmente definindo `margin-left` e `margin-right` como `auto`:

```css
#menu {
  margin-left: auto;
  margin-right: auto;
}
```

### 8. Usar Seletor de Classe
Um seletor de classe é definido por um ponto antes do nome da classe:

```css
.class-name {
  styles
}
```

### 9. Aplicar Classe ao `div`
Substitua o `id` pelo `class` na `div` e defina o valor como `menu`:

```html
<div class="menu">
```

### 10. Adicionar Imagem de Fundo
Use uma imagem de fundo para o corpo da página:

```css
body {
  background-image: url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg);
}
```

### 11. Estruturar o `article`
Aninhe dois elementos `p` dentro do `article` para o sabor e o preço:

```html
<article>
  <p>French Vanilla</p>
  <p>3.00</p>
</article>
```

### 12. Adicionar Classes para Estilo
Adicione a classe `flavor` ao elemento `p` que diz `French Vanilla`:

```html
<p class="flavor">French Vanilla</p>
<p>3.00</p>
```

### 13. Estilo dos Elementos `p`
Para que os elementos `p` fiquem na mesma linha, defina `display: inline-block`:

```css
.item p {
  display: inline-block;
}
```

### 14. Adicionar Espaçamento
Adicione padding à classe `menu`:

```css
.menu {
  padding-left: 20px;
  padding-right: 20px;
  width: 80%;
  max-width: 500px;
}
```

### 15. Alterar a Família da Fonte
Defina a fonte do corpo e dos títulos:

```css
body {
  font-family: sans-serif;
}

h1, h2 {
  font-family: Impact, serif;
}
```

### 16. Ajustar o Tamanho da Fonte
Defina o tamanho da fonte para `h1` e `h2`:

```css
h1 {
  font-size: 40px;
}
h2 {
  font-size: 30px;
}
```

### 17. Estilizar o Divisor
Altere a altura e a cor das bordas do elemento `hr`:

```css
hr {
  height: 3px;
  border-color: transparent;
}
```

### 18. Ajustar Margens e Tamanho da Fonte
Ajuste a margem e o tamanho da fonte para elementos dentro da classe `item`:

```css
.item p {
  margin-top: 5px;
  margin-bottom: 5px;
  font-size: 18px;
}
```

### 19. Adicionar Margem Inferior
Crie uma classe `bottom-line` para adicionar margem superior:

```css
.bottom-line {
  margin-top: 25px;
}
```

### 20. Estilizar o Rodapé
Defina o tamanho da fonte e as cores dos links no rodapé:

```css
footer {
  font-size: 14px;
}

a {
  color: black;
}

a:visited {
  color: grey;
}

a:hover {
  color: brown;
}

a:active {
  color: white;
}
```

### 21. Remover Margem Superior do `h1`
Remova a margem superior do `h1` e ajuste a margem inferior do `p`:

```css
h1 {
  margin-top: 0;
  margin-bottom: 15px;
}

.address {
  margin-bottom: 5px;
}
```

### 22. Centralizar Imagem
Centralize imagens e ajuste a margem superior:

```css
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-top: -25px;
}
```
