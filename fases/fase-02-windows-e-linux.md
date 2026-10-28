# Fase 2 — Windows e Linux

**Semana 3** · **Carga:** 8 a 10 horas por semana · [← Roadmap](../roadmap/README.md)

## 🎯 Objetivo

Conseguir navegar e realizar operações básicas em Windows e Linux, e encontrar eventos de autenticação nos logs.

> 💡 Um profissional de Cibersegurança precisa de compreender os sistemas que está a proteger.

## 📚 Temas

- **Windows:** ficheiros, pastas, utilizadores, grupos e permissões
- **Windows:** processos, serviços, Task Manager e Event Viewer
- **Windows:** linha de comandos e PowerShell (fundamentos)
- **Windows:** Event IDs essenciais: 4624, 4625, 4720 e 4688
- **Windows:** noções de Active Directory: domínio, utilizadores, grupos e políticas
- **Linux:** estrutura de ficheiros, utilizadores, grupos e permissões
- **Linux:** processos e serviços
- **Linux:** comandos essenciais: `ls`, `cd`, `pwd`, `cat`, `grep`, `find`, `ps`, `chmod`, `sudo`
- **Linux:** logs de autenticação: `/var/log/auth.log`

## 🔗 Onde aprender

- **[Microsoft Learn — Windows](https://learn.microsoft.com/training/)** — Conceitos fundamentais relacionados com Windows e segurança.
- **[Linux Journey](https://linuxjourney.com/)** — Fundamentos de Linux e linha de comandos.
- **[OverTheWire — Bandit](https://overthewire.org/wargames/bandit/)** — Jogo gratuito para treinar comandos Linux (níveis 0 a 10).

## 🏁 Exercício do primeiro dia (segunda-feira)

Linux: criar 2 utilizadores e o grupo `analistas`; criar um ficheiro com `chmod 640` e testar quem o consegue ler.

## 📬 Exercícios da semana (terça a quinta)

Os restantes exercícios práticos e as perguntas rápidas são publicados pelo mentor como **comentários na issue desta fase** (separador [Issues](https://github.com/northtech-cyber/cyber-base/issues)). Responde lá mesmo.

## 🛠️ Mini-projeto: "Investigar o Meu Próprio Sistema" (sexta e sábado)

Relatório de 1 página com os utilizadores, 5 serviços em execução e 3 eventos de login (ID, hora, utilizador e resultado), em Windows e em Linux.

**Onde entregar:** no teu `cyber-journey`, numa branch `fase-02`, em `mini-projetos/fase-02-windows-e-linux/README.md`.

**O que tem de ter:**

- [ ] Lista de utilizadores (Windows e Linux) e os comandos usados para os obter
- [ ] 5 serviços em execução em cada sistema e para que servem
- [ ] 3 eventos de login em cada sistema: ID do evento, hora, utilizador, sucesso/falha
- [ ] Screenshots do Event Viewer e do `auth.log`

⚠️ Faz isto **nas tuas VMs**, não no computador do trabalho ou da escola.

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

➡️ Próxima: [Fase 3 — Fundamentos de Cibersegurança](fase-03-fundamentos-ciberseguranca.md)
