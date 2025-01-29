RESPUESTAS:

¿Qué comando utilizaste en el paso 11? ¿Por qué? 

git reset --hard HEAD~1 porque hay que perder los cambios guardados en el working copy. 

 

¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 

git reset --hard ea58c17 porque mueve además del puntero de la rama actual (HEAD) al commit especificado, y además se actualiza el directorio de trabajo y el área de preparación (staging area) para reflejar exactamente el estado de ese commit. 

 

El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?  

No causó conflicto porque no hay hay discrepancias entre las versiones del archivo git-nuestro.md en las dos ramas que se está intentando fusionar.  

  

El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué? 

Sí causó conflicto porque en este caso sí hay hay discrepancias entre las versiones del archivo en las dos ramas que se está intentando fusionar. 

 

El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué? 

No causó conflicto porque es un merge Fast-forward. 

 

¿Qué comando o comandos utilizaste en el paso 25? 

git log--graph--decorate--pretty=oneline 

 

El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

No porque las ramas no forman una lista por lo que es necesario en este caso producir un nuevo commit. 

 

¿Qué comando o comandos utilizaste en el paso 27? 

git reset HEAD~1 

 

¿Qué comando o comandos utilizaste en el paso 28? 

git reset --hard HEAD~1 

 

¿Qué comando o comandos utilizaste en el paso 29? 

git branch -D title 

 

¿Qué comando o comandos utilizaste en el paso 30? 

git reset –-hard 671ab48 

 

¿Qué comando o comandos usaste en el paso 32? 

git reset --hard 46ba3b0 

 


¿Qué comando o comandos usaste en el punto 33? 

git reset --hard 671ab48 

 

 
