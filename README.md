# CovidAI

Autor: Maurício Jornada Bastos

Trabalho desenvolvido na disciplina de Inteligência Artificial do curso de Engenharia de Computação da UFMS em junho de 2021.

Proposta do trabalho:

O objetivo deste trabalho é treinar redes convolucionais para classificar imagens de raio-x de torax de pulmão em Covid, normal, lung_opacity e viral_pneumonia.

Tarefa 1 - Coleta de dados:

O conjunto de dados está disponível no kaggle em

https://www.kaggle.com/tawsifurrahman/covid19-radiography-database

Para fazer download das imagens, siga as instruções descritas em

https://www.kaggle.com/general/74235

A criação do token de acesso acesse

https://www.kaggle.com/<NOME_USARIO>/account

você deverá utilizar a sua conta institucional (acesso via passaporte UFMS) no google, devido ao tamanho do conjunto que é de aproximadamente 800mb.
Na conta institucional acessado pelo seu passaporte UFMS você não deverá ter problemas de espaço.

Tarefa 2 - Adaptação dos modelos para realizar ajuste fino. Você deverá adaptar os modelos resnet18 ,mobilenet_v3_small e shufflenet_v2_x0_5
que estão disponíveis em torchvision.models.

Tarefa 3 - Treinamento

Você deverá dividir o conjunto em treino, validação e teste e avaliar o desempenho dos três modelos. Sempre treinando com conjunto de treinamento, 
ajustando parâmetros com validação e avaliando o modelo treinado com teste.

Tarefa 4 - Resultados

Você deverá gerar a matriz de confusão com o sklearn, juntamente com a accuracy, precision, recall e f1 para cada algoritmo.
Além disso você deverá gerar dois gráficos: um mostrando a taxa de acerto por cada epoch e outra mostrando a loss de cada epoch.

