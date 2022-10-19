## No olvides guardar tu trabajo antes de subirlo##
    
    - git add .
    - git commit -m 'Algun mensaje alusivo a los cambios por guardar'
    
Es importante recalcar que la rama main esta bloqueada, por lo tanqo es necesario subir el trabajo a una rama nueva y luego crear un pull request
    
    - git push origin main:<nombre_de_la_nueva_rama>
    
###¿Cómo contribuir?###
    - Para iniciar, es necesrio tener una copia actualizada del repositorio.
    - El proyecto de organiza con un Router en App.js, así que cualquier Vista debe ser anexada en una carperta con su nombre dentro de la carpeta Views de la siguiente manera:
    
    src
    |
    index.js
    .
    App.js
    .
    Views
    .  |_Auth
    .  |_Inicio
    .  |_Menu
    .  |_NavBar
    .
    components
       |_Theme.js
    
Los archivos que sean dependencias de una vista deben ser incluidos dentro de dicha carpeta, exepto los archivos de imagen, que deben incluirse y referenciarse a la carpeta images dentro del la carpeta public
    
    
### ¿Para qué es este repositorio? ###

Aplicación frontend para el proyecto Savage Food Restaurant presentado en el marco de la capacitación
dada por la Universidad Nacional en convenio con MisiónTIC2022

* Version

    1.0.0

### Set-Up ###

    - git clone https://bitbucket.org/savage-food/frontend/src/main/ 
    - cd savage-food-app
    - npm install
    - npm start

    Esta aplicación trabaja con:
    - Material UI
    

* Deployment instructions
     pendiente...

  
### ¿Qué hago si no me deja hacer Merge? ###
    por defecto se necesita que alguien apruebe el Merge antes de poder realizarse, 
    existen revisores por defecto, pero puedes agregar o modificar quienes pueden
    pregunta en el grupo quien puede hacerlo

### ¿Qué hago si no me deja hacer un Merge por incompatibilidad? ###
*lo primero es cersiorarte de que tengas tu trabajo asegurado en local, haz una copia en otra carpeta
Ahora viene la parte mas dificil: debes crear un nuevo clon del repositorio en una nueva ruta en local y a partir de este hacer los cambios que
necesitas hacer. Recuerda que puedes incluir nuevos archivos solo pegandolos en el nuevo clon, los demas cambios deberás editarlos para que
coincidan con tu trabajo.
Ahora que todo está bien puedes hacer el pull request sin problemas


### Who do I talk to? ###

* Repo owners
    - Oswaldo Pacheco García(linuxcisco12@gmail.com)
    - Jorge Morantes Bohórquez(jorgemorantes17@gmail.com)
    - Luis García Bastidas(luis.garcia@correounivalle.edu.co)
    - Duvan Lozada Bahamón(duvanlozada89@gmail.com)
    - Leonel Doria (leoneldoria09@gmail.com)
    - Gregorio Morales Pájaro (grmoralesp@gmail.com)

