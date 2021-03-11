# explicando funcinamento do branch

## criando uma branch

~~~~bash
git branch nome_da_branch
~~~~

## visualizando as branchs

~~~~bash
git branch
~~~~

## navegando entre as branch

~~~~bash
git checkout nome_da_branch
~~~~

## subindo branch para o repositorio na nuvem(somente uma vez apos pode utilizar git push)

~~~~bash
git branch -u origin nome_da_branch
~~~~

## exemplo de utilização

~~~~bash

git branch nome_da_branch # cria a branch nome da branch

git branch  # mostra as branch muito provavelmente vai ser:
            # main
            # * nome_da_branch

git checkout nome_da_branch # navega até a branch

git add . # adiciona os arquivos

git commit -m nome_do_commit # commita os arquivos

git push -u origin nome_da_branch # ta o push na nuvem da branch

# apartir de agora para enviar para nuvem soh é necessario utilizar git push
~~~~
