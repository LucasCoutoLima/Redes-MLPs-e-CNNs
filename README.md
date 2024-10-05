# Redes Neurais: MLPs e CNNs
Esse projeto foi feito para a disciplina de mestrado da Unicamp IA048 - Aprendizado de Máquina.

Neste projeto, foi abordado o problema de reconhecimento de células sanguíneas periféricas utilizando a base de dados BloodMNIST, a qual possui 17.092 imagens microscópicas coloridas (3 canais de cor)

![Screenshot_1](https://github.com/user-attachments/assets/34b666d5-189b-4e71-9c29-f012ad9ceaa3)

O mapeamento entre os identificadores das classes e os rótulos é dado na tabela abaixo:

| Id | Rótulo |
-----|---------
| 0 | Basófilos |
| 1 | Eosinófilos |
| 2 | Eritroblastos |
| 3 | Granulócitos imaturos|
|4| Linfócitos|
|5|Monócitos|
|6|Neutrófilos|
|7|Plaquetas|

As análises realizadas foram:

(a) Aplique uma rede MLP com uma camada intermediária e analise (1) a acurácia e (2) a matriz de confusão para
os dados de teste obtidas pela melhor versão desta rede. Descreva a metodologia e a arquitetura empregada,
bem como todas as escolhas feitas.


(b) Monte uma CNN simples contendo: (i) uma camada convolucional com função de ativação não-linear; (ii)
uma camada de pooling; (iii) uma camada de saída do tipo softmax. Avalie a progressão da acurácia junto
aos dados de validação em função:
• Da quantidade de kernels utilizados na camada convolucional;
• Do tamanho do kernel de convolução.

(c) Escolhendo, então, a melhor configuração para a CNN simples, refaça o treinamento do modelo e apresente:
• A matriz de confusão para os dados de teste;
• A acurácia global;
• Cinco padrões de teste que foram classificados incorretamente, indicando a classe esperada e as probabilidades
estimadas pela rede.

(d) Explore, agora, uma CNN um pouco mais profunda. Descreva a arquitetura utilizada e apresente os mesmos
resultados solicitados no item (c) para o conjunto de teste. Por fim, façaa uma breve comparação entre
os modelos estudados neste exercício. Observação: pode ser interessante explorar ideias ou elementos
característicos de algumas CNNs famosas (como as ResNets ou as DenseNets).
