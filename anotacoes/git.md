<h1 align="center">Git</h1>


## Log

Mostra informações sobre os commits existentes.

```bash
git log
```

Utilizando o SHA (SHA são os 7 primeiros digitos do ID criado para cada commit).

```bash
git log 689aa7f
```

Listando os commits com suas informações em uma linha.

```bash
git log --oneline
```

Mostra uma lista com todos os arquivos modificado no commit.

```bash
git log --stat
```

Visualizar o log de commits de uma forma mais visual com branches representados por linhas.

```bash
git log --graph
```

---

## Show

Mostra informações sobre o commit em questão com mais detalhes mesma saida que o "git log -p" porém de apenas um commit.

```bash
git show
```

Utilizando o SHA SHA são os 7 primeiros digitos do ID criado para cada commit.

```bash
git show 689aa7f
```

---

## Branch

Listar os branchs

```bash
git branch
```

Criar um novo branch

```bash
git branch nome
```

Deleta um branch

```bash
git branch -d nome
```

---

## Diff

Verifica as mudanças feitas, porém ainda sem commit

```bash
git diff
```

Verifica as mudanças feitas dois commits

```bash
git diff 65421df..4532as4
```

---

## Checkout

Alternar entre os branchs

```bash
git checkout nome-do-branch
```

Criar um novo branch e muda para ele

```bash
git checkout -p nome
```

---

## Merge

O merge junta os trabalhos e gera um merge commit.

```bash
git merge brach-name
```

---

## Rebase

O rebase aplica os commits de outra branch na branch atual.

```bash
git rebase branch-name
```

---

## Desfazer mudanças

Desfazer antes de colocar no stage

```bash
git checkout -- file
```

Desfazer quando esta no stage

```bash
git reset HEAD file
```

Desfazer depois do commit

```bash
git revert 1345c65
```

---

## Stash

Salva as mudanças para trabalho futuro

```bash
git stash
```

Lista tudo que esta no stash

```bash
git stash list
```

Deleta as informações do stash

```bash
git stash drop numero
```

Aplica as modificações salvas sem deletar do stash

```bash
git stash apply numero
```

Aplica a ultima informação já removendo do stash

```bash
git stash pop
```

---

## Tag

Adiciona uma tag a um commit

```bash
git tag -a -m "v0.1.0"
```

---

## Cherry-pick

Trazer apens um commit de outro branch

```bash
git cherry-pick hash
```

---