### Unidade `vh`

- A unidade `vh` significa **altura da janela de visualização**.
- 1 `vh` é equivalente a **1% da altura da janela de visualização**.
- Isso torna essa unidade **relativa à altura da janela**.

---

### Melhorando o projeto com CSS

- Aplique ao `body` uma largura (`width`) de **100%** e uma altura (`height`) de **100vh**:
  
  ```css
  body {
    width: 100%;
    height: 100vh;
  }
  ```

---

### Input de Envio (submit)

- O primeiro elemento `input` do tipo `submit` **envia automaticamente** o formulário (`form`) pai mais próximo.
- Para adicionar um botão de envio ao final de um formulário, use:

  ```html
  <input type="submit" value="Submit">
  ```

---

### Upload de Foto de Perfil

- Para permitir que um usuário faça o **upload de uma foto de perfil**, use um `input` do tipo `file`.
- Exemplo:

  ```html
  <fieldset>
    <label>Upload a profile picture: <input type="file"></label>
  </fieldset>
  ```

---

### Elemento `textarea`

- O elemento `textarea` é similar a um `input` do tipo `text`, mas permite **várias linhas de texto**.
- Para adicionar um campo de biografia em um formulário, use o `textarea` com um `label`:

  ```html
  <fieldset>
    <label>Provide a bio: <textarea></textarea></label>
  </fieldset>
  ```

  > Lembre-se de que o `textarea` precisa de uma **tag de fechamento**.

---

### Estilizando o último `fieldset`

- Para remover a borda inferior do último `fieldset`, use o seletor CSS `last-of-type`:

  ```css
  fieldset:last-of-type {
    border-bottom: none;
  }
  ```

---

### Estilizando o Botão de Envio

- Para estilizar um botão de envio (`submit`), você pode usar um **seletor de atributo**. Por exemplo:

  ```css
  input[type="submit"] {
    display: block;
    width: 60%;
  }
  ```

---
