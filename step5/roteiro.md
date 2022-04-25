## Do init até o push do repositório

### Nome do projeto

```bash
mkdir <project>
touch <project/file.yaml>
```

### Inicializando repositório

```bash
git init
```

**OBS:** No terminal, digite `ls -lha` , notasse o diretório oculto **.git** que é criado após executar o comando a cima, mencionado.

### Branch

```bash
# verifica qual a branch estou
git branch

# muda de branch (master/main) para que estou criando
git checkout -b <my_branch>
```

### Adicionar o arquivo no INDEX

```bash
git status
git add <project/file.yaml>
git status
```

### Adicionar o arquivo no HEAD

```bash
# adiciona todos os arquivos do INDEX para HEAD
git commit -am "mensagem descritiva do commit" 
```

OU

```bash
# criado com alias
git c "mensagem descritiva do commit"
```

### Mudanças para o repositório Git remoto

```bash
# adiciona ao servidor remoto a branch específicada
git push origin <my_branch>
``` 