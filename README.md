# Biblioteca Digital UniFECAF

Projeto acadêmico da disciplina Design Web, criado a partir do protótipo de baixa fidelidade fornecido no enunciado. A página mantém a sequência: navegação, apresentação, destaques, livros, serviços e contatos.

## Como abrir

Abra `index.html` em um navegador. Não há instalação, dependências ou JavaScript. Para publicar em GitHub Pages, use a raiz do repositório como origem.

## Estrutura

- `index.html`: conteúdo e estrutura semântica.
- `css/style.css`: identidade visual e regras responsivas.
- `assets/imagens/hero-biblioteca.svg`: ilustração vetorial original, incluída localmente.

## Escopo e limites

Esta interface é uma demonstração de Design Web, não um catálogo institucional. Os seis livros são exemplos visuais; sua disponibilidade na UniFECAF não foi confirmada. Os três blocos de serviços remetem à página oficial da biblioteca. O site não coleta dados, não requer login e não reproduz sistemas internos da instituição.

## Decisões de implementação

HTML semântico, links de navegação por âncora, cartões de livros com `details` e `summary` nativos, texto alternativo na ilustração, link para pular conteúdo, foco visível e suporte a preferência de movimento reduzido. O CSS usa grades que passam de duas ou três colunas para uma em telas menores. As cores azul e verde foram escolhidas como referência visual à identidade da UniFECAF, sem afirmar que os códigos hexadecimais sejam valores oficiais da marca.

## Fontes

- [Biblioteca UniFECAF](https://www.unifecaf.com.br/biblioteca), usada para identificar os tipos de serviço apresentados.
- Protótipo e instruções do documento `TRABALHO - Design Web (1) (1).docx`, fornecido pelo estudante. O documento original não está incluído no projeto.

