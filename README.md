[practica5](./practica5.md)

 creando la versión 1.0.0 de este repositorio.

### ¿Cómo se inicializa un repositorio en Git? 

1. Al iniciar git tienes que configurar en el visual studio code y tienes que poner las siguientes lineas de codigo

``` 
git --version 

```
``` 
git config --global user.name "Nombre del usario" 
```
 ``` 
 git config --global user.email correo electronico que esta configurado con github 
 ```
 ```
  git config --global user.ui true
  ```
 ``` 
 git config --global init.defaultBranch main 
 ```
 ```
  git config --list 
  ```
 ``` 
 git config --global core.editor "code --wait" 
 ```
``` 
git config --global -e 
```

a si tienes el --global pero esto abarcaria a tu computadora pero si no es tu computadora personal es mejor usar el --local

---
### ¿Cómo creas un repositorio en GitHub?
Para hacer un repositorio en github debes

 1. tener una cuenta de github
1. al iniciar sesion aparecera en la parte de arriba a la derecha el simbolo de +
 

 1. al presionar ponlo en new repository 

 1. debes poner un nombre a tu repositorio sin espacios 

1. y tu eliges si tu repositorio sera publico o privado 


1. si quieres puedes poner un git ignore hacia algunso archivos que usan algunos motores de codigo o de juegos 

1. y al final le pones create repository
 

---
### ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub? 
se debe poner 

se agrega el origen de tu repositorio de GitHub
``` 
git remote add origin https://github.com/usuario/repositorio.
``` 
despues ponemos la siguiente linea de codigo
``` 
git push -u origin main
``` 
aparecera una ventana emergente para enlazar el git con tu cuenta de github

y al ultimos para subir todos los cambios debes poner 

``` 
git push
``` 
---

### ¿Cuál es el flujo básico de trabajo en Git y GitHub?

El flujo basico de git y github es la forma de guardar los cambios y subirlos a la nube para asi trabajar en cualquier parte mediante los comandos de git al github 

---