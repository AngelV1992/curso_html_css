Pasos para usar git

Configuración inicial de git:
*git config --global user.name "nombre_del_usuario"
*git config --global user.emal 'correo electronico'
*git config --global core.editor "code--wait"
*git config --global core.autocrlf input (se utiliza para que los caracteres especiales de salto de linea no den errores entre windows y mac)

Comandos de git
*mkdir (se escribe el nombre de la carpeta que se quiere crear)
*cd nombredecarpeta (nos movemos al directorio en el que vamos a trabajar)
*cd .. (regresar un directorio)
*git init (iniciapiza repositorio vacio git)
*code . (abre el editor para empezar a crear archivos)
*git status  (nos muestra el estatus y la rama en la que nos encontramos)
*git add (permite agregar archivos para poder commit)
*git commit -m "comentario del commit" (se utiliza para hacer commit en los archivos)