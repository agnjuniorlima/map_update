Map Updater (lifelong SLAM)
Este espaço é dedicado ao atualizador de mapas objeto do trabalho de Robótica Probabilística do PPGI/UFES, período 2024/2.

Resumo— Este trabalho visa a implementação de um novo modulo atualizador de mapas, denominado MAPUPDATER, que visa à implementação de um sistema que permite atualização precisa do offline map (mapa inicial), em especial a retirada ou inclusão de objetos (carros estacionados, barrancos, obstáculos, árvores derrubadas, colisões entre veículos, etc.) de forma a proporcionar situações mais próximas da realidade, ao mesmo tempo, garantir uma navegação segura e eficiente ao longo do tempo no sistema de controle de veículos autônomos do projeto denominado IARA (Intelligent Autonomous Robotic Automobile), desenvolvido pelo Laboratório de Computação de Alto Desempenho (LCAD) da Universidade Federal do Espírito Santo (UFES), cujo código de controle é baseado no CARMEN (Carnegie Mellon Robot Navigation Toolkit), cuja versão foi denominada CARMEN-LCAD. É apresentado um procedimento para edição (alterações) do offline map, que é executado antes da execução do CARMEN (independente) e outro procedimento para alteração (edição) do mapa atual durante a execução do CARMEN. 

O trabalho foi realizado por duas duplas:
1) Luiz Rogério Araujo de Araujo (luiz.r.araujo@edu.ufes.br e luiz.r.araujo2@gmail.com)
2) Agnelo Pereira Lima Junior    (agnjuniorlima@gmail.com)
3) Áurea Santos de Oliveira      (aurea.s.oliveira@edu.ufes.br)
4) Miguel Gewhr de Oliveira      (miguel.g.oliveira@edu.ufes.br)

O relatório está disponível em https://1drv.ms/w/c/70412aa3b15ab01e/Ee7ud2ZxPStKh1Snjv-TOxMBYclYa7vXb1yxmnoS0UJEYQ?e=DXD5xA 

Os logs das voltas na UFES estão no endereço https://drive.google.com/drive/folders/1Kch9jpfGJdmnJ7BQSiIXqpbi2FdHrFVQ?usp=sharing 

Procedimentos de criação e edição de mapas:

1) O procedimento para criar um novo mapa a partir de um log do CARMEN, no arquivo ["Como Criar um Mapa a Partir de um Log.txt"](https://github.com/agnjuniorlima/map_update/blob/main/Como%20Criar%20um%20Mapa%20a%20Partir%20de%20um%20Log.txt)
   
2) O procedimento para editar um mapa através do CARMEN => ["Como Editar um Mapa Com o CARMEN.txt"](https://github.com/agnjuniorlima/map_update/blob/main/Como%20Editar%20um%20Mapa%20com%20o%20CARMEN.txt)


