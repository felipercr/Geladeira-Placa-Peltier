# Geladeira com Placa Peltier

Projeto final da disciplina de sistemas digitais III do curso técnico em eletrônica do CEFET-MG feito em um grupo de 2 estudantes.

Um dos meus primeiros projetos que fiz utilizando programação. O código não está bem escrito, estava aprendendo ainda, algumas soluções para determinados 
problemas são bem ruins, porém, decidi colocá-lo no github para ter como recordação, pois, apesar dos pesares, foi um projeto no qual me dediquei bastante,
fiz com bastante carinho e me senti muito realizado au vê-lo funcionando. A ideia era montar um modelo de geladeira utilizando, ao invés de um compressor, 
uma simples placa peltier, pois, o intuito não era de fato ter algo para refrigerar alimentos, e sim aprender um pouco de eletrônica e programação.

O sistema foi feito utilizando um modelo microcontrolador da Texas Instruments da série MSP430 (entretanto, não me recordo qual), porém, criamos uma biblioteca 
para que ele pudesse ser também utilizado com o MSP430G2553. A IDE utilizada foi o IAR Workbench e a linguagem de programação era C, utilizando apenas a 
biblioteca padrão do MSP430, todas as outras bibliotecas (para o teclado, display, etc.) foram implementadas por nós.

A geladeira conta com:
  1. Um teclado numérico para setar a temperatura e fazer outras configurações
  2. Um display para mostrar dados importantes ao usuário
  3. Timer interno do microcontrolador programado para implementar funções de relógio/temporização
  4. Sistema de controle de temperatura da geladeira usando o módulo ADC do MSP
  5. Possibilidade de trabalhar com célcius e fahrenheits
 
O relatório final do projeto com mais especificações sobre o mesmo está na pasta do projeto.

Nota final dada pelo professor: 9.9/10 - Ao se aproximar da temperatura desejada, algumas raras vezes os relés ficavam chaveando rapidamente. Fora isso, tudo
funcionou conforme era esperado
