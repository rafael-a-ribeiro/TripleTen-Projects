## Introdução <a id='intro'></a>
O trabalho de um analista é analisar dados para obter percepções valiosas dos dados e tomar decisões fundamentadas neles. Esse processo consiste em várias etapas: visão geral de dados, pré-processamento de dados e testes de hipóteses.

Sempre que fazemos uma pesquisa, precisamos formular uma hipótese que depois poderemos testar. Às vezes nós aceitamos essas hipóteses; outras vezes, nós as rejeitamos. Para tomar as decisões certas, um negócio deve ser capaz de entender se está fazendo as suposições certas ou não.

Neste projeto, você vai comparar as preferências musicais dos habitantes de Springfild e Shelbyville. Você estudará os dados de um serviço de streaming de música online para testar as hipóteses apresentadas abaixo e comparar o comportamento dos usuários para essas duas cidades.

### Objetivo:
Teste as três hipóteses:
1. A atividade do usuário varia dependendo do dia da semana e da cidade.
2. Nas segundas-feiras de manhã, os habitantes de Springfield e Shelbyville escutam diferentes gêneros. Isso também é verdadeiro para noites de sexta-feira.
3. Ouvintes de Springfield e Shelbyville têm preferências diferentes. Em Springfield, as pessoas preferem pop, enquanto Shelbyville tem mais fãs de rap.

### Etapas
Os dados sobre o comportamento dos usuários estão armazenados no arquivo `/datasets/music_project_en.csv`. Não há informação sobre a qualidade dos dados, então você precisará examiná-los antes de testar a hipótese.

Primeiro, você avaliará a qualidade dos dados e verá se seus problemas são significativos. Depois, durante o pré-processamento dos dados, você tentará tratar dos problemas mais críticos.

O seu projeto consiste em três etapas:
 1. Visão geral dos dados
 2. Pré-processamento de dados
 3. Teste das hipóteses


### Desafio

Neste projeto, preparamos um pequeno desafio para você. Incluímos uma nova estrutura de dados: timestamps. Timestamps (marcas temporais) são comumente usadas e merecem atenção especial. Mais adiante no programa, você aprenderá muito sobre elas. Mas por enquanto, vamos tratá-las como strings simples. Precisamos de marcas temporais neste projeto para testar uma das nossas hipóteses. Não se preocupe, nós te ajudaremos. Seu nível atual de conhecimento será suficiente para lidar com isso.

Por exemplo, digamos que temos duas marcas temporais: `dt1 = "12:00:00"` and `dt2 = "06:00:00"`. Queremos comparar essas duas marcas temporais e ver qual delas é mais tarde.

Podemos compará-las usando os operadores padrão de comparação (`<`, `>`, `<=`, `>=`, `==`, `!=`). Execute a célula de código abaixo para comparar as duas marcas temporais:
