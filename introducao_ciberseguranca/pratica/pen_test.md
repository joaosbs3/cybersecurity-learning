# 🛠️ Teste de Penetração (Pen Test) — Processo em 5 etapas

## Resumo
Pen testing = avaliar sistemas/rede/processos para encontrar vulnerabilidades exploráveis; objetivo: melhorar defesas.

## Etapas do pen test

1. **Planejamento**
   - Definir escopo, autorizações, limites e metas.
   - Coletar informações públicas (reconhecimento passivo).

2. **Varredura (Reconhecimento ativo)**
   - Port scan (nmap), fingerprinting, verificação de vulnerabilidades.
   - Enumeração de serviços e contas.

3. **Obter acesso (Exploração)**
   - Explorar vulnerabilidades identificadas: exploits, engenharia social, falhas de configuração.

4. **Manter acesso**
   - Implantar backdoors/poCs para simular persistência (em teste controlado).

5. **Análise e relatório**
   - Documentar achados, risco, evidências e recomendações (correções e mitigação).

## 🧩 Nota prática
- Sempre com autorização por escrito. Em ambiente corporativo, combine janela de testes e rollback plan.

## Exercício (ordem correta, exemplo)
- Reúna informações sem ser detectado → Investigue a rede → Identifique vulnerabilidades → Explore vulnerabilidades → Relate descobertas.
