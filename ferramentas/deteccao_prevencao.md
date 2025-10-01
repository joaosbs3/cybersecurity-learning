# 🛡️ Ferramentas de Detecção e Prevenção

## 🎯 Resumo rápido
Conjunto de ferramentas usadas para detectar, analisar e (em alguns casos) bloquear tráfego malicioso na rede e em endpoints.

## Ferramentas e conceitos principais

### SNORT
- **O que é:** IDS/IPS de código aberto capaz de análise de tráfego em tempo real.
- **O que faz:** Detecta varreduras de porta, impressão digital (fingerprinting), ataques de estouro de buffer, e muito mais com base em assinaturas e regras.
- **Uso típico:** modo IDS (apenas alerta) ou modo IPS (bloqueio).

### IDS vs IPS
- **IDS (Intrusion Detection System):** identifica tráfego mal-intencionado comparando pacotes com assinaturas/regras e gera alertas.
- **IPS (Intrusion Prevention System):** além de identificar, pode **bloquear/negá**r o tráfego com base em regras ou assinaturas.

### SIEM (Security Information and Event Management)
- **O que faz:** coleta e correlaciona logs e alertas de múltiplas fontes (firewalls, IDS/IPS, servidores, endpoints) para detecção avançada e investigação forense.

### DLP (Data Loss Prevention)
- **O que faz:** previne vazamento de dados sensíveis monitorando dados em trânsito, em uso e em repouso; aplica políticas para bloquear/exfiltrar dados.

## 📝 Notas práticas
- Use SNORT para detecção com regras atualizadas; combine com um SIEM para correlação e histórico.
- IPS deve ser testado em ambiente controlado antes de entrar em produção para evitar falsos-positivos que interrompam serviços.

