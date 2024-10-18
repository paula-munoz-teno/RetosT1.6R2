#Cómo subir un proyecto a Git Hub

La subida de un proyecto a git cumple los siguientes pasos generales: 

Antecedentes: se sobreentiende que ya hemos creado el proyecto con
git clone o git init


0. GIT STATUS: valoro cómo está mi repositorio

1. GIT ADD: paso el doc de zona de trabajo a stage (marco los archi
vos que quiero subir)Fase stage

2. GIT STATUS:ver estado 
Nos debe decir que los cambios están preparados para ser comitados

3. GIT COMMIT -M" ": Comitar los cambios: subir los cambios de stage al repo local 
Importante poner el mensaje descriptivo

4. GIT StATUS
Your branch is ahead (Tu versión del local es más
nueva que la de la nube) y se debe a un commit
Me debe devolver nothing to commit 

5. Git PUSH
Los cambios del local al remoto (Hay que tener internet) 
Al hacerlo, si refresco git hub se actualiza 

6. GIT STATUS
