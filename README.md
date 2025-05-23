# K_WaterFlow
Sistema de monitoramento inteligente de água com ESP32-S3, DHT22, MQTT e ThingSpeak.

# K_WaterFlow - Monitoramento Inteligente de Consumo de Água

Projeto acadêmico desenvolvido para a disciplina de IoT e Sistemas Embarcados da Universidade Presbiteriana Mackenzie.

## 📌 Objetivo

Desenvolver uma solução para monitoramento e controle do uso de água em ambientes urbanos, utilizando o microcontrolador ESP32-S3, sensor DHT22 e protocolo MQTT, com visualização dos dados via ThingSpeak.

## 🔧 Componentes utilizados

- ESP32-S3 (Wokwi simulado)
- Sensor DHT22 (Temperatura e Umidade)
- LEDs (simulação de alerta e válvula)
- Broker MQTT (HiveMQ)
- Plataforma ThingSpeak
- Simulador Wokwi

## 💻 Funcionalidades

- Leitura de temperatura e umidade com DHT22
- Publicação MQTT dos dados para tópicos:
  - `k_waterflow/temp`
  - `k_waterflow/hum`
- Acionamento de LED de alerta quando a temperatura > 30°C
- Simulação de válvula com LED (relay)
- Envio em tempo real para o ThingSpeak

## 🚀 Como executar

1. Abra o projeto no Wokwi:  
   [Clique aqui para simular](https://wokwi.com/projects/429615231347717121)

2. Use um broker MQTT gratuito como HiveMQ

3. Configure um canal no ThingSpeak com 2 campos (temperatura e umidade)  
   - Copie o link e insira no código

## 📊 Resultados

Veja na pasta `resultados/`:
- Prints da simulação
- Captura da dashboard ThingSpeak
- Tabela de tempos de resposta

## 🎥 Demonstração

](https://youtu.be/bOd7mAYoe0I?feature=shared) ← (Adicione aqui o link do seu vídeo)

## 📁 Esquema do Projeto

- `esquema.png` → Diagrama de montagem
- ![image](https://github.com/user-attachments/assets/0b50aa30-9ed4-4d12-8e10-6c1d069b983a)

- `fluxograma.png` → Lógica de funcionamento
![undefined_ESP32-S3_and_MQTT_Data_Handling](https://github.com/user-attachments/assets/9a5c5c9e-7f44-4af7-8cc7-89894039268b)


---

**Autor:** Kennedy Guedes dos Santos Silva  
**Disciplina:** Sistemas Embarcados / IoT  
**Universidade Presbiteriana Mackenzie**

