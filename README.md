# Sistema-de-Irrigacao



Monitoramento de Plantações Residenciais com Arduino:
Este projeto utiliza a plataforma Arduino para criar um sistema de irrigação inteligente para pequenas hortas caseiras. Ele usa um sensor de temperatura e um sensor de umidade do solo para determinar quando as plantas precisam ser regadas.

Sumário
Introdução
Requisitos
Instalação
Uso

Introdução:
O desperdício de alimentos é um problema global. Muitas vezes, as plantas em pequenas hortas caseiras morrem devido à falta de irrigação adequada ou a condições ambientais não ideais. Este projeto visa resolver esse problema através do monitoramento e ajuste automatizados das condições ambientais.

Requisitos:
Para replicar este projeto, você precisará dos seguintes componentes:

Arduino UNO
Sensor de temperatura TMP36
Potenciômetro (para simular um sensor de umidade do solo)
LED (para simular uma bomba de água)
Fios e resistores adequados
Instalação:
Conecte o sensor de temperatura TMP36 e o potenciômetro ao seu Arduino UNO conforme as instruções fornecidas no código.

Conecte o LED ao seu Arduino UNO. Este LED representará a bomba de água em nosso sistema.

Carregue o código do Arduino fornecido neste repositório para o seu Arduino UNO.

Uso:
Uma vez que o sistema esteja configurado, ele começará a monitorar a temperatura e a umidade do solo. Se a temperatura estiver acima do limite definido ou a umidade do solo estiver abaixo do limite definido, o sistema "irrigará" as plantas (ou seja, acenderá o LED). As leituras dos sensores e o estado da "bomba d'água" serão exibidos no monitor serial do Arduino.
