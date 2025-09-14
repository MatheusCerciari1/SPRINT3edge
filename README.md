# SPRINT3edge

# Projeto  FIAP – Passa a Bola

Contagem de gols em tempo real com IoT
Arduino + sensor de movimento + buzzer + Node-RED para registrar gols e mostrar o total em painel interativo.

👥 Integrantes
Matheus Cerciari Reis RM-565817
Henrique Vicente Vicente RM-564116
Arthur Gaspare Gil RM-555764
Anna Clara Ruggeri da Silva RM-565553
Luis Gustavo Vansconcelos Costa RM-566023 


🧩 Componentes

Arduino: ArduinoJson, sensor de movimento, buzzer
Node-RED: node-red-dashboard, nós Serial In, JSON, Function, Gauge

⚙️ Como Usar

Conecte o Arduino e carregue o código com ArduinoJson.
Instale Node-RED e o dashboard (npm install node-red-dashboard).
Importe o fluxo, configure Serial In ou use Inject para simular gols.
O Gauge mostrará o total de gols; o buzzer soa a cada gol.


Links:
Simulação Wokwi: https://wokwi.com/projects/441934975598714881
Vídeo YouTube: https://youtu.be/fkyZQ9pIUIY

📌 Resumo

Integração de Arduino e Node-RED para dashboards em tempo real, aplicável a esportes ou eventos que exigem registro e análise imediata de dados.
