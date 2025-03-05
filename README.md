# mi-primer-repositorio

Saul Stiven Escobar Gomez

Git es una herramienta que guarda el historial de cambios en el código para que los desarrolladores puedan trabajar juntos sin dañarsen los cambios. Es distribuido, lo que significa que cada uno tiene una copia completa en su computador y puede trabajar sin estar siempre conectado, Con Git tambien se puede crear ramas para trabajar en diferentes tareas sin que se mezclen, y después unirlas cuando estén listas.por otro lado GitHub, es una plataforma donde subes tus repositorios para que otros colaboren, y tiene herramientas como "issues" para organizar tareas o reportar errores y tambien puedes usar GitHub para automatizar pruebas y mantener documentación.

Git tiene muchas ventajas, como permitir trabajar offline, mantener un historial completo de cambios y facilitar la colaboración sin miedo a sobrescribir trabajo ajeno. Para usar Git, creas un repositorio con git init, y puedes conectarlo a GitHub con comandos como git remote add y git push. Los comandos básicos incluyen git add para añadir cambios, git commit para guardarlos, git push para subirlos a GitHub, y git pull para obtener actualizaciones.

Los repositorios pueden ser locales, en tu máquina, o remotos, en plataformas como GitHub, y pueden ser públicos o privados según quieras que otras personas los vean. Las claves SSH te permiten conectarte de forma segura sin tener que ingresar tu contraseña cada vez que interactúas con GitHub.

git init: Este comando es como darle vida a tu proyecto en Git. Crea un repositorio en la carpeta en la que estás trabajando, para empezar a seguir los cambios de tu código.

git clone <URL>:copia todo el proyecto (con su historial de cambios) a tu máquina local, para que puedas empezar a modificarlo.

git add <archivo>: Después de hacer cambios en un archivo, usas este comando para decirle a Git que el archivo esta listo.

git commit -m "mensaje": Es como "guardar" tu trabajo. Este comando toma todos los cambios que agregaste con git add y los guarda oficialmente en el historial de Git, con un mensaje que explica qué hiciste.

git push: Después de haber guardado tus cambios con un commit, usas este comando para subir esos cambios al repositorio remoto (como GitHub), para que otros puedan verlos o trabajar sobre ellos.

git pull: Si estás trabajando en equipo, este comando sirve para traer los cambios que otros hayan subido al repositorio remoto. Así tu proyecto local se pone al día con lo que ha pasado en el proyecto compartido.

git status: Este comando es como pedirle a Git un resumen de lo que está pasando en tu proyecto. Te muestra si tienes archivos modificados, si ya están listos para hacer commit, o si te falta hacer algo.

git branch: Aquí es cuando quieres ver las diferentes ramas de tu proyecto. Las ramas son como versiones separadas donde puedes trabajar en nuevas características sin afectar el trabajo de los demás. También te permite crear o eliminar ramas cuando lo necesites.

//PREGUNTAS


1. ¿Qué es Git y cuál es su función en el desarrollo de software? 
Git es un sistema de control de versiones distribuido que permite gestionar y seguir los cambios realizados en el código fuente a lo largo del tiempo. Su función principal es permitir a los desarrolladores colaborar en proyectos sin sobrescribir el trabajo de los demás, facilitando la creación de versiones y el historial del código, lo que facilita la revisión y el manejo de errores. 

2. ¿Cómo se diferencia Git de otros sistemas de control de versiones? 
Git se diferencia de otros sistemas de control de versiones, como Subversion (SVN) o CVS, principalmente por ser distribuido. Esto significa que cada desarrollador tiene una copia completa del repositorio en su máquina local, lo que le permite trabajar sin conexión a Internet. Otros sistemas de control de versiones suelen ser centralizados, lo que implica que el código reside en un servidor central y los usuarios necesitan estar conectados para realizar cambios. 

3. ¿Qué es el branching en Git y cómo ayuda en el desarrollo de software? 
El branching (ramificación) en Git permite crear ramas paralelas dentro de un proyecto. Cada rama puede representar una funcionalidad o característica específica. Esto permite que diferentes partes del equipo trabajen en paralelo sin interferir en el trabajo de los demás. Después, las ramas pueden fusionarse cuando el trabajo en ellas esté listo. 

