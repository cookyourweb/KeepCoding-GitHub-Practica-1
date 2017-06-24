# Práctica del curso de git, gitHub y Sourcetree


***
![Keepcoding](https://d2vvqscadf4c1f.cloudfront.net/078jf4zQNCjF2CsMPMmR_128x.png)



*Verónica Serna*

  
<verserper@gmail.com>


***

## Ejercicio 1
  


1. **¿Qué comando utilizaste en el paso 11? ¿Por qué?

**
> $ git reset --hard HEAD~1 // Retrocedo un paso y con el --hard se pierden los cambios en el working copy.



2. **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

**
> $ git reflog .


> $ git reset --hard 5b2add1 // Siendo 5b2add1 el identificador del commit (Hash).
Con el reflog puedo ir directamente al último commit y seleccionarlo para hacer el reset del commit a continuación y rehacer el último commit.


3. **El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

**
> No ha dado ningún conflicto, ya que el texto se ha insertado sin problemas y estaban en una lista las ramas.


4. **El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

**
> Si, porque el archivo git-nuestro.md ha sido editado en la misma linea en dos ramas diferentes.


5. **El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

**
> No, ya que se ha añadido el contenido que faltaba pero sin conflictos en el texto.


6. **¿Qué comando o comandos utilizaste en el paso 25?

**
> Primero creo el alias con el siguiente comando: git log --graph --decorate --pretty=oneline
> Luego simplemente llamo al alias con git graph.


7. **El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

**
> No, porque en cada rama teniamos un commit, las ramas no formaban una lista y por lo que git te hace un merge no- ff , producen un nuevo commit automáticamente generado.


8. **¿Qué comando o comandos utilizaste en el paso 27?

**
> git reset HEAD~1 //sin hard no pierdo los cambios en el working copy.


9. **¿Qué comando o comandos utilizaste en el paso 28?**
> git reset --hard HEAD
10. 

**¿Qué comando o comandos utilizaste en el paso 29?

**
> git branch -D title
11. 

10. **¿Qué comando o comandos utilizaste en el paso 30?

**
> git reset --hard 65939cc y a continuacion creo de nuevo la rama: git branch title
12. 

11. **¿Qué comando o comandos usaste en el paso 32?

**
> Primero hago un git reflog, me voy al inicio y copio el identificador.
> git reset 43ae30f
13. 

12.**¿Qué comando o comandos usaste en el punto 33?

**
> Como en el punto anterior en el git reflog busco el punto donde pusimos título al  poema.
git reset  2b7fe37 

