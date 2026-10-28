# Fase 7 — Phishing e Threat Intelligence

**Semana 9** · **Carga:** 8 a 10 horas por semana · [← Roadmap](../roadmap/README.md)

## 🎯 Objetivo

Conseguir analisar um email suspeito e verificar indicadores de forma segura.

> 💡 A análise de phishing é uma das tarefas mais frequentes de um analista SOC L1.

## 📚 Temas

- Anatomia de um email de phishing
- Cabeçalhos de email: `From`, `Return-Path` e `Received`
- SPF, DKIM e DMARC
- IOCs: IP, domínio, URL e hash
- Verificação de reputação sem abrir links nem anexos

## 🔗 Onde aprender

- **[LetsDefend (nível gratuito)](https://letsdefend.io/)** — Alertas de phishing simulados num ambiente SOC.
- **[VirusTotal](https://www.virustotal.com/)** — Reputação de ficheiros, URLs, domínios e IPs.
- **[URLScan.io](https://urlscan.io/)** — Analisa um URL sem o abrires no teu browser.
- **[AbuseIPDB](https://www.abuseipdb.com/)** — Reputação de endereços IP.
- **[MXToolbox — Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)** — Análise automática de cabeçalhos de email.

## 🏁 Exercício do primeiro dia (segunda-feira)

Abrir os cabeçalhos completos de um email que recebeste (no Gmail: "Mostrar original") e identificar o remetente real, os servidores e o resultado SPF/DKIM/DMARC.

## 📬 Exercícios da semana (terça a quinta)

Os restantes exercícios práticos e as perguntas rápidas são publicados pelo mentor como **comentários na issue desta fase** (separador [Issues](https://github.com/northtech-cyber/cyber-base/issues)). Responde lá mesmo.

## 🛠️ Mini-projeto: "Relatório de Análise de Phishing" (sexta e sábado)

Resumo, cabeçalhos, IOCs encontrados, reputação, veredicto (malicioso ou legítimo) e ações recomendadas.

**Onde entregar:** no teu `cyber-journey`, numa branch `fase-07`, em `mini-projetos/fase-07-phishing-e-threat-intel/README.md`.

**O que tem de ter:**

- [ ] Resumo do email (sem dados pessoais de ninguém)
- [ ] Análise dos cabeçalhos e resultado SPF/DKIM/DMARC
- [ ] IOCs encontrados, **desarmados** (`exemplo[.]com`, `hxxp://`)
- [ ] Reputação de cada IOC (VirusTotal, URLScan, AbuseIPDB)
- [ ] Veredicto: malicioso ou legítimo, e porquê
- [ ] Ações recomendadas: bloquear remetente, remover emails, alertar utilizadores

⚠️ **Nunca cliques** nos links nem abras anexos. Usa emails de plataformas de treino (LetsDefend) ou emails teus. Antes de publicar, **apaga** nomes, emails e dados pessoais.

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

➡️ Próxima: [Fase 8 — Resposta a Incidentes](fase-08-resposta-a-incidentes.md)
