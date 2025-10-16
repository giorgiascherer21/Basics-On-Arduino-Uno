## Parte 2: Blink Led Externo TinkerCad
Este projeto tem como objetivo simular, no **Tinkercad**, o funcionamento de um LED **externo** conectado a um **Arduino Uno**, utilizando um **protoboard** e **resistor**.  

A simulação demonstra o controle de um LED fora da placa, fazendo-o piscar em intervalos definidos via programação.

Código utilizado a seguir: 

```c++
#include <Arduino.h>

int ledPin = 6; // LED conectado ao pino digital 6

void setup() {
  pinMode(ledPin, OUTPUT); // Define o pino 6 como saída
}

void loop() {
  digitalWrite(ledPin, HIGH); // Liga o LED
  delay(1000);                // Espera 1 segundo (1000 ms)
  digitalWrite(ledPin, LOW);  // Desliga o LED
  delay(1000);                // Espera 1 segundo

```



[Clique aqui e cesse a simulação completa no Tinkercad](https://www.tinkercad.com/things/0GcKGZj6H3j-fantabulous-wolt/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=BER5DX6-22MzfWF1ERQtejahC6lbkdcCM_3ho7-65-I)
 
