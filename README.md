| Comandos                                                | Descripción |
| :------------------------------------------------------ | :---------- |
| `git init`                                              | Iniciar un repositorio |
| `git config --global user.name "lstabile"`              | registrar un nuevo usuario |
| `git config --global user.email "lstabile@gmail.com"`   | registrar correo electrónico |
| `git config --global init.defaultBranch main`           | Definir el nombre de la rama principal |
| `git add file.txt`                                      | Agrega el archivo al control de versiones |
| `git status -s`                                         | Verificar el estado actual del proyecto |
| `git commit -m "Comentario del Commit"`                 | Realizar un Commit con el mensaje entre comillas |
| `git log --oneline`                                     | Ver los logs resumido en una lína |
| `git remote add origin https://github.com/lstabile/proyecto.git` | Conectarnos con un repositorio remoto |
| `git push -u origin main`                               | Subir el proyecto al respositorio remoto |
| `git clone https://github.com/lstabile/proyecto.git`    | Clonar un repositorio | 
| `git remote -v`                                         | Para ver con que repositorio remoto estamos conectados |
| `echo ".env" >> .gitignore`                             | Ignorar un archivo o carpeta. Se pueden usar wildcards, por ejemplo: *.js |
| `git checkout 73b44ef`                                  | Viajamos al commit con id 73b44ef solo para revisar dado que queda `HEAD detached` |
| `git checkout main`                                     | Volvemos a la rama principal luego del checkout |
| `git reset 73b44ef`                                     | Viajamos al commit con id 73b44ef pero en la rama, de modo que se puede modificar |
| `git reset --hard 73b44ef`                              | Viajamos al commit pero desaparecen los archivos locales que fueron creados posteriores al mismo |
| `git reflog`                                            | Muestra todos los cambios realizados en el proyecto. Sirve para encontrar el id de un commit posterior |
| `git pull origin NOMBRE_RAMA`                           | Restaurar la última versión remota |
| `git revert 73b44ef`                                    | Deshacer los cambios realizados por un commit anterior creando un commit nuevo |
| `git rm --cached FILENAME`                              | Eliminar un archivo que ya fue se ha hecho commit |
| `git branch`                                            | Ver en que rama estamos |
| `git branch NOMBRE_RAMA`                                | Crear una rama con el nombre especificado |
| `git checkout NOMBRE_RAMA`                              | Movernos a una rama |
| `git log --oneline --graph`                             | Ver los logs resumidos con mejor visualización de ramas |
| `git push --set-upstream origin NOMBRE_RAMA`            | Subir commits de la rama al repositorio remoto |
| `git banch -d NOMBRE_RAMA`                              | Eliminar una rama |
| `git merge NOMBRE_RAMA`                                 | Unir ramas. Nos posicionamos en la que recibe los cambios |
| `git tag NOMBRE_VERSION -m "Comentario del tag"`        | Etiquetar una versión del proyecto |
| `git tag`                                               | Listar todos los tags del proyecto |
| `git tag -a NOMBRE_TAG ID_COMMIT -m "Comentario"`       | Etiquetar un commit anterior con el id especificado |
| `git tag -d NOMBRE_TAG`                                 | Eliminar un tag |
| `git push --tag`                                        | Subir los tags al repositorio remoto |
| `git remote -v`                                         | Verificar con servidor remoto estamos conectados | 
| `git pull`                                              | Descargar los cambios realizados en el repositorio remoto |


