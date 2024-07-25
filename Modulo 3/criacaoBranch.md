## Criação da branch no terminal

**Branch** = ramificação da branch master para que possibilite outras pessoas trabalharem simultaneamente. E depois juntarem (merge) as informações, sem que um atrapalhe o outro

## Passo a Passo

1 - Criar a branch usando o comando **git checkout - b (nome da nova branch)**

2 - verifico a criação da branch com git status

3 - Crio uma pasta (ex: modulo 3) e uma nota.md (onde será indicado as anotações ou código) da nova branch

4 - toda modificação realizada é necessario salvar usando os comandos **git add .** , **git commit -m "mensagem de alteração"** e **git status**

5 - Para verificar no VScode a quantidade de branch criadas uso o comando:
**git branch** - irá mostrar o numero de branch (master e adcionais) - quem estiver grifado é a branch atual de trabalho;

6 - para alternar as branch uso o comando: **git checkout (nome da branch)**

### CRIAÇÃO DE BRANCH NO GITHUB

#### é possível criar branch direto no github com as funções branches e ver o número criadas, quem foi e quais alterações;

## Envio da branch local para o repositório remoto/github

Comando git checkout -b (nome da branch) = cria e troca para a nova branch

### Merge Local

#### **Git pull** = atualiza o git e github?

#### **Git Merge** = juntar as informações 'soltas' entre as diferentes branch
**git merge (nome da branch)**