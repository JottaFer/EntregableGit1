Describe que hacen los siguientes comandos de git, escribe su descripcion al frente en una sola linea.

git status: Este comando se usa para obtener el estado actual del repositorio

git clone: se utiliza para crear un repositorio existente

git pull: Se utiliza para fusionar los cambios remotos en un repositorio local
 # En resumen, git pull sirve para actualizar el repositorio local con los últimos cambios realizados por otros colaboradores en el

git checkout: Se utiliza en Git para cambiar entre ramas o versiones de un repositorio
# Es importante tener en cuenta que al cambiar de rama o versión con "git checkout", se perderán los cambios no guardados en el directorio de trabajo.

git log: se utiliza en Git para ver el historial de commits en un repositorio
# Además, el comando "git log" ofrece varias opciones para personalizar la salida del historial de commits, como:oneline Muestra cada commit en una sola línea, con el identificador único y el mensaje del commitgraph Muestra el historial de commits en forma de gráfico mostrando las ramas y las fusionesauthor Filtra los commits por autor específicosince y until Filtra los commits por fecha específica o rango de fechas.

git branch: Se utiliza en Git para administrar y visualizar las ramas en un repositorio
# Es importante tener en cuenta que el comando "git branch" solo administra las ramas en el repositorio local. Para ver y administrar las ramas remotas, se utilizan otros comandos como "git remote" y "git push".

git add: Se utiliza en Git para agregar cambios al área de preparación (staging area) antes de realizar un commit
# Después de agregar los cambios al área de preparación con "git add", puedes realizar un commit utilizando el comando "git commit" para guardar los cambios en el repositorio.

git commit: Se utiliza en Git para guardar los cambios realizados en el área de preparación (staging area) en el repositorio
# Después de ejecutar el comando "git commit", los cambios se guardarán en el repositorio y se creará un nuevo commit con un identificador único. Estos commits formarán el historial de cambios del repositorio y se pueden ver utilizando el comando "git log".

git push: Se utiliza en Git para enviar los cambios locales a un repositorio remoto
# Si la rama remota no existe en el repositorio remoto, Git creará una nueva rama con el mismo nombre y enviará los cambios. Si la rama ya existe en el repositorio remoto, Git actualizará la rama con los cambios locales.

git merge: Se utiliza en Git para combinar los cambios de una rama con otra rama.
# Después de realizar un merge, los cambios de la rama fusionada se reflejarán en la rama actual y se creará un nuevo commit que representa la fusión.
