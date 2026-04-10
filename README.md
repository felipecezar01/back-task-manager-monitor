# 📊 Laboratório de Observabilidade: Prometheus & Grafana

Uma Prova de Conceito (PoC) local desenvolvida para explorar os pilares de **Observabilidade e Telemetria** em aplicações Backend. O laboratório simula a instrumentação de uma API JavaScript (Node.js) para coleta, armazenamento e visualização de métricas de infraestrutura em tempo real.

---

## 🏗️ Arquitetura do Laboratório

Este ambiente de testes foi configurado localmente para validar a integração entre o ecossistema de monitoramento:

* **Node.js (JavaScript):** Aplicação alvo instrumentada para expor métricas (como volume de requisições e uso de recursos).
* **Prometheus:** Time-series database configurado para fazer o *scraping* (coleta) contínua das métricas expostas pela aplicação alvo.
* **Grafana:** Plataforma de visualização conectada ao Prometheus para construção de dashboards interativos, permitindo a identificação de gargalos e anomalias.

---

## 📸 Evidências da Implementação

> 💡 **Nota Histórica:** Este projeto é um laboratório de infraestrutura executado em ambiente local (localhost) no ano de 2023. As capturas de tela abaixo documentam o sucesso da integração e a visualização dos dados no momento da validação da PoC.

### Dashboard de Telemetria (Grafana)
<div align="center">
  <img src="grafana.png" alt="Dashboard do Grafana exibindo painéis de monitoramento">
</div>

### Análise de Métricas Brutas
<div align="center">
  <img src="pre-graf.png" alt="Visualização de Gráficos e queries de Monitoramento">
</div>

---
*Projeto mantido como registro de evolução técnica, focado em práticas de SRE (Site Reliability Engineering) e monitoramento de performance de servidores.*
