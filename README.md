# ComandosGit
	--- Aula 01 ---

O que é GIT?
	Git - Sistema de versionamento de código, que guarda os registros de versão como snapshots do estado do projeto,
		além da referência/caminho para essa foto.

	--- Aula 2 ---

Abrir CMD e ver versão -> git --version
Criar pasta no Vs Code -> git-digital_course
	git config --global user.name "Luiz"
	git config --global user.email luizfelipeamancio@gmail.com

	--- Aula 3---

git remote add origin nomeRepositorio -> Pega repositório remoto
git clone 'hash do projeto do github' -> Pegar repositório no Git e jogar na sua máquina 
git init -> Inicia repositório Git


	--- Aula 4 ---

git status -> estado do repositório (Untracked, Unmodified, Modified e Staged)
		Unmodified -> Arquivo não modificado
		Modified - Arquivo foi modificado
		Staged -> Arquivo modificado vai ser preparado para o commit

git add arquivo -> Adicionar arquivo modificado para estado Staged 


	--- Aula 5 ---

git diff -> Mostra as alterações do repositório 
git commit -m "mensagem" -> Salva o estado do projeto


	--- Aula 6 ---

git log -> explorar o histórico do repositório
git restore arquivo -> retorna estado do repositório

	--- Aula 7 ---

git remote -> ver repositório remoto
git push origin nomeBranch -> adicionar no repositório remoto(github)
git pull -> pega o que tem de novo no repositório remoto e adiciona na sua máquina
git fetch -> pega o que tem de novo mas não adiciona ainda na sua máquina
git diff origin/nomeBranch -> mostra o que falta na sua máquina, so dar um git pull para pegar o que falta.   


	--- Aua 9 ---
git branch nomeBranch -> Cria nova branch
git log --oneline --decorate -> pra descobrir qual branch vc esta
git checkout nomeBranch -> Muda para branch escolhida


	--- Aula 10 ---

git merge nomeBranch2 -> Recebe o que há de diferente entre branchs.