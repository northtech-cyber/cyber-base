# Fase 1 — Redes

**Semanas 1–2** · **Carga:** 8 a 10 horas por semana · [← Roadmap](../roadmap/README.md)

## 🎯 Objetivo

Compreender como dispositivos comunicam através de uma rede e reconhecer os principais protocolos utilizados.

> 💡 Antes de aprender segurança, é necessário compreender como os dispositivos comunicam.

## 📚 Temas

- LAN, WAN e endereçamento IP (público/privado)
- MAC Address, TCP e UDP, portas e protocolos
- DNS, DHCP, HTTP e HTTPS
- Routers, switches e firewalls
- Modelo OSI — conceitos essenciais
- Diagnóstico de rede: `ipconfig`, `ping`, `tracert`, `nslookup` e `netstat`

## 🔗 Onde aprender

- **[Cisco Networking Academy — Networking Basics](https://www.netacad.com/courses/networking-basics)** — Percurso introdutório para compreender os fundamentos de redes.
- **[Professor Messer — CompTIA Network+ (vídeos gratuitos)](https://www.professormesser.com/)** — Usa apenas os vídeos dos temas desta fase.

## 🏁 Exercício do primeiro dia (segunda-feira)

Executar `ipconfig /all` (Windows) ou `ip a` (Linux): anotar IP, máscara, gateway, DNS e MAC. O IP é privado ou público? Porquê?

## 📬 Exercícios da semana (terça a quinta)

Os restantes exercícios práticos e as perguntas rápidas são publicados pelo mentor como **comentários na issue desta fase** (separador [Issues](https://github.com/northtech-cyber/cyber-base/issues)). Responde lá mesmo.

## 🛠️ Mini-projeto: "A Minha Rede" (sexta e sábado)

Diagrama da rede de casa (router, dispositivos e IPs), tabela com 10 portas/protocolos e a sua função, e explicação escrita do que acontece quando se abre um site.

**Onde entregar:** no teu `cyber-journey`, numa branch `fase-01`, em `mini-projetos/fase-01-redes/README.md`.

**O que tem de ter:**

- [ ] Diagrama da rede de casa (pode ser feito em draw.io ou à mão e fotografado)
- [ ] Tabela com 10 portas/protocolos: porta, protocolo, TCP/UDP, para que serve
- [ ] Texto: o que acontece, passo a passo, quando escreves um endereço no browser (DNS → TCP → HTTP/HTTPS)
- [ ] Screenshots dos comandos de diagnóstico usados

⚠️ No diagrama, **não publiques o teu IP público** nem dados que identifiquem a tua casa. Os IPs privados (192.168.x.x, 10.x.x.x) podem aparecer.

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

➡️ Próxima: [Fase 2 — Windows e Linux](fase-02-windows-e-linux.md)
