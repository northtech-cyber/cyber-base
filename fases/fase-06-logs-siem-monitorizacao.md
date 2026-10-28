# Fase 6 — Logs, SIEM e Security Monitoring

**Semanas 7–8** · **Carga:** 8 a 10 horas por semana · [← Roadmap](../roadmap/README.md)

## 🎯 Objetivo

Conseguir interpretar logs e investigar alertas básicos de segurança.

> 💡 Esta é uma das fases mais importantes para funções de entrada em Security Operations. O objetivo é compreender o funcionamento de um SIEM, não dominar várias plataformas.

## 📚 Temas

- O que são logs, eventos e indicadores de comprometimento (IOC)
- Logs de autenticação, sistema e rede
- Alertas, falsos positivos e correlação de eventos
- SIEM e monitorização
- Regras de deteção simples e dashboards

## 🔗 Onde aprender

- **[Splunk (versão gratuita)](https://www.splunk.com/en_us/download/splunk-enterprise.html)** — SIEM principal para a prática desta fase.
- **[Splunk Education](https://education.splunk.com/)** — Cursos gratuitos de introdução ao Splunk.
- **[Splunk — Boss of the SOC (BOTS v3)](https://github.com/splunk/botsv3)** — Conjunto de dados gratuito para treinar investigações.
- **[Microsoft Learn — Microsoft Sentinel](https://learn.microsoft.com/azure/sentinel/)** — Apenas teoria: a prática exige uma subscrição Azure.
- **[Wazuh](https://wazuh.com/)** — Alternativa gratuita e open source.

## 🏁 Exercício do primeiro dia (segunda-feira)

Gerar 10 falhas de login SSH contra **a tua própria VM** e encontrá-las no `auth.log`.

## 📬 Exercícios da semana (terça a quinta)

Os restantes exercícios práticos e as perguntas rápidas são publicados pelo mentor como **comentários na issue desta fase** (separador [Issues](https://github.com/northtech-cyber/cyber-base/issues)). Responde lá mesmo.

## 🛠️ Mini-projeto: "As Minhas Primeiras Deteções" (sexta e sábado)

3 regras de deteção, um dashboard simples e a documentação de cada regra (lógica, motivo e possíveis falsos positivos).

**Onde entregar:** no teu `cyber-journey`, numa branch `fase-06`, em `mini-projetos/fase-06-logs-siem-monitorizacao/README.md`.

**O que tem de ter:**

- [ ] **Regra 1:** 5 falhas de login em 1 minuto
- [ ] **Regra 2:** login fora do horário de trabalho
- [ ] **Regra 3:** criação de novo utilizador (evento 4720)
- [ ] Para cada regra: a pesquisa (SPL), a lógica, porque é útil e possíveis falsos positivos
- [ ] Screenshot do dashboard

📦 **Dados de apoio:** se precisares de mais eventos para testar, usa o ficheiro [`dados/auth.log`](../dados/auth.log). Tem um ataque de força bruta a SSH já registado, com IPs de documentação (não reais). Vais voltar a usá-lo na Fase 9.

Quando terminares, abre um Pull Request para o teu `main` e comenta na issue da fase: `Feito: <link do PR>`. Os passos estão em [`COMO-ENTREGAR.md`](../COMO-ENTREGAR.md).

## 🎤 Apresentação (domingo)

Apresenta o mini-projeto ao mentor na sessão de domingo, em **5 a 10 minutos**:

1. Objetivo
2. O que foi feito
3. Evidências
4. O que aprendeste
5. Dificuldades

## ✅ A fase termina quando

- [ ] O mini-projeto está entregue (PR aprovado pelo mentor)
- [ ] O mini-projeto foi apresentado no domingo

---

➡️ Próxima: [Fase 7 — Phishing e Threat Intelligence](fase-07-phishing-e-threat-intel.md)
