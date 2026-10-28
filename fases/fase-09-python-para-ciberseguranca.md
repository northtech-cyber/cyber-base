# Fase 9 — Python Básico para Cibersegurança

**Semana 11** · **Carga:** 8 a 10 horas por semana · [← Roadmap](../roadmap/README.md)

## 🎯 Objetivo

Conseguir utilizar Python para automatizar tarefas simples relacionadas com análise de segurança.

> 💡 O objetivo não é transformar-te num developer: Python serve para automatizar pequenas tarefas de segurança.

## 📚 Temas

- Variáveis, condições e ciclos
- Funções, listas e dicionários
- Ficheiros e leitura de logs
- Extrair IPs de texto e exportar resultados para CSV

## 🔗 Onde aprender

- **[Kaggle Learn — Python](https://www.kaggle.com/learn/python)** — Conteúdos fundamentais, gratuitos e interativos.
- **[Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)** — Livro gratuito online; capítulos sobre ficheiros e texto.

## 🏁 Exercício do primeiro dia (segunda-feira)

Criar um script que pede um nome e imprime uma saudação.

## 📬 Exercícios da semana (terça a quinta)

Os restantes exercícios práticos e as perguntas rápidas são publicados pelo mentor como **comentários na issue desta fase** (separador [Issues](https://github.com/northtech-cyber/cyber-base/issues)). Responde lá mesmo.

## 🛠️ Mini-projeto: "Projeto de Portefólio 2 — Analisador de Logs" (sexta e sábado)

Script Python que lê o ficheiro de logs da Fase 6, identifica eventos, conta ocorrências, identifica IPs, filtra comportamentos específicos e produz um resumo.

**Onde entregar:** no teu `cyber-journey`, numa branch `fase-09`, em `projetos/02-analisador-de-logs/`.

**O que tem de ter:**

- [ ] Script `analisador.py` comentado
- [ ] Lê um ficheiro de log passado como argumento
- [ ] Conta falhas de login por IP e por utilizador
- [ ] Deteta logins bem-sucedidos vindos de IPs que antes falharam
- [ ] Exporta o resultado para CSV e imprime um resumo
- [ ] README com como correr o script e um exemplo de saída

📦 Usa os logs que geraste na Fase 6 **e** o ficheiro [`dados/auth.log`](../dados/auth.log) para testar.

⭐ Este é o **segundo projeto principal** do teu portfólio. Entrega-o em `projetos/02-analisador-de-logs/`.

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

➡️ Próxima: [Fase 10 — Preparação para o Mercado](fase-10-preparacao-mercado.md)
