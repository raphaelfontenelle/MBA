# MBA PUC-RS 

Este é um repositório dos notebooks e programas utilizado no meu MBA em Tecnologia para Negócios: AI, Data Science e Big Data


# Arquivos

## Espetograma
[SpectogramasMFCCs.ipynb](https://github.com/raphaelfontenelle/MBA/blob/main/SpectogramasMFCCs.ipynb "SpectogramasMFCCs.ipynb") - É um notebook que gera o espectogram de um som produzido. O espectograma é utilizado para que a rede neural convolucional CNN reconheça o som. O notebook está escrito em Python 3.

## Treinamento do Modelo
[PretrainedModel.ipynb](https://github.com/raphaelfontenelle/MBA/blob/main/PretrainedModel.ipynb "PretrainedModel.ipynb") - É um notebook utilizado para treinar a rede neural e gerar os pesos da rede para ser importado no micro controlador. O notebook está escrito em Python 3.

## Treinamento do Modelo com Palavras Customizadas

[4-6-8-CustomDatasetKWSModel.ipynb](https://github.com/raphaelfontenelle/MBA/blob/main/4-6-8-CustomDatasetKWSModel.ipynb "4-6-8-CustomDatasetKWSModel.ipynb") - É um notebook utilizado para treinar o modelo utilizando suas próprias palavras chave. Como o dataset está em inglês esse notebook é útil porque permite que se criem entradas de palavras em português no dataset. Nesse notebook ele aceita a entrada de arquivos gerado pelo site: https://tinymlx.org/open_speech_recording/ e são necessários em torno de 90 gravações para que o modelo reconheça de forma satisfatória a nova palavra adicionada. O notebook está escrito em Python 3.

## Código em C++ do Arduino para acionamento por voz. 

[Arduino](https://github.com/raphaelfontenelle/MBA/tree/main/Arduino "Arduino") - É um repositório do código fonte utilizado para programar o arduino. Ele consiste em um programa **KWS** de ativação do micro controlador por uma palavra chave. O objetivo é a substituição dos botões por comandos de voz. Ele é escrito em C++.