# Geladeira com Placa Peltier

Projeto final da disciplina de sistemas digitais III do curso técnico em eletrônica do CEFET-MG feito em um grupo de 2 estudantes.

A ideia era montar um modelo de geladeira utilizando, ao invés de um compressor, uma simples placa peltier, pois, o intuito não era de fato ter algo para refrigerar 
alimentos, e sim aprender um pouco de eletrônica e programação. O sistema foi feito utilizando um modelo de microcontrolador da Texas Instruments, o
MSP430G2553. A IDE utilizada foi o IAR Workbench e a linguagem de programação era C, utilizando apenas a biblioteca padrão do MSP430, todas as outras bibliotecas (para o teclado, display, etc.) foram implementadas por nós.

A geladeira conta com:
  1. Um teclado numérico para setar a temperatura e fazer outras configurações
  2. Um display para mostrar dados importantes ao usuário
  3. Timer interno do microcontrolador programado para implementar funções de relógio/temporização
  4. Sistema de controle de temperatura da geladeira usando o módulo ADC do MSP
  5. Possibilidade de trabalhar com célcius e fahrenheits
 
O relatório final do projeto com mais especificações sobre o mesmo está na pasta do projeto.

Este foi um dos primeiros projetos que fiz utilizando programação. Algumas soluções para determinados 
problemas não são as mais adequadas, porém, decidi colocá-lo no github para ter como recordação e para, talvez, ajudar alguém que esteja fazendo um projeto similar. 
Apesar dos pesares, foi um projeto no qual nos dedicamos bastante, fizemos com bastante carinho e nos sentimos muito realizado ao vê-lo funcionando. 

Nota final dada pelo professor: 9.9/10 - Ao se aproximar da temperatura desejada, algumas raras vezes os relés ficavam chaveando rapidamente. Fora isso, tudo
funcionou conforme era esperado
