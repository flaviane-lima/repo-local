
# Prática Git/GitHub

Neste repositório estou executando comandos git para ter uma base sólida de utilizar seus comandos. Estarei listando cada um e suas respectiva funcionalidade no git sendo que localmente e no envio para o github


# 📚 Documentação 

- [documentação Git](https://git-scm.com/search/results?search=readme&language=pt_BR)
- [documentação GitHub](https://docs.github.com/pt)

# 💻 Comandos
Os comando são executados no terminal Git bash. Antes é necessário criar uma pasta localmente no desktop, depois você deve entrar na pasta e abrir o terminal e começar a executar os comandos

#### Criar um repositório local

```
 mkdir repo-local

``` 

#### Entrando na pasta do repositório

```
 cd repo-local

```

#### Inicializar um repositório Git repositório local

```
 git init

```

#### Verificar o status do repositório


```
 git status

```

#### Criar um arquivo readme

```
 touch README.md

```

#### Adicionar arquivos ao índice(stating area)

```
 git add README.md

```

#### Salvar arquivos modificados ao índice

```
 git commit -m"Descreva a alteração"

```

#### Verificar alteração feita

```
 git log

```

#### Adicionar todos os arquivo ao índice

```
 git add.

```

#### Alteração da mensagem do commit anterior

```
git commit --amend -m "reescreva a mensagem"

```

#### Desfazer um commit anterior

```
 git reset --soft <HEAD>

 ```

📝 **observação**: este HEAD aparece quendo é executado git log
Copie e cole o HEAD do commit que deseja manter e execute o comando. Mas mantém os arquivos no indice para fazer commit

```
 git reset -- mixed <HEAD>

 ```

📝 **observação**: Isso desfaz o commit e remove os arquivos do índice, **mas mantém as alterações no diretório de trabalho**. Você precisará adicioná-las novamente com `git add` antes de criar um novo commit.  

```
 git reset --hard <HEAD>

 ```
📝 **observação**: Este comando desfaz o commit e **remove todas as alterações dos arquivos**, tanto do índice quanto da área de trabalho.  
 Essa ação é irreversível! Use com cuidado.  



#### Visualizar todas alterações do repositório

```
 git flog

```

🚨 **OBS:** Estes comandos até agora foram feitos locamente no desktop. Nos próximos pontos, será feitos comando para repositório remoto

#### Vincular o repositório local para o remoto

```
 git remote add origin <URL>

```

#### Enviar alteração da branch main local para branch main do repositório remoto

```
 git push -u origin main

```

#### Abaixando alterações do remoto para local

```
git pull

```

#### Adicionar arquivos ao índice(stating area)

```
$ git add README.md

```

#### Salvar arquivos modificados ao índice

```
$ git commit -m"Descreva a alteração"

```

#### Verificar alteração feita

```
$ git log

```

#### Adicionar todos os arquivo ao índice

```
$ git add.

```




 





