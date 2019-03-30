**a. Control de versiones (VC)**
Es un sistema que ayuda a dar seguimientos a todos los cambios que se van haciendo a lo largo del tiempo en un proyecto, con el fin de ante posibles cambios se puedan recuperar versiones antiguas, entre otros.
https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones

**b. Control de versiones distribuido (DVC)**
Siguiendo con la idea anterior, el que sea “distribuido” facilita a los desarrolladores de software mantener todos los cambios sincronizados sin la necesidad de de compartir una misma red. 
https://es.wikipedia.org/wiki/Control_de_versiones_distribuido

**c. Repositorio remoto y Repositorio local**
En Git es considerado repositorio una carpeta que contiene todas las versiones del proyecto, incluyendo la documentación. Estos pueden ser públicos o privados.
Un repositorio local es un directorio que se encuentra alojado en el ordenador del desarrollador, mientras que el repositorio remoto es el que está en un software, como GitHub. El repositorio local se usa para luego subir las versiones al repositorio remoto.
https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos

**d. Copia de trabajo / Working Copy**
Se le dice copia de trabajo al repositorio completo y localizado que tiene que tener cada usuario al momento de trabajar en un proyecto distribuido. 
https://www.thomas-krenn.com/en/wiki/Git_Basic_Terms 

**e. Área de Preparación / Staging Area**
Corresponde a un repositorio intermedio utilizado para la carga temporal de datos en un proceso ETL (Extraer, transformar y cargar). Por lo general contiene datos solo cuando se realiza el proceso de carga del datawarehouse (repositorio unificado para todos los datos que recogen los diversos sistemas de una empresa)
https://enfoquepractico.com/glosario/

**f. Preparar Cambios / Stage Changes**
Se realiza luego de la fase de modificación de un archivo en un repositorio, en la cual se preparan los cambios para concluir de forma  efectiva el proceso de guardado de modificaciones. En esta fase es necesario utilizar el comando “git add” y “git status” para corroborar que los cambios se encuentran “preparados”.

https://git-scm.com/book/es/v1/Fundamentos-de-Git-Guardando-cambios-en-el-repositorio 

**g. Confirmar cambios / Commit Changes**
Luego de realizar las modificaciones al área de preparación, se confirman los cambios. Cualquier cosa que este sin preparar no se incluirá en esta confirmación y se mantendrán como modificados en el disco.
https://git-scm.com/book/es/v1/Fundamentos-de-Git-Guardando-cambios-en-el-repositorio

**h. Commit**
El comando commit se utiliza para guardar cambios en el repositorio local.
https://git-scm.com/docs/git-commit 

**i. clone**
Se usa para obtener una copia de un repositorio existente
https://git-scm.com/book/es/v1/Fundamentos-de-Git-Obteniendo-un-repositorio-Git 

**j. pull**
Se utiliza para recuperar y unir de forma automática la rama remota con la rama actual, en otras palabras, para unir todos los cambios que se han hecho en el repositorio local trabajando.
https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos

**k. push**
Se utiliza para enviar los cambios que se han hecho en la rama principal de los repertorios remotos que están asociados con el directorio con el que se está trabajando.
https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos

**l. fetch**
Este comando recupera información y la coloca en el repositorio local, en otras palabras, busca en un repositorio remoto todos los objetos que no se encuentran en el directorio local en el que se trabaja.
https://www.hostinger.es/tutoriales/comandos-de-git

**m. merge**
Este comando es utilizado para unir una rama con otra rama activa.
https://www.hostinger.es/tutoriales/comandos-de-git

**n. status**
Este comando muestra los distintos estados de los archivos del directorio del desarrollador; como cuales se encuentran modificados, sin seguimientos o sin confirmación.
https://git-scm.com/book/es/v2/Appendix-B%3A-Comandos-de-Git-Seguimiento-B%C3%A1sico

**o. log**
El comando log nos mostrara una lista de commits en una rama con todos sus detalles. 
https://www.hostinger.es/tutoriales/comandos-de-git

**p. checkout**
Este comando se utiliza para crear ramas o cambiarlas entre ellas.
https://www.hostinger.es/tutoriales/comandos-de-git

**q. Rama / Branch**
En Git existe una rama principal de desarrollo llamada master, en la que a partir de esta se va a continuar trabajando. El comando branch se utiliza para listar, borrar o crear ramas. 
https://www.hostinger.es/tutoriales/comandos-de-git

**r. Etiqueta / Tag**
En Git existen dos tipos de etiquetas, las ligeras que es muy parecida a una rama que no cambia y las etiquetas anotadas que son almacenadas como objetos completos en la base de datos de Git. El comando tag va a lista las etiquetas en orden alfabético.
https://git-scm.com/book/es/v1/Fundamentos-de-Git-Creando-etiquetas
