# 📤 Como entregar

Este guia explica como entregas o trabalho de cada fase. É sempre o mesmo processo, por isso ao fim de duas ou três fases já o fazes de olhos fechados.

> 💡 **Porquê assim?** Branches, Pull Requests e revisão de código são o dia a dia de qualquer equipa técnica. Ao entregares desta forma, estás a treinar exatamente o que vais fazer num emprego.

---

## Adicionar-te ao `mentorados.md`

Fazes isto **uma vez**, na Fase 0. É o teu primeiro Pull Request.

1. Abre o [`mentorados.md`](mentorados.md) e clica no **lápis ✏️**.
2. O GitHub avisa que não tens permissão e oferece-se para criar um **fork** (uma cópia na tua conta). Aceita.
3. Adiciona a tua linha no **fim** da tabela de mentorados, com o mesmo formato do exemplo.
4. Clica em **Commit changes…**, escreve `Adiciona <teu nome> aos mentorados` e clica em **Propose changes**.
5. Clica em **Create pull request**. Na descrição escreve: *"Li e aceito o Código de Conduta."* e confirma.

O mentor revê e aceita. A partir daí, o teu nome fica na lista oficial.

---

## Entregar o mini-projeto de cada fase

Tudo acontece no **teu** `cyber-journey`. Podes fazer só no browser.

### 1. Cria uma branch para a fase

No teu `cyber-journey`, clica no seletor **`main`** (canto superior esquerdo) → escreve `fase-01` (com o número da fase) → **Create branch: fase-01**.

> Uma branch é uma "cópia de trabalho": podes mexer à vontade sem estragar o `main`.

### 2. Cria a pasta e o README do mini-projeto

Com a branch `fase-01` selecionada: **Add file → Create new file** → escreve o caminho indicado na fase, por exemplo:

```
mini-projetos/fase-01-redes/README.md
```

Copia o [modelo de mini-projeto](https://github.com/northtech-cyber/template-portfolio-cyber/blob/main/mini-projetos/_modelo-mini-projeto.md) e preenche-o. Faz **Commit changes** para a branch `fase-01`.

### 3. Adiciona os screenshots

Dentro da pasta do mini-projeto: **Add file → Upload files** → arrasta as imagens → **Commit changes**.

No README, mostra cada imagem assim:

```markdown
![Descrição da imagem](nome-da-imagem.png)
```

### 4. Abre o Pull Request

Aparece um botão amarelo **Compare & pull request**. Clica nele.

- **De:** `fase-01` **para:** `main` do **teu** repositório
- **Título:** `Fase 1 — A Minha Rede`
- **Reviewers** (à direita): escolhe `W4cher`

Clica em **Create pull request**.

### 5. Avisa na issue da fase

Na [issue da fase](https://github.com/northtech-cyber/cyber-base/issues), comenta:

```
Feito: <link do teu PR>
```

### 6. Corrige e faz merge

O mentor (e um colega, se houver pares de review) deixa comentários no PR. Faz as melhorias na mesma branch: o PR atualiza-se sozinho.

Quando o mentor aprovar, clica em **Merge pull request**. O mini-projeto passa para o teu `main` e fica no teu portfólio. 🎉

---

## 💬 Responder às perguntas da semana

De terça a quinta, o mentor publica exercícios e perguntas na [issue da fase](https://github.com/northtech-cyber/cyber-base/issues). Respondes com um **comentário na própria issue**, logo por baixo das perguntas, indicando o número de cada uma (ex.: `P1: ...`). O mentor dá-te feedback aí mesmo.

Se uma resposta for longa (com comandos, saídas ou screenshots), guarda-a em `notas/fase-XX.md` no teu `cyber-journey` e deixa o link no comentário. Assim também fica no teu portfólio.

---

## Projetos de portefólio

As Fases 8 e 9 têm os dois **projetos principais** do portfólio. Entregam-se da mesma forma, mas na pasta `projetos/`:

- Fase 8 → `projetos/01-investigacao-incidente/`
- Fase 9 → `projetos/02-analisador-de-logs/`

Cada projeto deve incluir: **objetivo, cenário, ambiente utilizado, processo de investigação, ferramentas utilizadas, evidências, resultados, conclusões, screenshots e README**.

---

## ⚠️ Antes de cada commit, confirma

- [ ] Não há passwords, tokens ou chaves
- [ ] Não há o teu IP público nem dados pessoais de outras pessoas
- [ ] Domínios e URLs maliciosos estão desarmados (`exemplo[.]com`, `hxxp://`)

Publicaste algo por engano? Avisa o mentor **imediatamente**. Apagar o ficheiro não chega, porque o histórico do Git guarda tudo.

---

## ❓ Ficaste bloqueado?

Pergunta nas [Discussions](https://github.com/northtech-cyber/cyber-base/discussions) ou na issue da fase. Se estás bloqueado há mais de **2 horas**, pede ajuda: lutar com o problema faz parte, ficar preso dias não.
