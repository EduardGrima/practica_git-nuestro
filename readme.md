##REspuestas práctica 1

#Paso 11:
<code>git reset --hard HEAD~1</code>, el <code>--hard</code> es para que modifique el Working
copy y  el <code>HEAD~1</code> para retroceder al commit padre de el que estamos

#paso 12:
He introducido <code>git reflog</code> par buscar el identificador del commit que habiamos 
desecho, después he ejecutado <code>git reset Nª commit abreviado.

#paso 13:
No me ha dado ningún conflicto!! No debía haber guardado los cambiados, por que, me lo tenía
que haber dado, dándome los cambios para que escoja. He repasado todos los commits i no me
sale el cambio.

#paso 21:
No me ha dado ningún conflicto, creo que es por que el texto es el mismo , lo que hemos
incluido es marcado el cual ha incorporado. He comprobado el archivo con nano y tiene los
cambios hechos en la rama styled.

#paso 25:
De hacer servir, he hecho servir <code>git graph</code> que es el alias que ya tenía
configurado. La intrucción en si sería <code>git log --graph --decorate --pretty=oneline</code>

#paso 26:
si que podría ser fast forward, antes de creaar title, la rama master ha absorbido a con 
un merge a htmlify y styled. asi que si hhace un merge fast forward no perderia la referencia
a ninguno de sus commits.

#paso 27:
<code> git reset HEAD~1</code>

#paso 28:
<code> git restore git-nuestro.md</code>

#paso 29:
<code>git branch -D title</code> con d minúscila no me dejaba.

#paso 30:
<code>git reflog</code> para buscar el commit
<code>git reset --hard <Nªcommit></code>

#paso 32:
<code>git log</code> para buscar el identificador del primer commit con la descripción 
Creación del git-nuestro.md.
<code>git reset --hard "identificadorcommit"</code>

#paso 33:
<code>git reflog</code> para poder ver todos los commits.
<code>git reset --hard "identificador commit"</code> 
