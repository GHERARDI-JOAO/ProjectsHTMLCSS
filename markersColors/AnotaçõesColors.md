### Classes Múltiplas no CSS

Quando um elemento tem duas classes, você pode criar uma nova regra CSS vinculada à segunda classe. Exemplo:

```html
<div class="marker one"></div>

```

No CSS:

```css
.one {
  background-color: red;
}

```

### Modelos de Cor

Existem dois modelos de cores:

- **RGB (aditivo)**: usado em dispositivos eletrônicos.
- **CMYK (subtrativo)**: usado em impressão.

Neste projeto, usaremos **RGB**. As cores começam como preto e mudam conforme você adiciona diferentes níveis de vermelho, verde e azul.

### Definindo Cores com `rgb`

A função `rgb()` aceita três argumentos (vermelho, verde, azul) e produz uma cor. Exemplo:

```css
.container {
  background-color: rgb(0, 0, 0); /* Preto */
}

```

### Exemplo de Cores Primárias (RGB):

- **Vermelho:** `rgb(255, 0, 0)`
- **Verde:** `rgb(0, 255, 0)`
- **Azul:** `rgb(0, 0, 255)`

### Exemplo de Cores Secundárias:

- **Ciano:** `rgb(0, 255, 255)` (Verde + Azul)
- **Magenta:** `rgb(255, 0, 255)` (Vermelho + Azul)
- **Amarelo:** `rgb(255, 255, 0)` (Vermelho + Verde)

### Cores com `hsl()`

O modelo de cores **HSL** (matiz, saturação e luminosidade) também pode ser usado. A função `hsl()` tem três parâmetros:

1. **Matiz**: Valor de 0 a 360 (ex: 0° = Vermelho, 120° = Verde, 240° = Azul).
2. **Saturação**: Intensidade da cor, de 0% (tons de cinza) a 100% (cor vibrante).
3. **Luminosidade**: Clareza da cor, de 0% (preto) a 100% (branco).

Exemplo:

```css
background-color: hsl(240, 100%, 50%); /* Azul */

```

### Gradientes com CSS

Um gradiente é uma transição suave de uma cor para outra. A função `linear-gradient()` permite controlar a direção e as cores da transição.

Exemplo de sintaxe:

```css
background: linear-gradient(to right, red, yellow);

```

### Opacidade no CSS

A opacidade controla a transparência de um elemento. No CSS, usamos a propriedade `opacity`, que vai de 0 (totalmente transparente) a 1 (totalmente opaco).

Exemplo:

```css
opacity: 0.5; /* 50% de opacidade */

```

Também podemos adicionar um canal alfa às cores com a função `rgba()`:

```css
background-color: rgba(255, 255, 255, 0.5); /* Branco com 50% de opacidade */

```

### Exibindo Elementos na Mesma Linha

Para exibir elementos `div` na mesma linha, defina a propriedade `display` como `inline-block`:

```css
.cap, .sleeve {
  display: inline-block;
}

```

### Bordas no CSS

Você pode controlar as bordas de um elemento com a propriedade `border`. Use a propriedade abreviada `border-left` para definir largura, estilo e cor de uma vez:

```css
.sleeve {
  border-left: 10px solid black;
}

```

### Sombra em Elementos com `box-shadow`

A propriedade `box-shadow` adiciona sombras aos elementos. Exemplo de sintaxe:

```css
box-shadow: offsetX offsetY color;

```

- `offsetX`: Desloca a sombra horizontalmente (positiva para direita, negativa para esquerda).
- `offsetY`: Desloca a sombra verticalmente (positiva para baixo, negativa para cima).

Exemplo:

```css
box-shadow: 5px 5px 10px gray;

```

---

Assim, o texto está mais estruturado e direto, facilitando a compreensão das principais funções e propriedades CSS abordadas no projeto.
