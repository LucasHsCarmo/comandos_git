## Revert

Comandos referentes a possíveis correções:

* 1º Exemplo:

```bash
git add <project/file.yaml>
git status

# retira as modificações INDEX e devolve para o WORK DIR
git reset
git status
```

* 2º Exemplo:

```bash
git add
git status

# a ponta para o último commit feito, excluindo qualquer alteração adicionada no WORK DIR
git reset --hard 
git status
```

* 3º Exemplo:

```bash
git add <project/file.yaml>
git status
git commit -m "digitei a mensagem errada"

# corrigi a mensagem que está escrita errada
git commit --amend
git log
```

* 4º Exemplo:

```bash
git add <project/file.yaml>
git status

# retira as modificações INDEX e devolve para o WORK DIR
git reset
git status

# mostra o arquivo que será removido
git clean -n

# remove o arquivo
git clean -f
```