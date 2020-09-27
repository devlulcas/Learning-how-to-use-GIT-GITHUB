# ESTE REPOSITÓRIO TEM COMO ÚNICO OBJETIVO SERVIR COMO UM BLOCO DE ANOTAÇÕES PARA MIM MESMO

# Começo
`git init` = inicia um repositório

# Adicionando arquivos / Salvando alterações 
`git add arquivo.txt` = adiciona algo ao repositório // para adicionar multiplas alterações e dar um só commit para elas use *git add .*

`git commit -m "Mensagem" arquivo.txt` = cria um ponto na história do nosso código

# Removendo arquivos do repositório git
`git rm arquivo.txt` = remove arquivo/diretorio 

# Informações sobre o repositório
`git log` = mostra um log de commits // se você não estiver conseguindo sair deste comando mova seu cursor até *exit* e pressione a tecla *q*

`git status` = mostra o estado dos seus arquivos

`git show` = mostra as ultima alterações realizadas

# Uso das branchs (Ramos)
`git branch nome_branch` = cria nova ramificação do projeto

`git branch` = mostra todas as nossas branchs

`git branch -D nome_branch` = deleta a branch sem dó 

`git checkout nome_branch` = te leva até a branch especificada

`git merge nome_branch` = mistura a branch citada com a branch que você está

*LÁÁÁÁ NAS NUVENS - GITHUB*
`git remote add origin https://url.com` = adiciona um repositório externo

`git remove -v` =  serve para ver seus repositórios remotos

`git push` = empurra seu repositório local para o github // na primeira vez você precisa criar a branch master no github com *git push -u origin master*

`git config credential.helper store` = salva suas credenciais