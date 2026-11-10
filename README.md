# Aprendizado por Reforço: dos Fundamentos à Abstração Temporal

Material do minicurso de Aprendizado por Reforço oferecido na [ERAMIA-RS 2026](https://eramia-rs.sbc.org.br/2026/).

> O aprendizado por reforço é um paradigma de aprendizado de máquina no qual agentes aprendem a tomar decisões por meio da interação com um ambiente, buscando maximizar recompensas acumuladas ao longo do tempo. Suas aplicações incluem robótica, jogos, LLMs, sistemas autônomos e otimização de processos. Neste tutorial, estudamos os fundamentos do aprendizado por reforço — da formalização por processos de decisão de Markov a algoritmos clássicos de aprendizado por diferença temporal — e introduzimos a abstração temporal por meio de *options*, que representam comportamentos temporalmente estendidos.

## Material

O minicurso é acompanhado por um notebook interativo, com explicações, exercícios e experimentos práticos:

- [Abrir o notebook no Google Colab](https://colab.research.google.com/github/ramos-ai/minicurso-eramia-rs-2026/blob/main/notebook_pr%C3%A1tica_RL.ipynb)
- [Ver o notebook no GitHub](https://github.com/ramos-ai/minicurso-eramia-rs-2026/blob/main/notebook_pr%C3%A1tica_RL.ipynb)

O notebook aborda, entre outros tópicos:

1. Processos de decisão de Markov (MDPs), retorno, fator de desconto, políticas e funções de valor.
2. Exploração ε-greedy, SARSA e Q-learning.
3. Experimentos com os ambientes Decision 1D, Cliff Walking, FrozenLake e Taxi, incluindo comparação e avaliação das políticas aprendidas.
4. Aprendizado por reforço hierárquico e abstração temporal com *options*, usando o ambiente Four Rooms e o algoritmo Option-Critic.

## Como executar

A forma mais simples de executar o material é abrir o notebook no Google Colab pelo link acima. Também é possível baixá-lo e executá-lo em um ambiente Jupyter com Python e acesso à internet. O próprio notebook instala as dependências usadas nos experimentos, incluindo Gymnasium, NumPy, Matplotlib e imageio.

Execute as células em ordem. Algumas células treinam agentes e podem levar alguns minutos para terminar; o tempo depende do ambiente de execução.

## Pré-requisitos

- Conhecimentos básicos de programação em Python.
- Conhecimentos introdutórios de aprendizado de máquina.
- Notebook próprio com acesso à internet (desejável).

## Ministrantes

- [Prof. Gabriel de Oliveira Ramos](https://br.linkedin.com/pub/gabriel-de-oliveira-ramos/24/b62/248/)
- [Arturo de Souza](https://www.linkedin.com/in/arturo-de-souza-a48529176/)
- [Augusto Antônio Fontanive Leal](https://www.linkedin.com/in/augustoafleal/)

## Evento

[ERAMIA-RS 2026](https://eramia-rs.sbc.org.br/2026/)
