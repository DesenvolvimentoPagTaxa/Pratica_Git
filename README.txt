git init 	            --> iniciar
git add .	            --> adicionar/atualizar mudança
git commit -m "message"	--> adicionar um ponto na linha do tempo
git log 	            --> visualizar os pontos na linha do tempo
git status 	            --> informa o status das alterações do projeto
---------------------------------------------------------------
git branch nome_do_branch         -->cria branch 
git checkout nome_do_branch       -->trocar branch
git checkout -b nome_do_branch    --> criar branch e ja troca
---------------------------------------------------------------
* LISTAR branch
git branch
---------------------------------------------------------------
* juntar todo branch 
* trocar primeiro para master

git checkout master
git merge teste
---------------------------------------------------------------
* DELETAR branch
git branch -D teste

*add online
git remote add origin https://github.com/Chih-Yao-Yang/teste.git
git push -u origin master --> primeira vez
git push origin master
* Ou add outro branch
git push origin develop
---------------------------------------------------------------
git clone https://github.com/Chih-Yao-Yang/teste.git

sempre commit na master