# Fase 4 — Análise de Rede

**Semana 5** · **Carga:** 8 a 10 horas por semana · [← Roadmap](../roadmap/README.md)

## 🎯 Objetivo

Conseguir observar tráfego de rede e compreender informações básicas presentes numa captura.

> 💡 O tráfego de rede mostra o que realmente aconteceu, mesmo quando os logs não o mostram.

## 📚 Temas

- Pacotes, tráfego de rede, protocolos e portas
- Captura de tráfego e filtragem
- Handshake TCP, tráfego DNS e HTTP vs HTTPS
- Identificação de comportamento suspeito

## 🔗 Onde aprender

- **[Wireshark — documentação](https://www.wireshark.org/docs/)** — Documentação e materiais introdutórios.
- **[TryHackMe](https://tryhackme.com/)** — Salas gratuitas de Wireshark e networking.
- **[Malware-Traffic-Analysis.net — exercícios](https://www.malware-traffic-analysis.net/training-exercises.html)** — Exercícios com capturas reais.

## 🏁 Exercício do primeiro dia (segunda-feira)

Capturar 2 minutos de tráfego e aplicar os filtros `dns`, `tcp.port==443` e `ip.addr==<o teu IP>`.

## 📬 Exercícios da semana (terça a quinta)

Os restantes exercícios práticos e as perguntas rápidas são publicados pelo mentor como **comentários na issue desta fase** (separador [Issues](https://github.com/northtech-cyber/cyber-base/issues)). Responde lá mesmo.

## 🛠️ Mini-projeto: "Análise de uma Captura" (sexta e sábado)

Analisar um PCAP de exercício e responder num relatório: IP da vítima, hostname, domínio ou IP suspeito, hora do primeiro contacto e protocolo usado, com screenshots.

**Onde entregar:** no teu `cyber-journey`, numa branch `fase-04`, em `mini-projetos/fase-04-analise-de-rede/README.md`.

**O que tem de ter:**

- [ ] Qual o exercício/PCAP analisado (link)
- [ ] IP e hostname da vítima
- [ ] Domínio ou IP suspeito e hora do primeiro contacto
- [ ] Protocolo usado na comunicação suspeita
- [ ] Filtros de Wireshark usados e screenshots
- [ ] Domínios e URLs maliciosos **desarmados** (`exemplo[.]com`, `hxxp://`)

⚠️ Os PCAPs do Malware-Traffic-Analysis contêm **tráfego de malware real**. Abre-os **apenas na VM**, nunca extraias ficheiros executáveis e nunca visites os domínios no browser.

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

➡️ Próxima: [Fase 5 — Vulnerabilidades e Reconhecimento](fase-05-vulnerabilidades-e-reconhecimento.md)
