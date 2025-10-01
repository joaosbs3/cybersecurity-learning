# 🔁 NetFlow e Coleta de Telemetria

## 📌 Definição
NetFlow (e protocolos similares como sFlow/IPFIX) é um protocolo para coletar informações sobre o tráfego que atravessa dispositivos de rede (fluxos, volumes, IPs, portas, timestamps).

## ✅ Para que serve
- Análise de padrões de tráfego
- Detecção de anomalias (DDoS, varredura)
- Auditoria e capacidade de rede

## 🛠️ Exemplos de uso
- Exportar fluxos de roteadores/switches para um coletor (p.ex. Elastic Stack, ntopng, SolarWinds).
- Analisar flows para encontrar hosts que transferem grandes volumes de dados.

## 📝 Notas pessoais
- Sempre correlacione NetFlow com logs de firewall/IDS para contexto.
