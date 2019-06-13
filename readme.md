* **¿Qué comando utilizaste en el paso 11? ¿Por qué?**
	git reset --hard HEAD~1
	para que recuperase lo que hay en el repositorio y no en la working

* **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
	hacemos un git reflog, apuntamos la ref de el ultimo commit hecho modifificando el archivo
	y hacemos un  git reset --hard 8066df8

* **El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
	git merge master
		Dice que ya está actualizado: "Already up to date."

* **El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
	da errores porque hay modificaciones en las mismas lineas:
		git checkout styled
		git merge htmlify
			Auto-merging git-nuestro.md
			CONFLICT (content): Merge conflict in git-nuestro.md
			Automatic merge failed; fix conflicts and then commit the result.
	
* **El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
	No ha dado errores:
		$ git merge styled
			Updating 8d36eff..5a60f43
			Fast-forward
		 	git-nuestro.md | 20 ++++++++++----------
	 		1 file changed, 10 insertions(+), 10 deletions(-)

* **¿Qué comando o comandos utilizaste en el paso 25?**
	git log --graph --pretty=oneline --decorate

* **El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
	si, por que no hay ningun nodo que se pudiese perder

* **¿Qué comando o comandos utilizaste en el paso 27?**
	git reset HEAD~1

* **¿Qué comando o comandos utilizaste en el paso 28?**
	git checkout -- git-nuestro.md

* **¿Qué comando o comandos utilizaste en el paso 29?**
	git branch -D title

* **¿Qué comando o comandos utilizaste en el paso 30?**
	git reset --hard 132d400

* **¿Qué comando o comandos usaste en el paso 32?**
	git reset --hard 8d36effc5f128c03d52263dae706d5287cade2c5

* **¿Qué comando o comandos usaste en el punto 33?**
	git reset --hard 132d400e5d71c8b91bae9a2e70d30dc04cd534c8


