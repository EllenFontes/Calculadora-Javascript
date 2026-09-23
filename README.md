# 🧮 Calculadora Web

Uma aplicação de calculadora simples, elegante e responsiva construída com **HTML5**, **CSS3** e **JavaScript (ES6+)**. O projeto faz a manipulação direta do DOM para registrar teclas, formatar expressões numéricas e calcular os resultados de forma dinâmica.

---

## 📸 Demonstração

*(Adicione uma imagem ou GIF do projeto aqui)*

```
 _____________________
|  [ 12 + 5         ] |
|_____________________|
|  C  |  <  |  /  |  *  |
|  7  |  8  |  9  |  -  |
|  4  |  5  |  6  |  +  |
|  1  |  2  |  3  |  =  |
|      0    |  .  |     |
 ---------------------
```

---

## ✨ Funcionalidades

- [x] **Inserção de Dígitos e Operadores:** Adiciona números e símbolos aritméticos à tela.
- [x] **Limpeza Total (`C` / `clean`):** Reseta o visor completamente.
- [x] **Backspace (`<` / `back`):** Apaga o último caractere digitado via manipulação de string (`substring`).
- [x] **Cálculo Automático (`=` / `calcular`):** Resolve a expressão matemática visível na tela.
- [x] **Layout Responsivo:** Estilizado para ser funcional tanto em telas de computadores quanto em dispositivos móveis.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica dos botões e do visor da calculadora.
- **CSS3:** Estilização visual (Grade/Flexbox, cores, alinhamentos e efeitos nos botões).
- **JavaScript:** Lógica de manipulação do DOM e processamento das expressões matemáticas.

---

## 📂 Estrutura do Projeto

```text
├── index.html       # Estrutura principal da página
├── style.css        # Estilização visual da calculadora
└── script.js        # Lógica das funções de cálculo e manipulação do visor
```

---

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd nome-do-repositorio
   ```

3. **Abra o projeto:**
   - Basta dar um duplo clique no arquivo `index.html` para abrir diretamente no seu navegador, **ou**
   - Use a extensão *Live Server* no VS Code para rodar um servidor local.

---

## 💡 Como Funciona a Lógica (JS)

- **`insert(num)`**: Recupera o conteúdo atual do visor via `.innerHTML` e concatena o novo caractere pressionado.
- **`clean()`**: Define o `.innerHTML` do visor como vazio.
- **`back()`**: Utiliza `.substring(0, resultado.length - 1)` para fatiar o texto atual do visor, removendo o último caractere.
- **`calcular()`**: Avalia a expressão matemática construída no visor para exibir o resultado numérico final.

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE). Veja o arquivo de licença para mais detalhes.

---