4. ¿Cuál es la diferencia entre Git y GitHub? 
Git es un sistema de control de versiones, como ya mencionamos, que gestiona el historial de cambios de un proyecto. GitHub, por otro lado, es una plataforma en línea que aloja repositorios de Git de manera remota. Además de servir como repositorio remoto, GitHub ofrece herramientas de colaboración como problemas (issues), pull requests, wikis, entre otras. 

5. ¿Cuáles son las principales características de GitHub? 
Las principales características de GitHub incluyen: 
Alojamiento de repositorios Git: Facilita la gestión de código en la nube. 
Control de versiones distribuido: Almacena el historial de cambios y versiones. 
Colaboración: A través de "issues", "pull requests", "forks", y "reviews". 
Integración continua: Herramientas para automatizar pruebas y despliegues. 
Gestión de proyectos: Tableros de tareas y seguimiento. 
Documentación: Puedes alojar wikis y leerme.md para explicar el proyecto. 

6. ¿Qué ventajas tiene usar Git en comparación con otros métodos tradicionales de guardar versiones de archivos? 
Las principales ventajas de Git incluyen: 
•	Historial completo y trazabilidad de todos los cambios realizados. 
•	Trabajo offline gracias a su naturaleza distribuida. 
•	Ramificación y fusión fácil para gestionar tareas o características separadas. 
•	Colaboración eficiente sin riesgo de sobrescribir cambios de otros. 
•	Eficiencia en términos de espacio y velocidad, incluso en repositorios grandes. 

7. ¿Qué es un repositorio en Git y cómo se crea uno? 
Un repositorio en Git es un lugar donde se guarda el historial completo del proyecto, incluyendo todos los archivos y versiones anteriores. Se puede crear un repositorio en Git con el siguiente comando: 
git init 
Este comando inicializa un repositorio vacío en la carpeta donde se ejecute. 

8. ¿Cómo se crea un repositorio en GitHub y cómo se conecta con Git localmente? 
Para crear un repositorio en GitHub: 
Inicia sesión en GitHub y haz clic en "New" para crear un nuevo repositorio. 

Dale un nombre, una descripción (opcional) y decide si será público o privado. 
Una vez creado, GitHub te dará las instrucciones para conectar tu repositorio local. Los pasos básicos son: 
git remote add origin <URL-del-repositorio> 
git push -u origin master 

9. ¿Cuáles son los principales comandos de Git y qué hacen? 
Algunos de los comandos básicos son: 
git init: Crea un nuevo repositorio. 
git clone <URL>: Clona un repositorio remoto. 
git add <archivo>: Añade cambios al área de preparación (staging area). 
git commit -m "mensaje": Realiza un commit con los cambios añadidos. 
git push: Sube los cambios al repositorio remoto. 
git pull: Baja los cambios desde el repositorio remoto. 
git status: Muestra el estado de los archivos (modificados, añadidos, etc.). 
git branch: Muestra o crea ramas. 

10. ¿Cómo funcionan los issues en GitHub y para qué se utilizan? 
Los issues en GitHub son una herramienta para realizar seguimientos de tareas, errores o mejoras dentro de un proyecto. Los miembros del equipo pueden crear issues, asignar tareas, añadir etiquetas y realizar comentarios sobre los mismos. Es útil para la organización y gestión del proyecto. 

11. ¿Qué es un repositorio y cuáles son sus tipos (local, remoto, público, privado)? 
Un repositorio es un directorio donde se almacena todo el código y su historial. Los tipos son: 
Local: Repositorio en tu máquina local. 
Remoto: Repositorio alojado en un servidor externo (ej. GitHub). 
Público: Repositorio accesible para cualquier persona. 
Privado: Repositorio accesible solo para los miembros autorizados. 

