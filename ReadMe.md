# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

*Para borrar todo cuanto habia hecho volviendo un paso hacia atrás. El `--hard` para que no se guardara en el working copy.*

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reset --hard (serie del último commit)` 

*Parecido al anterior, pero con el número del último commit para que gracias a un git relflog, poder volver al paso que me encontraba antes de borrar*

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

*No porque el commit donde se encuentran guardados los cambios del archivo don-quijote se encuentran por encima del commit de la rama master*

--

**4. El merge del 19, ¿Causó algún conflicto? ¿Por qué?**

*Si, porque ambas ramas se encuentran a la misma altura, por lo que es necesario arreglar los cambios y crear un commit superior*

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

*No por el mismo motivo que el merge del paso 13*

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph`

--

**7. El merge del paso 26, ¿Podría ser fast foward? ¿Por qué?**

Si podría, pero entonces no tendriamos total control ni noción de las características de la rama. Además de que quedará más claro en el historial*

--

**8. ¿Que comando o comandos utilizaste en el paso 27?**

`git reset --soft HEAD~1`

--

**9. ¿Que comando o comandos utilizaste en el paso 28?**

`git reset --hard HEAD~1`

--

**10. ¿Que comando o comandos utilizaste en el paso 29?**

`git branch -D title`

--

**11. ¿Que comando o comandos utilizaste en el paso 30?**

`git reset --hard (código del commit merge title)`

--

**12. ¿Que comando o comandos usaste en el paso 32?**

`git reset --hard (código del 1 commit)`

--

**13. ¿Que comando o comandos usaste en el punto 33?**

`git reset --hard (código del último commit)`
