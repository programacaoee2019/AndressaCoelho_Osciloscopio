# AndressaCoelho_Osciloscopio
# Osciloscópio

Conceito: osciloscópio com gerador de sinais integrado.

Motivação: Como o osciloscópio foi um dos instrumentos mais  utilizados por nós nos laboratórios de eletrônica e de circuitos elétricos, criá-lo em LabView seria mais conveniente para o engenheiro eletricista, pois seria a adaptação de suas funcionalidades em um só hardware.

Funcionalidade: o osciloscópio vai receber até duas entradas de dados, exibir esses sinais recebidos em um gráfico tensão por tempo em um display. Será possível somar ou subtrair os sinais recebidos e ver qual o Vpp e o RMS de cada canal e do canal representado pela função Math e também escolher os parâmetros dos sinais a serem enviados para cada canal. Além disso, haverá um outro display gráfico para plotar os canais 1 e 2 nos eixos XY. 

# Interface gráfica

![github-small](https://user-images.githubusercontent.com/48967416/60466784-06049080-9c2b-11e9-957e-c0bf315e268f.png)

Legenda da interface:

![github-small](https://user-images.githubusercontent.com/48967416/60467287-a0190880-9c2c-11e9-9abf-aa8f70ea013e.png)


A - Botão de ligar e desligar cada canal;

B - Cor de cada canal no gráfico;

C - Valor da amplitude máxima de pico a pica medida para cada canal ligado; 

D - Valor RMS medido para cada canal ligado;

E - Escolha da fase desejada para gerar o sinal de cada canal ligado;

F - Escolha da amplitude desejada para gerar o sinal de cada canal ligado;

G - Escolha do offset desejado para gerar o sinal de cada canal ligado;

H - Escolha da frequência desejada para gerar o sinal de cada canal ligado;

I - Função Math ligada para realizar operações entre os canais 1 e 2;

J - Escolha da operação desejada para a função Math executar entre os canais 1 e 2;

K - Botão de ligar ou desligar o gráfico que apresenta o canal 1 no eixo x e o canal 2 no eixo y;

L - Gráfico que mostra os canais 1 e 2 e a função Math quando ligados;

M - Gráfico que mostra os canais 1 e 2 plotados nos eixos XY.

# Código

Alguns screenshots do código. OBS.: Os canais 1 e 2 tem códigos análogos.

![github-small](https://user-images.githubusercontent.com/48967416/60468162-26cee500-9c2f-11e9-9671-145a3c3be4e7.png)

![github-small](https://user-images.githubusercontent.com/48967416/60468796-29323e80-9c31-11e9-98fb-2dccf9d88191.png)

![github-small](https://user-images.githubusercontent.com/48967416/60468940-8cbc6c00-9c31-11e9-9189-a7550dec9a46.png)

# Fluxograma 

![github-small](https://user-images.githubusercontent.com/48967416/60472925-3d7e3780-9c41-11e9-8401-245362c96473.png)

