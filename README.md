# Publish-Subscribe (Pub/Sub)


“A inovação é a única maneira de vencer a concorrência e prosperar”. - Jeff Bezos


**Introdução**


O Publish-Subscribe (também conhecido como pub/sub) é uma arquitetura de mensagens orientada a eventos que permite que os serviços se comuniquem de forma assíncrona. Esta abordagem é ideal para aplicações em tempo real que precisam lidar com grandes volumes de dados. O objetivo deste artigo é descrever uma prova de conceito usando Python, Publish-Subscribe, Kinesis, ESP32, API Gateway, Lambda, Elasticsearch, Kibana e DynamoDB para construir uma plataforma de análise de dados em tempo real.


**Descrição da Prova de Conceito**


O objetivo desta prova de conceito é criar uma plataforma que possa coletar dados de dispositivos IoT usando ESP32, processar os dados usando API Lambda e armazená-los no DynamoDB. Os dados devem ser então publicados no Kinesis para que possam ser consumidos por Elasticsearch e Kibana para análise.


Arquitetura da Solução


![](img/fig1.png)


Coleta de Dados


Processamento de Dados





**Referências:**


[ 1 ] [https://micropython.org/download/esp32-ota/](https://micropython.org/download/esp32-ota/)<br>
[ 2 ] [https://micropython.org/resources/firmware/esp32-ota-20220618-v1.19.1.bin](https://micropython.org/resources/firmware/esp32-ota-20220618-v1.19.1.bin)<br>
[ 3 ] [https://docs.micropython.org/en/latest/esp32/quickref.html](https://docs.micropython.org/en/latest/esp32/quickref.html)<br>

```python

```
