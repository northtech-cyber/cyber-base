# Fase 5 — Vulnerabilidades e Reconhecimento

**Semana 6** · **Carga:** 8 a 10 horas por semana · [← Roadmap](../roadmap/README.md)

## 🎯 Objetivo

Compreender como vulnerabilidades são identificadas e como informações técnicas são utilizadas para avaliar exposição e risco.

> 💡 Um analista precisa de saber que fraquezas existem e quais corrigir primeiro.

## 📚 Temas

- Vulnerabilidade, CVE e CVSS
- Portas abertas, serviços e scanning
- Reconhecimento, patches, atualizações e gestão de vulnerabilidades
- OWASP Top 10 — conhecer as categorias principais

## 🔗 Onde aprender

- **[TryHackMe](https://tryhackme.com/)** — Salas gratuitas de Nmap e vulnerabilidades.
- **[NVD — National Vulnerability Database](https://nvd.nist.gov/)** — Pesquisa de CVE e pontuação CVSS.
- **[OWASP Top 10](https://owasp.org/www-project-top-ten/)** — Lista das falhas mais comuns em aplicações web.
- **[Metasploitable 2](https://sourceforge.net/projects/metasploitable/)** — VM propositadamente vulnerável para o laboratório.

## 🏁 Exercício do primeiro dia (segunda-feira)

Instalar o Metasploitable 2 numa rede interna (**Host-Only**), nunca exposta à Internet.

## 📬 Exercícios da semana (terça a quinta)

Os restantes exercícios práticos e as perguntas rápidas são publicados pelo mentor como **comentários na issue desta fase** (separador [Issues](https://github.com/northtech-cyber/cyber-base/issues)). Responde lá mesmo.

## 🛠️ Mini-projeto: "Relatório de Vulnerabilidades do Laboratório" (sexta e sábado)

Tabela Host / Porta / Serviço / Versão / CVE / CVSS / Recomendação, ordenada por prioridade, com uma conclusão de 5 linhas.

**Onde entregar:** no teu `cyber-journey`, numa branch `fase-05`, em `mini-projetos/fase-05-vulnerabilidades-e-reconhecimento/README.md`.

**O que tem de ter:**

- [ ] Comando Nmap usado e o que cada opção faz
- [ ] Tabela: Host · Porta · Serviço · Versão · CVE · CVSS · Recomendação
- [ ] Tabela ordenada por prioridade (CVSS mais alto primeiro)
- [ ] Conclusão de 5 linhas: o que corrigirias primeiro e porquê

⚠️ **Só fazes scan às tuas VMs.** Fazer scan a redes ou sistemas de terceiros sem autorização é crime, mesmo que "só para ver".

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

➡️ Próxima: [Fase 6 — Logs, SIEM e Security Monitoring](fase-06-logs-siem-monitorizacao.md)
