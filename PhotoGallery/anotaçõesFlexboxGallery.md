### Propriedade `box-sizing`

- A borda azul da imagem se estende além da borda vermelha da galeria devido à forma como os navegadores calculam o tamanho dos elementos contêineres.
- A propriedade `box-sizing` define esse comportamento.
- O valor padrão é `content-box`. Nesse modelo, a largura de um elemento é calculada apenas com base no conteúdo, e os valores de padding (preenchimento) e borda são adicionados ao tamanho total, fazendo o elemento crescer.
- Tente definir `box-sizing` para `content-box` explicitamente, usando o seletor global `*`. Neste caso, você não verá nenhuma mudança, já que esse é o valor padrão.

---

### Flexbox: Conceitos Básicos

- Flexbox é um layout CSS unidimensional que controla o espaçamento e alinhamento dos itens dentro de um contêiner.
- Para usar, defina a propriedade `display` de um elemento como `flex`. Isso torna o elemento um **contêiner flex**.
- Os filhos diretos de um contêiner flex são chamados de **itens flex**.

```css
.gallery {
  display: flex;
}
```

- Flexbox tem dois eixos: o eixo principal e o eixo cruzado.
  - O eixo principal é definido pela propriedade `flex-direction`, que tem quatro valores possíveis:
    - `row` (padrão): eixo horizontal, com itens da esquerda para a direita
    - `row-reverse`: eixo horizontal, com itens da direita para a esquerda
    - `column`: eixo vertical, com itens de cima para baixo
    - `column-reverse`: eixo vertical, com itens de baixo para cima
  - **Nota**: os eixos e direções podem mudar dependendo da direção do texto (ex.: de esquerda para direita).

---

### Propriedade `flex-wrap`

- Define o comportamento dos itens flex quando o contêiner é pequeno demais.
- Com o valor `wrap`, os itens podem quebrar para a próxima linha ou coluna.
- O valor padrão `nowrap` impede a quebra e encolhe os itens, se necessário.

---

### Propriedade `justify-content`

- Controla o alinhamento dos itens ao longo do eixo principal.
- Determina a posição e o espaço ao redor dos itens.

```css
.gallery {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
}
```

---

### Propriedade `align-items`

- Controla o alinhamento dos itens ao longo do eixo cruzado.
- Se o `flex-direction` estiver em `row`, o eixo cruzado será vertical.
- Para centralizar verticalmente suas imagens, use `align-items: center`.

---

### Propriedade `object-fit`

- Algumas imagens podem ficar distorcidas devido a diferentes proporções de aspecto.
- Para manter a proporção, use a propriedade `object-fit: cover` nas imagens.
- Isso ajustará a imagem para preencher o contêiner, cortando a imagem se necessário.

```css
.gallery img {
  object-fit: cover;
}
```

---

### Propriedade `gap`

- A propriedade `gap` define o espaço entre as linhas e colunas.
- Essa propriedade pode ser usada com layout flex, grid ou multi-coluna.
- Defina um `gap` de `16px` no contêiner flex da galeria para espaçar as imagens.

---

### Pseudo-elemento `::after`

- O pseudo-elemento `::after` cria um elemento vazio após o último filho do elemento selecionado.
- Ele pode ser usado para empurrar a última imagem para a esquerda quando a galeria estiver em um layout de duas colunas.

```css
.gallery::after {
  content: "";
  width: 350px;
}
```