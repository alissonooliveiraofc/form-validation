# 📋 Formulário de Cadastro com Validação em Vanilla JS

[![Projeto no Ar](https://img.shields.io/badge/🚀_Acessar_Projeto_no_Ar-00DBDE?style=for-the-badge&logoColor=white)](https://alissonooliveiraofc.github.io/form-validation)

> 🔗 **Link do Projeto:** [alissonooliveiraofc.github.io/form-validation](https://alissonooliveiraofc.github.io/form-validation)

---

## 💻 Sobre o Projeto

Este é um projeto de formulário interativo de criação de conta desenvolvido com HTML5, CSS3 e JavaScript puro (Vanilla JS). O foco principal da aplicação é fornecer **feedback visual dinâmico em tempo real** e **validação de dados no lado do cliente (Client-Side Validation)** antes do envio do formulário.

A interface conta com um design moderno com degradê, tipografia limpa (Poppins) e estados visuais bem definidos para indicar sucesso ou erro em cada campo.

---

## 🚀 Funcionalidades

- **Interceção do Envio:** Bloqueio do comportamento padrão do navegador (`event.preventDefault()`) para processamento das validações.
- **Validação de Campos Obrigatórios:** Checagem de preenchimento para Usuário, Email, Senha e Confirmação de Senha.
- **Validação de Formato de Email:** Utilização de Expressão Regular (Regex) para garantir a estrutura do email inserido.
- **Regras de Senha:** Checagem de comprimento mínimo (mínimo de 7 caracteres) e verificação de igualdade entre a senha e a confirmação.
- **Feedback Visual Dinâmico:**
  - Alteração de bordas dos campos (`#2ecc71` para sucesso e `#e74c3c` para erro).
  - Exibição contextualizada de mensagens de erro abaixo do campo afetado.
  - Alternância de ícones de status via FontAwesome (`check-circle` e `exclamation-circle`).
- **Validação de Estado Global:** Verificação final utilizando o método de array `.every()` antes de liberar o envio do formulário.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica e acessível.
- **CSS3:** 
  - Layout flexível com Flexbox.
  - Estilização de estados dinâmicos com classes `.success` e `.error`.
  - Posicionamento absoluto de ícones e mensagens de erro.
  - Google Fonts (Poppins).
- **JavaScript (ES6+):**
  - Manipulação direta da DOM (`getElementById`, `querySelectorAll`, `querySelector`).
  - Expressões Regulares (Regex).
  - Métodos modernos de Array (`Array.from`, `.every()`).
- **FontAwesome:** Ícones vetoriais de sinalização visual.

---

## 📁 Estrutura de Arquivos

```text
├── index.html        # Estrutura e marcação semântica da página
├── styles.css        # Estilização, layout e regras de estado (success/error)
├── main.js          # Lógica de validação e manipulação do DOM
└── README.md         # Documentação do projeto
