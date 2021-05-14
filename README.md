# Medidor de Pressão Arterial Digital


O nosso projeto consiste em realizar leituras em um transdutor como sensor de pressão, detectar seus pulsos fazendo a transdução do sinal de pressão para uma tensão analógica, e posteriormente digitalizá-los por meio de um conversor analógico-digital (ADC).
Também estaremos alterando o medidor de pressão original (Esfigmomanômetro), substituindo a Pêra Valvulada por uma bomba de pressão de ar e uma válvula eletrônica.

Ao invés de necessitar do pressionamento físico de um botão antes de um upload, o Arduino Uno é desenvolvido de maneira que permita que esta operação seja feita por meio do software rodando em um computador. Uma das linhas de controle de fluxo do hardware (DTR) do ATmega8U2 é conectado à linha de reset do ATmega328 através de um capacitor de 100nF. Quando esta linha é declarada (rebaixada) a linha de reset cai o suficiente para resetar o chip. O software do Arduino utiliza esta capacidade para permitir o envio de código novo simplesmente pressionando o botão de upload na IDE. Isto significa que o bootloader pode ter um intervalo mais curto, uma vez que o rebaixamento do DTR pode ser melhor coordenado com o início do upload.

Detalhamento dos Componentes
Arduino Uno R3
Microcontrolador	ATmega328
Sensor de Pressão modelo 2050 da linha MPX 
Bomba de Pressão de Ar KPM14A
Válvula Eletrônica KSV05A
Módulo Ethernet ENC28J60 para conexão com a Internet


OBJETOS INTELIGENTES CONECTADOS {TURMA 05A} 2021/1

EDMILSON BISPO PAES DOS SANTOS - 10919010291

JONI WELTER RAMOS - 10919005636

Professor: WILIAN FRANCA COSTA.
