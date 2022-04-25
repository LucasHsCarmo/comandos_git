## Escrever uma boa mensagem de commit

Uma boa mensagem de commit deve conter a descrição do que foi feito e para nos ajudar, podemos utilizar este padrão de escrita das mensagens, vamos aos tipos:

* **fix:** Commits do tipo **fix** indicam que seu trecho de código commitado está solucionando um problema (bug fix).

* **feat** Commits do tipo **feat** indicam que seu trecho de código está incuindo um novo recurso.

* **test** Commits do tipo **test** são utilizados quando são realizadas alterações em testes, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

* **docs** Commits do tipo **docs** indicam que houveram mudanças na documentação, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

### Estrutura do commit

```bash
<tipo>(escopo opcional): <descrição> 
```

### Exemplos

```bash
docs: organizando a estrutura de diretórios
```

```bash
feat: adicionado o novo módulo GKE
```

```bash
fix(vars.tf): corrigindo o default da variavel referente ao type_machine
```