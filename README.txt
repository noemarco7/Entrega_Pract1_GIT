1-INICIALIZAR UN REPOSITORIO
git init

USUARIO Y CORREO
git config --global user.name "Noemi Martinez Couto"
git config --global user.mail "nmc_1988@hotmail.com"

2-AÑADIR TODOS LOS FICHEROS AL REPOSITORIO
git add .

3-SUBIR CAMBIOS
git commit -m "Comienzo del proyecto"

4-PARA VER LOS COMMITS
git log --oneline


5-SUBIR LOS CAMBIOS EN EL GITHUB
git remote add origin https://github.com/noemarco7/Entrega_Pract1_GIT.git

6-ACTUALIZAR EL REPOSITORIO
git push origin master

7-SABER EN QUE RAMA 
git branch

8- CREAR UNA RAMA 
git branch Rama2

9-MOVERSE A LA RAMA QUE NOS INTERESA
git checkout Rama2



**se puede editar el mismo fichero desde distintas ramas, y parece como dos proyectos distintos,
y cada cambio se ve en cada rama.

1. para hacer un merge es necesario  ir a la rama master
2. git merge mas el normbre de la rama que se quiere fusionar
git merge Rama2


**Para clonar el repositorio de github a local
git clone repositorio web de github

