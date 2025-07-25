# Lista de Exercícios 3 - Desenvolvimento Web Básico

Este repositório contém os arquivos de uma lista de exercícios práticos focada nos fundamentos do desenvolvimento web, cobrindo desde a estrutura semântica com HTML até a estilização e interatividade com CSS e JavaScript.

## 🚀 Exercícios Incluídos

O projeto é dividido em múltiplos arquivos `.html`, cada um correspondendo a um exercício específico da lista:

1.  **`index.html`**: Estrutura semântica de uma página, utilizando `header`, `main`, `section` e `footer`, com estilização básica de cores e box model aplicada através do `style.css`.
2.  **`lista.html`**: Demonstração do uso de listas ordenadas (`<ol>`) e não ordenadas (`<ul>`) e de um bloco de navegação (`<nav>`) com links externos.
3.  **`feedback.html`**: Construção de um formulário de feedback completo, utilizando diversos tipos de campos (`input`, `textarea`) e um botão de envio.
4.  **`grid-imagem.html`**: Uma galeria de imagens responsiva, organizada com CSS Grid e centralizada na página com Flexbox.
5.  **`menuHamburger.html`**: Implementação de um menu "hambúrguer" que aparece em telas menores (≤ 600px) e controla a exibição da navegação principal através de JavaScript.

## 🛠️ Como Rodar o Projeto

Todos os exercícios são compostos por arquivos estáticos (HTML, CSS e JavaScript). Portanto, **não é necessária a instalação de nenhum servidor ou dependência**.

Para visualizar qualquer um dos exercícios, siga estes passos simples:

1.  **Clone ou Baixe o Repositório**
    Se você estiver usando Git, clone o repositório:

    ```bash
    git clone https://github.com/williamjmrosa/lista-de-exercicios-3-maisprati.git
    ```

    Caso contrário, apenas faça o download dos arquivos em formato ZIP e extraia-os em uma pasta no seu computador.

2.  **Navegue até a Pasta do Projeto**
    Use o explorador de arquivos do seu sistema operacional para entrar na pasta onde você salvou os arquivos do projeto.

3.  **Abra o Arquivo HTML Desejado**
    Dê um duplo clique em qualquer um dos arquivos `.html` (por exemplo, `index.html`, `grid-imagem.html`, etc.). O arquivo será aberto diretamente no seu navegador padrão (Google Chrome, Firefox, etc.) e você poderá ver o resultado do exercício.

## 💻 Tecnologias Utilizadas

  * **HTML5**: Para a estrutura e semântica de todas as páginas.
  * **CSS3**: Para estilização, layout (Flexbox e Grid), responsividade (`@media queries`) e efeitos visuais.
  * **JavaScript**: Para a funcionalidade do menu hambúrguer e do modal na página principal.

  ## 📂 Estrutura de Diretórios

O projeto está organizado da seguinte forma para manter os arquivos bem estruturados:

```
/
├── index.html              # Exercício 1: Estrutura e CSS Básico
├── lista.html              # Exercício 2: Listas e Navegação
├── feedback.html           # Exercício 3: Formulário de Feedback
├── grid-imagem.html        # Exercício 6: Galeria com Grid e Flexbox
├── menuHamburger.html      # Exercício 7: Menu Hambúrguer
├── style.css               # Folha de estilos principal para o index.html
│
└─── img/                   # Pasta contendo todas as imagens da galeria
│    ├── marvel-01.jpg
│    ├── marvel-02.jpg
│    └── ... (e as outras imagens)
│
└─── .vscode/               # Pasta de configuração do Visual Studio Code
     └── settings.json
```