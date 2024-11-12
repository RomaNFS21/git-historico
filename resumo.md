# Resumo dos Exercícios

## Exercício 1

Foi criada uma pasta chamada **git-historico**. Abriu-se o **CMD** no diretório da pasta criada e foi executado o comando *git init* para transformar a pasta em um repositório. Após isso, foram criados três arquivos:

- notas.txt
- resumo.md
- tarefa.txt

Em seguida, foram feitas modificações em cada arquivo, realizando um commit individual para cada alteração. Após os commits, foi executado o comando para visualizar o histórico das modificações.

## Exercício 2

Criação da pasta **projeto-reversao**, que foi configurada como repositório. Em seguida, foi criado o arquivo *experimento.txt*, alterado seu conteúdo e realizado o commit.

Foram feitas novas modificações sem commit, mas desejava-se voltar ao estado anterior do arquivo. Para isso, foi utilizado o comando `git restore`.

Novas modificações foram realizadas, comitadas e, em seguida, o comando `git reset --hard` foi usado para voltar ao estado do último commit.

## Exercício 3

Criação da pasta **branch-test**, que foi configurada como repositório, e criação do arquivo *principal.txt* com informações, seguido do primeiro commit.

Em seguida, foi criada uma branch chamada *melhorias*, na qual foi criado o arquivo *novidades.md* e realizado um commit nesta branch.

Voltando à branch *main*, foi feita uma modificação no arquivo *principal.txt*, com novas informações, e realizado o commit dessa alteração. Após isso, foi feito o merge entre as duas branches.
