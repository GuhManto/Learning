# Learning

## github

Serve para controle de versão 
### Repositório__
-É onde todos os arquivos são armazenados, junto com o histórico de alterações sendo LOCAL (Seu Computardor) ou REMOTO (Na Nuvem)

 ~ Para criar um repositorio se usa 
     `git init`




### Commit__
-"Commitar" algo é salvar o código atual, para que você saiba a alteração que foi feita em relação ao código inicial

 ~ Para Commitar algo você precisa ter os arquivos no "stage"

  : De forma unica sendo " git add + arquivo " 
  ; De forma que adicione tudo de uma vez " git add + . "

 ~ E para fazer o Commit usa

```sh
git commit -m 
```

### Branch__
-Uma branch é uma linha de desenvolvimento separada para não interferir no código principal, util para testar outras funcionalidades

 ~ Para criar e alterar para uma Branch
  : " git checkout -b arquivo "

 ~ Para retornar a Branch principal
  : " git checkout main/master "