Esse repositório implementa um modelo Transformer com TensorFlow para tradução.

## Pontos Positivos (Vantagens do Transformer) 

1. Modelos podem ser pré-treinados em grandes quantidades de texto e adaptados para tarefas específicas (tradução, resumo, resposta a perguntas etc.). Isso reduz a necessidade de treinar um modelo do zero.  

2. O TensorFlow disponibiliza ferramnetas especializados, como o TensorFlow Text usado no tutorial, que simplifica a implementação de modelos Transformer em tarefas de processamento de linguagem natural.

3. Cada cabeça de atenção aprende diferentes representações da frase, permitindo que o modelo capture nuances do significado, contexto e até estrutura gramatical.

## Pontos Negativos (Desafios e Limitações do Transformer)  

1. CPU vs GPU
   - O modelo exige muita memória e poder computacional, especialmente em grandes conjuntos de dados.
   - Ele atingiu o limite de RAM com CPU. GPUs são praticamente indispensáveis.

2. Precisam de muito texto para treinar. Se os dados forem limitados, o modelo pode não generalizar bem.  

3. Modelos muito grandes podem ser lentos na inferência, especialmente em aplicações que exigem respostas rápidas, como assistentes virtuais ou chatbots.
