
**Para remover último commit:**

`git reset HEAD~1` Vai voltar o último commit.

`git push -f` Vai dar um push sem o ultimo commit (- f força a dar o push).

**Renomear último commit:**

`git commit --amend -m "Nova mensagem"`  Esse comando deve ser utilizado caso não tenha sido feito o push.


**Caso o commit já tenha sido feito push:**

`git reset HEAD~1`  para voltar o último commit.

`git add .` Vai adicionar os arquivos para staged.

`git commit -m "Nova descrição do commit"`  Nova descrição para o commit.

`git push -f` Para reenviar o commit.

**Remover uma branch local:**

`git branch -d nome da branch`

> A opção -d excluirá o branch somente se você já fez o push e o merge com o branch remoto. 
Use a opção -D em vez disso se quiser forçar a exclusão do branch, mesmo que você ainda não tenha feito o push e o merge com ele.

**Remover branch remoto:**

`git push origin --delete nomeDaBranch`