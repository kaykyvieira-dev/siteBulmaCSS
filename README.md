# 🚀 Tutorial Prático: Bulma CSS

Projeto da disciplina de **Frameworks**.

O objetivo deste projeto é demonstrar, na prática e através de comparações diretas com o Bootstrap, como o **Bulma CSS** resolve os desafios comuns de construção de interfaces web modernas e responsivas.

---

## 📌 Sobre o Bulma CSS

O **Bulma** é um framework CSS open-source baseado em **Flexbox**. Suas principais características são:

* **100% CSS Puro:** Não possui dependência nativa de JavaScript, permitindo total controle da lógica de scripts pela equipa de desenvolvimento.
* **Sintaxe Intuitiva:** Utiliza modificadores com numeração e prefixos claros como `is-` (ex: `is-primary`, `is-fullwidth`) e `has-` (ex: `has-text-centered`).
* **Layouts Flexíveis:** Sistema de colunas responsivo e dinâmico sobre a estrutura `columns` e `column`.
* **Integração Aberta:** Por não possuir biblioteca de ícones própria, conecta-se perfeitamente a bibliotecas externas como **Bootstrap Icons** e **FontAwesome**.

---

## 💻 Funcionalidades e Componentes Demonstrados

A página interativa (`index.html`) apresenta os seguintes recursos:

1. **Navbar Responsiva Fixa:** Menu superior com estado colapsável para dispositivos móveis.
2. **Barra de Progresso & Scrollspy:** Indicador de leitura dinâmico vinculado ao deslocamento da página via JavaScript.
3. **Hero Section:** Cabeçalho de apresentação principal em bloco destacado.
4. **Sistema de Layout & Cards:** Comparação de sintaxe e exibição de componentes de notificação sem dependência de scripts.
5. **Formulários e Tabelas:** Validação visual de campos com ícones e tabela de dados com linhas alternadas (`is-striped`) e destaque ao passar o rato (`is-hoverable`).
6. **Objeto de Mídia (Media Object):** Estrutura alinhada com avatar e ações sociais.
7. **Componente Modal:** Janela sobreposta interativa ativada por alternância da classe `.is-active`.

---

## ⚖️ Comparativo: Bulma vs Bootstrap

| Recurso / Conceito | Bootstrap | Bulma |
| :--- | :--- | :--- |
| **Botão Principal** | `btn btn-primary` | `button is-primary` |
| **Sistema de Grid** | `.row` + `.col-md-6` | `.columns` + `.column.is-6` |
| **Biblioteca de Ícones** | Bootstrap Icons (Oficial) | Requer biblioteca externa (ex: Bootstrap Icons) |
| **JavaScript Integrado** | Sim (`bootstrap.bundle.min.js`) | **Não** (100% CSS puro) |
| **Modificadores de Estilo**| Classes prefixadas com hífens | Classes com prefixos `is-` e `has-` |

---

## 🛠️ Tecnologias Utilizadas

* **HTML5**
* **Bulma CSS** (v0.9.4 via CDN)
* **Bootstrap Icons** (v1.11.3 via CDN)
* **JavaScript** (Vanilla JS para Scrollspy e acionamento do Modal)

---

## 📂 Como Executar o Projeto

Como o projeto utiliza distribuição por CDN (sem necessidade de bundlers ou instalação via Node.js/NPM), o processo de execução é muito simples:

1. Clone ou descarregue este repositório.
2. Abra o ficheiro `index.html` diretamente em qualquer navegador moderno.