12. ¿Cuál es la diferencia entre un repositorio local y un repositorio remoto? 
Un repositorio local está almacenado en tu máquina, mientras que un repositorio remoto está en un servidor (como GitHub, GitLab, Bitbucket), y se utiliza para compartir y colaborar con otros.

14. ¿Cómo funciona el control de versiones y por qué es importante? 
El control de versiones permite llevar un registro de todos los cambios realizados en el código, facilitando la recuperación de versiones anteriores y evitando la pérdida de trabajo. Es fundamental para la colaboración en equipo, ya que asegura que varios desarrolladores puedan trabajar en paralelo sin sobrescribir el trabajo de otros. 

15. ¿Cuáles son los comandos básicos de Git y para qué sirven? 
•	git init: Inicializa un nuevo repositorio Git en un directorio. Crea una carpeta oculta .git donde se almacenan los metadatos del repositorio. 
git init 
•	git clone: Clona un repositorio remoto en tu máquina local. Copia todo el historial y los archivos del repositorio. 
git clone <URL_del_repositorio> 
•	git add: Añade cambios al área de preparación (staging area). Puedes añadir archivos específicos o todos los archivos modificados. 

•	git add <nombre_del_archivo>  # Añade un archivo específico 
git add .                     # Añade todos los archivos modificados 
•	git commit: Guarda los cambios del área de preparación en el historial del repositorio. Se debe incluir un mensaje que describa los cambios realizados. 
git commit -m "Mensaje descriptivo del commit" 
•	git status: Muestra el estado actual del repositorio, incluyendo archivos modificados, añadidos o eliminados que aún no han sido confirmados. 

•	git push: Sube los cambios confirmados (commits) del repositorio local al repositorio remoto. 
git push <nombre_del_remoto> <nombre_del_rama> 
•	git pull: Obtiene los cambios del repositorio remoto y los fusiona con la rama actual en tu repositorio local. 

git pull <nombre_del_remoto> <nombre_del_rama> 
•	git branch: Muestra, crea o elimina ramas. Las ramas permiten trabajar en diferentes versiones del proyecto de manera aislada. 
git branch                  # Muestra las ramas existentes 
git branch <nombre_de_rama> # Crea una nueva rama 
git branch -d <nombre_de_rama> # Elimina una rama 
•	git checkout: Cambia entre ramas o restaura archivos en el directorio de trabajo. 
git checkout <nombre_de_rama> # Cambia a la rama especificada 
git checkout -b <nombre_de_rama> # Crea una nueva rama y cambia a ella 
•	git merge: Fusiona los cambios de una rama con la rama actual. 
git merge <nombre_de_rama> 
•	git log: Muestra el historial de commits en la rama actual. 
git log 
•	git diff: Muestra las diferencias entre archivos en el directorio de trabajo y el área de preparación, o entre commits. 
git diff                  # Muestra diferencias en el directorio de trabajo 
git diff --cached         # Muestra diferencias en el área de preparación 
git diff <commit1> <commit2> # Muestra diferencias entre dos commits 
•	git reset: Deshace cambios, ya sea en el área de preparación o en el directorio de trabajo. 
git reset <nombre_del_archivo> # Quita un archivo del área de preparación 
git reset --hard              # Deshace todos los cambios en el directorio de trabajo 
•	git remote: Gestiona las conexiones a repositorios remotos. 
git remote -v               # Muestra los repositorios remotos configurados 
git remote add <nombre> <URL> # Añade un nuevo repositorio remoto 
•	git fetch: Obtiene los cambios del repositorio remoto pero no los fusiona con la rama actual. 
git fetch <nombre_del_remoto> 

15. ¿Qué es una clave SSH y cómo se usa para autenticar Git con GitHub? 
Una clave SSH es una clave criptográfica utilizada para autenticarte de manera segura sin necesidad de introducir tu contraseña cada vez que interactúas con un repositorio remoto en GitHub. Para configurarla: 
-	Genera la clave SSH con ssh-keygen. 
-	Añade la clave pública a tu cuenta de GitHub en la sección de claves SSH. 
-	Usarás el protocolo SSH para autenticarte al hacer git push o git pull.
