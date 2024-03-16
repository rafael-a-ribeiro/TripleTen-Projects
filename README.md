# Descrição do projeto
Os dados são armazenados em três arquivos:

gold_recovery_train.csv — download do conjunto de dados de treinamento
gold_recovery_test.csv — download do conjunto de dados de teste
gold_recovery_full.csv — download do conjunto de dados fonte
Os dados são indexados com a data e hora da aquisição (característica data). Os parâmetros que estão próximos uns dos outros em termos de tempo geralmente são semelhantes.

Alguns parâmetros não estão disponíveis porque foram medidos e/ou calculados muito mais tarde. Por isso, algumas das características presentes no conjunto de treinamento podem estar ausentes do conjunto de teste. O conjunto de teste também não contém objetivos.

O conjunto de dados de origem contém os conjuntos de treinamento e teste com todas as características.

Você tem os dados brutos, recebidos diretamente do cliente. Antes de construir o modelo, verifique a exatidão dos dados.
