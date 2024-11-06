Escalação de Time

Este é um projeto simples de front-end que permite adicionar e remover jogadores em uma lista de escalação de time, utilizando HTML, CSS e JavaScript.
Funcionalidades

    Escalar Jogador: Adiciona um jogador à escalação, especificando sua posição, nome e número.
    Remover Jogador: Remove um jogador da escalação usando seu número.

Como Usar

    Insira a Posição, Nome e Número do jogador que deseja escalar nos campos apropriados.
    Clique no botão Escalar para adicionar o jogador à lista.
    Para remover um jogador, insira o Número do jogador e clique em Remover.

Estrutura do Projeto

O projeto é composto por dois arquivos principais:

    index.html: Contém a estrutura da página com campos de entrada para adicionar e remover jogadores.
    index.js: Contém as funções JavaScript para adicionar e remover jogadores na escalação.

Código JavaScript

    addPlayer(): Adiciona um novo jogador à lista após confirmação, limpando os campos de entrada.
    removePlayer(): Remove o jogador com o número especificado após confirmação.

Exemplos de Uso

html

<!-- Adicionando um novo jogador -->
<h2>Escalar Jogador</h2>
<input type="text" id="position" placeholder="Posição">
<input type="text" id="name" placeholder="Nome">
<input type="text" id="number" placeholder="Número">
<button onclick="addPlayer()">Escalar</button>

<!-- Removendo um jogador -->
<h2>Remover Jogador</h2>
<input type="text" id="numberToRemove" placeholder="Número">
<button onclick="removePlayer()">Remover</button>

Observações

Certifique-se de preencher todos os campos antes de escalar um jogador. Cada número de jogador deve ser único para evitar conflitos na escalação.
