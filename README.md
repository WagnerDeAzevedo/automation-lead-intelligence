# ⚙️ Automation Lead Intelligence — n8n + OpenAI

Este projeto apresenta uma **automação inteligente de triagem e qualificação de leads**
utilizando **n8n** como orquestrador e **OpenAI** para análise e classificação.

O foco é **processo, decisão e priorização**, não interação por chat.

---

## 🎯 Objetivo

- Receber leads de diferentes fontes
- Padronizar informações de entrada
- Classificar e priorizar leads com IA
- Gerar resumo acionável para equipes
- Automatizar decisões sem inflar fluxos

---

## 🧩 Visão de Produto

Esta automação foi pensada para negócios que precisam:

- responder leads mais rápido
- priorizar oportunidades reais
- reduzir trabalho manual
- padronizar critérios de decisão

O mesmo core pode ser reutilizado para diferentes canais
(formulários, APIs, planilhas ou CRMs),
mudando apenas a origem da entrada ou o destino da saída.

---

## 🧱 Arquitetura (resumida)

Fluxo principal:

1. Entrada via webhook genérico
2. Padronização dos dados do lead
3. IA para classificação e resumo estruturado
4. Switch por prioridade ou perfil
5. Ação automática (notificação, CRM, planilha, etc.)

Arquitetura propositalmente enxuta para facilitar
manutenção, reuso e evolução.

---

## 🧠 Saída estruturada esperada

Exemplo de campos gerados pela IA:

- `prioridade`
- `perfil`
- `resumo_lead`
- `proximo_passo`

---

## 🔐 Segurança & Boas práticas

- Nenhuma credencial versionada
- Tokens via variáveis de ambiente
- Nenhum dado sensível persistido
- Pronto para adequação à LGPD

---

## 🧭 Evolução planejada

- Integração com CRMs
- Métricas de conversão
- Ajuste fino dos critérios de classificação
- Reuso para múltiplos clientes

---

## 📄 Licença

Uso educacional e demonstrativo.
