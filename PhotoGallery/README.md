
# Galeria de Fotos com Flexbox

Este projeto é uma **galeria de fotos** desenvolvida com HTML e CSS, como parte de meus estudos de front-end. Ele exibe uma série de imagens organizadas em um layout flexível utilizando Flexbox, garantindo uma experiência responsiva e visualmente agradável.

## Descrição

A galeria foi criada para demonstrar a utilização do Flexbox no CSS, com as seguintes funcionalidades:
- Layout flexível e responsivo que se ajusta ao tamanho da tela.
- Imagens com ajuste automático para evitar distorções, utilizando a propriedade `object-fit`.
- Um cabeçalho estilizado com cores contrastantes.

### Estrutura da Galeria

A página contém um cabeçalho seguido pela galeria de fotos organizada de forma responsiva. Cada imagem tem um limite de largura e altura, mantendo a proporção original. Quando o espaço horizontal não é suficiente, as imagens são reorganizadas em novas linhas.

### Estilo

O layout da galeria foi estilizado com CSS, focando em:
- Utilização de Flexbox para organizar as imagens de forma eficiente.
- Cores contrastantes para o cabeçalho e bordas.
- Ajustes visuais para garantir que as imagens sejam exibidas corretamente sem distorção.

## Estrutura

### HTML

O arquivo HTML (`gallery.html`) contém a estrutura da página e a galeria de imagens, com as imagens sendo carregadas diretamente de URLs externas.

### CSS

O arquivo de estilos (`gallery.css`) define o layout e a aparência da galeria e do cabeçalho, utilizando as seguintes propriedades principais:
- `flexbox` para a organização dos itens da galeria.
- `gap` para espaçamento entre as imagens.
- `object-fit: cover` para garantir que as imagens preencham seus contêineres sem distorção.

## Visualização

Para ver a galeria finalizada, consulte o arquivo PDF abaixo, que contém capturas de tela do projeto:

- [Visualização da Galeria](./flexboxGallery.png)

## Notas e Estudos

Durante o desenvolvimento deste projeto, fiz diversas anotações sobre o uso de Flexbox, responsividade e organização de layout. Essas anotações estão detalhadas no arquivo:

- [Anotações da Galeria](./anotaçõesFlexboxGallery.md)

## Como Usar

1. Clone o repositório.
2. Abra o arquivo `index.html` em seu navegador.
3. A galeria será exibida automaticamente com as imagens organizadas de forma flexível.

## Tecnologias Utilizadas

- **HTML5**: Para a estrutura da galeria.
- **CSS3**: Para a estilização do layout e responsividade, com ênfase no uso de Flexbox.

