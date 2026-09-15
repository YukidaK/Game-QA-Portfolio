# BUG-001 — Porta permanece fechada após obter três chaves

**Tipo:** Caso simulado
**Jogo de referência:** Minecraft Bedrock
**Categoria:** Gameplay / Progressão
**Status:** Em investigação

## Descrição

Após o jogador obter as três chaves necessárias para abrir uma determinada porta, a porta permanece fechada e impede a progressão normal do mapa.

## Pré-condições

* Jogador possui acesso à área das três chaves.
* A porta está inicialmente fechada.
* O jogador ainda não concluiu o objetivo relacionado às chaves.

## Passos para reprodução

1. Iniciar o mapa.
2. Obter a primeira chave.
3. Obter a segunda chave.
4. Obter a terceira chave.
5. Retornar até a porta que exige as três chaves.
6. Tentar interagir com a porta.

## Resultado esperado

Após o jogador possuir as três chaves, a porta deve reconhecer que os requisitos foram cumpridos e permitir a progressão.

## Resultado obtido

A porta permanece fechada mesmo após a obtenção das três chaves.

## Impacto

Caso a porta seja obrigatória para continuar o mapa, o problema impede a progressão do jogador.

## Investigação

Listando do que fazer para tentar identificar em quais condições o problema acontece:

* verificar se todas as três chaves foram registradas corretamente;
* obter novamente uma das chaves, caso seja possível;
* testar diferentes ordens de coleta;
* verificar se existe uma interação adicional necessária com a porta;
* verificar se a porta realmente permanece fechada ou se existe apenas uma falha visual ou de animação;
* sair e entrar novamente no mundo;
* morrer e retornar à área, quando aplicável;
* repetir o teste utilizando o modo criativo para acelerar a reprodução do cenário;
* testar novamente a mecânica a partir de um novo jogo ou cópia limpa do mapa.

## Frequência

Ainda não determinada.

Seria necessário repetir o cenário algumas vezes para verificar se o problema ocorre sempre ou apenas sob determinadas condições.

## Severidade sugerida

**Alta**, caso o problema impeça completamente a progressão do mapa.
  - Sujeito a mudança de classificação dependendo se há existência de outras formas de progredir o jogo.

## Evidências

Caso o problema fosse encontrado durante um teste real, seriam anexados:

* vídeo demonstrando os passos até o erro;
* screenshots;
* versão do Minecraft Bedrock;
* plataforma utilizada;
* informações adicionais necessárias para reprodução.
