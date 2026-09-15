# TC-001 — Validação do sistema de três chaves

**Tipo:** Caso de teste simulado
**Jogo de referência:** Minecraft Bedrock
**Mecânica:** Sistema de progressão por chaves

## Objetivo

Verificar se a porta responde corretamente de acordo com a quantidade de chaves obtidas pelo jogador.

## Pré-condições

* Jogador começa sem nenhuma chave.
* Porta inicialmente fechada.
* Existem três chaves disponíveis no mapa.

## Cenário 1 — Nenhuma chave

### Passos

1. Ir diretamente até a porta.
2. Tentar interagir com ela.

### Resultado esperado

A porta deve permanecer fechada.

---

## Cenário 2 — Apenas uma chave

### Passos

1. Obter uma chave.
2. Retornar até a porta.
3. Tentar abrir a porta.
---
OBS: testar cada chave diferente caso as chaves sejam diferentes.

### Resultado esperado

A porta deve permanecer fechada.

---

## Cenário 3 — Duas chaves

### Passos

1. Obter duas das três chaves.
2. Retornar até a porta.
3. Tentar abrir a porta.

---
OBS: testar as 3 combinações de chaves em caso de serem chaves diferentes.

### Resultado esperado

A porta deve permanecer fechada.

---

## Cenário 4 — Três chaves

### Passos

1. Obter todas as três chaves.
2. Retornar até a porta.
3. Interagir com ela.

### Resultado esperado

A porta deve abrir e permitir que o jogador continue o mapa.

---

## Cenário 5 — Ordem diferente de coleta

### Passos

1. Reiniciar o teste.
2. Coletar as três chaves em uma ordem diferente.
3. Retornar até a porta.
4. Tentar abri-la.

### Resultado esperado

A ordem de coleta não deve impedir a abertura da porta, exceto caso exista uma ordem definida pelas regras do mapa.

---

## Cenário 6 - Revisar Cenário
Esse cenário só será feito caso de suspeita de blocos do cenário não agirem de forma esperada no mapa.

### Passos

1. Verificar se possui alguma interação inesperado entre os blocos
2. Verificar se possível a mesma porta em outro mapa [super plano], ou em uma parte isolada do mapa.
3. No modo espectador verificar entre os blocos se não possui um bloco fora de posição.

### Resultado esperado

Os blocos não deveriam atrapalhar na interação do jogador com a porta.

--- 

## Cenário 7 — Reiniciar o mundo

### Passos

1. Obter as três chaves.
2. Salvar e sair do mundo.
3. Entrar novamente.
4. Retornar até a porta.
5. Tentar abri-la.

### Resultado esperado

O progresso relacionado às chaves deve ser mantido conforme as regras definidas pelo mapa.

---

## Informações a registrar

Durante os testes, registrar:

* cenário executado;
* resultado esperado;
* resultado obtido;
* aprovado ou reprovado;
* versão do jogo;
* plataforma;
* evidências quando houver falha.
