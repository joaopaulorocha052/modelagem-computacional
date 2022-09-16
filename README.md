# Modelagem Computacional
Trabalhos desenvolvidos na disciplina Modelagem Computacional da Universidade Federal de São Paulo-Campus São José dos Campos

#Descrição dos Projetos

Durante a disciplina, realizamos simulações de diversos eventos da realidade através de modelos matemáticos. A partir dos modelos matématicos que descrevem determinado fenomeno fizemos os calculos a ajustamos os parametros para que pudessemos simular sistemas complexos. Foram realizadas simulações de neurônios, propagação de doenças, sistemas ecológicos e de lancamentos.

## Tecnologias Utilizadas


<img width="60" height="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" /> <img width="60" height="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />




# Índice dos Projetos
1. [Simulação de um lançamento oblíquo](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/Projeto1_LancamentoObliquo.ipynb)
2. [Simulação do acoplamento de neurônios](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/Projeto_2.ipynb)
3. [Simulação de uma rede trófica](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/Projeto_3.ipynb)
4. [Simulação do contágio de uma doença](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/Projeto_4_(1).ipynb)
5. [Simulação do contágio utilizando o modelo SIR](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/Projeto_5.ipynb)
6. [Simulação do contágio utilizandoo modelo SIR aplicado em um grafo](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/Projeto_6%20(1).ipynb)


# Projeto 1

## Descrição
Simulação de um lancamento oblíquo de um projétil, onde alteramos parâmetros como a velocidade e massa do projétil, além da gravidade do planeta.

## Exemplo

![img](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/img/proje1.jpeg) Exemplo de lançamento



# Projeto 2

## Descrição
Simulação do acoplamento entre 500 neurônios, que comecam a sincronizar a sua pulsação com o passar do tempo. Foi utilizado o Oscilador de Van der Pol, equações que definem o comportamento uma da outra, como um laço de realimentacao entre uma variavel excitatória e uma inibitória. Assim, o comportamento delas é análogo ao funcionamento dos neurônios.

## Exemplo

![img](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/img/proje2.jpeg) Exemplo da pulsação de um neurônio



# Projeto 3

## Descrição
Simulação de uma rede tródica contendo 8 espécies de animais e produtores, utilizando o modelo Lotka-Volterra, um modelo de presa-predador, onde a população de predadores influencia a população das presas.

## Exemplo

![img](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/img/proje3.jpeg) Exemplo de uma das simulações da rede trófica




# Projeto 4

## Descrição
Simulação da propagação de uma em rede, utilizando grafos para simular uma rede de pessoas conectadas, que podem ou não transmitir e contrair a doença para seus vizinhos.

## Exemplo

![img](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/img/imagem_2022-09-15_201057118.png) Exemplo do número de infectados diário

![img](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/img/ezgif.com-gif-maker%20(1).gif) Contaminação orcorrendo em um grupo de 500 pessoas



# Projeto 5

## Descrição
Simulação da propagação de uma doença utilizando utilizando o modelo epidemiológico SIR, que descreve a transmissao de doenças em um grupo de pessoas, levando em conta a população de infectados, suscetíveis e de recuperados

## Exemplo

![img](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/img/proje5.jpeg) Exemplo de gráfico do modelo SIR



# Projeto 5

## Descrição
Simulação da propagação de uma doença utilizando utilizando o modelo epidemiológico SIR, mas agora aplicado a uma rede, que foi criada utilizando um grafo. Novamente o modelo SIR descreve a evolução da epidemia, mas agora cada nó do grafo representa uma cidade, com população propria e individuos suscetiveis, infectados e recuperados proprios. Assim, o modelo SIR é aplicado a cada cidade, que estão ligadas entre si, seguindo cidades do estado de São Paulo.

## Exemplo

![img](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/img/proje6_1.png) Grafo que representa as cidades do estado de São Paulo


![img](https://github.com/joaopaulorocha052/modelagem-computacional/blob/main/img/proje6_2.jpeg) Exemplo do grafico da evolução da epidemia na cidade de Jundiaí




