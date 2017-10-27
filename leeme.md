# Curso Git desde cero
Sistema de control de versiones para el mantenimiento eficiente y confiable de archivos.

## Zonas de Git
1. Directorio de trabajo
2. Área de preparación
3. Repositorio Git

## Flujo de trabajo básico en Git



## Configurando Git por primera vez

Esta línea fue creada en la rama master

## Configuración SSH en Windows

Usando Git Bash los siguientes pasos:

1.Creamos una carpeta llamada `llaves-ssh` en disco `C` para evitar problemas de rutas.

2.Ejecutamos el comando `ssh-keygen -t rsa -C "mi-correo@ejemplo.com"`.
El correo debe ser el mismo con el que nos registramos en Github para evitar posibles problemas.
Dejamos el passphrase vacío y damos enter.
Cuando nos pida la ruta escribimos `/c/llaves-ssh/hithub_rsa`.

3.Iniciamos ssh-agent en background ejecutando el comando `eval "$(ssh-agent -s)"`.

4.Agregamos la llave ssh generada a ssh-agent ejecutamos el comando `ssh-add /c/llaves-ssh/github_rsa`.

5.Desde ahora podemos hacer pull y push sin que Github nos éste pidiendo los datos de acceso.
