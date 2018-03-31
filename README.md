# EasyGitUserChange
Script para cambiar facil y rapido tu usuario git local / Script for Change easy and fast your local git user


Español/Spanish:

Este script fue desarrollado para quitarme la tediosa tarea de intercambiar mis usuarios git local, ya que me molestaba que en mis repositorios se guardaran los commit con otro nombre.

espero que guste:

```batch
ECHO OFF
ECHO ¡Bienvenido a EasyGitUserChange!
SET /P inputname= Por favor, ingresa el nombre de usuario:
SET /P inputemail= Por favor, ingresa el correo:
ECHO Su usuario Git sera cambiado por Usuario: "%inputname%" y el Correo: "%inputemail%"
ECHO Si no esta de acuerdo con los cambios presione Ctrl + C, Si esta de acuerdo
PAUSE
GIT config --global user.name %inputname%
GIT config --global user.email %inputemail%
GIT config --global user.name
GIT config --global user.email
PAUSE
```


Ingles/English:

This script was developed to get rid of the tedious task of exchanging my local git users, since it bothered me that in my repositories the commits with another name were saved.

I hope you like it: 

```batch
ECHO OFF
ECHO ¡welcome to EasyGitUserChange!
SET /P inputname= Please, insert username:
SET /P inputemail= Please, insert email:
ECHO Your Git user will be changed to User:  "%inputname%" and Email: "%inputemail%"
ECHO If you do not agree with the changes press Ctrl + C, if you agree
PAUSE
GIT config --global user.name %inputname%
GIT config --global user.email %inputemail%
GIT config --global user.name
GIT config --global user.email
PAUSE
```
