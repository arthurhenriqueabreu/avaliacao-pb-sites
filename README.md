# avaliacao-jp

git init
-Usamos para transformar um diretório/projeto em um repositório através do arquivo .git gerado

git status
-Exibe informações como por exemplo, a branch onde você está, se a branch selecionada está igual a branch main, se há algo para comitar....

git add <nome do arquivo/p>
-Adiciona o arquivo modificado/criado ao "stage", o que fica no stage pode ser implementado no repositório através de um commit

git -rm cached <arquivo>
-Remove o arquivo selecionado do "stage", ou seja, nâo vai pro próximo commit(a nâo ser que use o git add novamente 😜)

git branch
-Lista todas as branchs locais existentes no repositório (se adicionar no final:" -r", lista as branchs remotas, se adicionar " -a", lista todas as remotas e locais)

git checkout <nome da branch>
-Navega entre as branchs através do nome

git checkout -b <nome da branch>
-Cria uma branch e seleciona ela através de um único comando

git commit -m <descrição>
-Faz o commit, ou seja, todas as mudanças do "stage" são adicionadas ao repositório juntamente com uma descrição determinada pelo usuário

git merge <branch>
-Faz merge com a branch atual e a branch informada pelo usuário

git push
-Os commits do repositório local são enviados ao repositório remoto

git branch -D <branch>
-Exclui a branch local informada pelo usuário

git fetch
-Baixa os objetos e referências da branch remota

git pull
-Baixa os objetos e referências da branch remota e mescla com a branch local

