# Ponderada de Programação - Tradutor

Essa ponderada seguiu o seguinte tutorial: https://www.tensorflow.org/text/tutorials/transformer?hl=pt-br#run_inference

Ele tem como objetivo treinar um modelo Transformer para traduzir um conjunto de dados de português para inglês. O principal ponto do transformer é a ideia de autoatenção, que consiste na capacidade de atender a diferentes posições de sequência de entrada para calcular uma representação dessa sequência.

## Principais Pontos

### Pontos Positivos

- 1. Processo de Inferência rápido.


### Pontos Negativos

- 1. Dificuldade de traduzir com precisão frases que já contenham palavras em inglês, que são comumentes utilizadas, por exemplo: notebook, smartphone, frontend, backend e etc.

![ingles-portugues](/img/exemplo1.png)

**Tradução correta**: Let's focus on the Backend, while they focus on the frontend

**Resposta do Transformer**: let ' s focus on bacin , as they focus on the frodinand .

- 2. Para realizar o treinamento do Modelo utilizando CPU, demorou cerca de 4 Horask 1 minuto e 27 segundos

![ingles-portugues](/img/duracao.png)


- 3. Tradução incorreta. Talvez o dataset utilizado para treinar o modelo não seja suficientimente grande.
![ingles-portugues](/img/exemplo2.png)
