# Visão geral do projeto
Você trabalha na empresa de mineração OilyGiant. Sua tarefa é encontrar os melhores lugares para o desenvolvimento de novos poços de petróleo.

Para concluir essa tarefa, você vai precisar executar as seguintes etapas:

Ler os arquivos com parâmetros coletados de poços de petróleo na região selecionada: a quantidade de petróleo e o volume de reservas;
Construir um modelo para predizer o volume de reservas em novos poços;
Escolher os poços de petróleo que têm os maiores valores estimados;
Escolher a região com o maior lucro total para os poços de petróleo selecionados.
Você tem dados sobre amostras de petróleo de três regiões. Os parâmetros de cada poço de petróleo na região já são conhecidos. Construa um modelo que te ajudará a escolher a região com a margem de lucro mais alta. Utilize a técnica de Bootstrapping para analisar lucro potencial e riscos.

# Descrição de dados
Os dados de exploração geológica para as três regiões estão armazenados em arquivos:

geo_data_0.csv. baixe o conjunto de dados
geo_data_1.csv. baixe o conjunto de dados
geo_data_2.csv. baixe o conjunto de dados
id — identificador unívoco de poço de petróleo
f0, f1, f2 — três características de pontos (seu significado específico não é importante, mas as próprias características são significativas)
product — volume de reservas no poço de petróleo (milhares de barris).
# Condições:
Apenas regressão linear deve ser usada para o treinamento do modelo.
Ao explorar a região, um estudo de 500 pontos é realizado e os melhores 200 pontos são selecionados para calcular o lucro.
O orçamento para o desenvolvimento de 200 poços de petróleo é 100 milhões de dólares.
Um barril de petróleo bruto traz 4.5 dólares de receita. A receita de uma unidade de produto é 4.500 dólares (o volume de reservas está em milhares de barris).
Depois de ter avaliado os riscos, mantenha apenas as regiões com o risco de perdas inferior a 2.5%. Entre aquelas que se enquadram no critério, você precisa selecionar a região com o lucro médio mais alto.
Os dados são sintéticos e não incluem nenhum detalhe de contratos ou características de poços.
