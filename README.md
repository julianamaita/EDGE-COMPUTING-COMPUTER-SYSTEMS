# EDGE-COMPUTING-COMPUTER-SYSTEMS
 - Julia Palomari RM551910
 - Juliana Maita RM99224
 - Leticia Baptista RM550289
 - Leonardo Schunck RM99902
 - Kayky Schunck RM99756





Projeto: Controle Automático de Ambiente

Descrição:
Este projeto utiliza um Arduino para controlar o ambiente com base em leituras de sensores. Ele monitora a luminosidade, temperatura e umidade do ambiente e realiza ações automáticas, como abrir ou fechar janelas, acender LEDs e ativar um buzzer.

Componentes utilizados:

Arduino Uno (ou outro modelo compatível)
Sensor de luminosidade (LDR)
Sensor de temperatura (NTC)
Sensor de umidade (DHT11, DHT22, ou similar)
Display LCD 16x2
Servo motor
LEDs (vermelho e verde)
Buzzer
Resistores e cabos de conexão
Instruções de uso:

Conecte os componentes ao Arduino conforme os esquemas de conexão adequados.
Abra o software Arduino IDE.
Conecte o Arduino ao computador via cabo USB.
Compile e faça o upload do código para o Arduino.
Abra o monitor serial para visualizar as leituras dos sensores e as ações realizadas.
Requisitos:

Arduino IDE instalado no computador.
Bibliotecas "Servo" e "LiquidCrystal" instaladas na Arduino IDE.
Conexão dos componentes de acordo com os esquemas de conexão apropriados.
Dependências:

Biblioteca "Servo" (já incluída no Arduino IDE).
Biblioteca "LiquidCrystal" (já incluída no Arduino IDE).
Informações adicionais:

O projeto realiza leituras dos sensores de luminosidade, temperatura e umidade em intervalos regulares.
Com base nos valores lidos, o projeto toma decisões e executa ações automáticas.
Se a luminosidade estiver acima de 80%, as janelas serão abertas e informações serão exibidas no display LCD.
Caso contrário, as janelas serão fechadas e informações serão exibidas no display LCD.
O projeto também verifica se a temperatura está abaixo de 35°C e se a umidade está entre 10% e 30%.
Dependendo das condições, os LEDs vermelho e verde serão acionados e o buzzer será ligado ou desligado.
O monitor serial exibirá as leituras dos sensores e informações sobre as ações realizadas.
