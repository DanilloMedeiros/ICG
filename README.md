# Introduçao à Computação Gráfica

*Este documento trata de expor os trabalhos referentes a disciplina de ICG ministrada na Universidade Federal da Paraíba* 

# Rasterização

Rasterizar nada mais é do que desenhar imagens na tela do computador, porém, essa representação é feita através de pixels que são pequenos
quadrados pintados na tela, usando o padrão de cor: vermelho, verde, azul e alpha.Abaixo segue uma demonstração de como ficaria
a rasterização de uma reta:

![rasterizacao](https://user-images.githubusercontent.com/40369696/44006271-ffdad556-9e57-11e8-910e-b691df793951.PNG)

# Funções

Neste primeiro momento foi pedido a implementação de três funções: PutPixel,DrawLine e DrawTriangle

# PutPixel

Função que pinta na tela um único pixel dado a posição x,y e as cores, segue o código:

![putpixel](https://user-images.githubusercontent.com/40369696/44006436-c49a6260-9e5a-11e8-9d2e-52bc4c9d448e.PNG)


É possível observar que as posições são multiplicadas por 4,isso se da porque cada pixel ocupa 4 posições na memória referentes a cada cor,alem disso para que se possa locomover a posição y de forma adequada, faz-se necessário o uso da largura da tela criada, que no caso esta em 512x512.Resultado da aplicação dessa função quando chamada 6 vezes com cores e posições diferentes:

![put_pixel](https://user-images.githubusercontent.com/40369696/44006476-8945ec56-9e5b-11e8-9bdb-14415655dbb5.PNG)



