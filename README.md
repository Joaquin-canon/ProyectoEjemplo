
Autor: Joaquín Cañon
# 🦉 Autoguía para manejar Github ( sin terminar )
En este repositorio practicaré el uso de Github. Me daré instrucciones para hacer, descargar, actualizar y subir un repositorio 


## Descargar Repocitorio: 
#### 1. Crear e ubicarte en la carpeta de peoyecto 

```bash
  cd C:\Users\(ubicacion de la carpeta )            
```
Crea una carpeta , usando el cmd con el comando cd y la ruta del explorador de archivos de la carpeta que acabas de crear , ejecuta  el código y  te ubicaras en la ruta de la carpeta dentro del cmd
#### 2. Clona el proyecto

```bash
  git clone https://github.com/Joaquin-canon/ProyectoEjemplo.git 
            
```
 Para "Descargar la vercion de un proyecto debes usar el comendo  "git clone" " Direcion del proyecto .git " la dirección la puedes encontrar en el repositorio en el apartado code/https/ solo copia el link y lo pegas al lado de la consola (cmd) ejecuta el código  lo que descargara el proyecto en la carpeta , ubicacion que colocaste en el paso anterior 

 #### 3. Entar al proyecto 

 usando el editor de código preferido abre la carpeta que se descargó y podrás trabajar en lo que necesites de manera local 


## Actualizar una versión local a la que está subida 

###  
#### 1. Descargar actualización 

```bash
git felch 
```
Este comando permitirá descargar archivos actualizados de la rama en la que te encuentres ( No afectará los archivos locales)

#### 2. Instala  actualización 

```bash
git pull origin main
```
Este comando te actualizara los archivos locales con respecto a la versión que descargaste con (  git felch  )