git init 	--> iniciar
git add .	--> adicionar/atualizar mudança
git commit -m 'message'	--> adicionar um ponto na linha do tempo
git log 	--> visualizar os pontos na linha do tempo
git status 	--> informa o status das alterações do projeto
---------------------------------------------------------------
git branch 'nome do branch' -->cria branch 
git checkout 'nome do branch' -->trocar branch
git checkout -b 'nome do branch' --> criar branch e ja troca
---------------------------------------------------------------
* Listar branch
git branch
---------------------------------------------------------------
* juntar todo branch 
* trocar primeiro para master

git checkout chih
git merge chih
---------------------------------------------------------------
* Deletar branch
git branch -D chih

*add online
git remote add origin https://github.com/Chih-Yao-Yang/teste.git
git push -u origin master --> primeira vez
git push origin master
*Ou add branch
git push origin develop
---------------------------------------------------------------
git clone https://github.com/Chih-Yao-Yang/teste.git

sempre commit na master