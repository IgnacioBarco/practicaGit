* **�Qu� comando utilizaste en el paso 11? �Por qu�?**
	git reset --hard HEAD~1
	para que recuperase lo que hay en el repositorio y no en la working

* **�Qu� comando o comandos utilizaste en el paso 12? �Por qu�?**
	hacemos un git reflog, apuntamos la ref de el ultimo commit hecho modifificando el archivo
	y hacemos un  git reset --hard 8066df8

* **El merge del paso 13, �Caus� alg�n conflicto? �Por qu�?**
	git merge master
		Dice que ya est� actualizado: "Already up to date."

* **El merge del paso 19, �Caus� alg�n conflicto? �Por qu�?**
	da errores porque hay modificaciones en las mismas lineas:
		git checkout styled
		git merge htmlify
			Auto-merging git-nuestro.md
			CONFLICT (content): Merge conflict in git-nuestro.md
			Automatic merge failed; fix conflicts and then commit the result.
	
* **El merge del paso 21, �Caus� alg�n conflicto? �Por qu�?**
	No ha dado errores:
		$ git merge styled
			Updating 8d36eff..5a60f43
			Fast-forward
		 	git-nuestro.md | 20 ++++++++++----------
	 		1 file changed, 10 insertions(+), 10 deletions(-)

* **�Qu� comando o comandos utilizaste en el paso 25?**
	git log --graph --pretty=oneline --decorate

* **El merge del paso 26, �Podr�a ser fast forward? �Por qu�?**
	si, por que no hay ningun nodo que se pudiese perder

* **�Qu� comando o comandos utilizaste en el paso 27?**
	git reset HEAD~1

* **�Qu� comando o comandos utilizaste en el paso 28?**
	git checkout -- git-nuestro.md

* **�Qu� comando o comandos utilizaste en el paso 29?**
	git branch -D title

* **�Qu� comando o comandos utilizaste en el paso 30?**
	git reset --hard 132d400

* **�Qu� comando o comandos usaste en el paso 32?**
	git reset --hard 8d36effc5f128c03d52263dae706d5287cade2c5

* **�Qu� comando o comandos usaste en el punto 33?**
	git reset --hard 132d400e5d71c8b91bae9a2e70d30dc04cd534c8


