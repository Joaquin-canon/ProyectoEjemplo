
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

## Subir una actualizacion local al repositorio main 

#### 1. Verificar cambios 

```bash
git status
```
Este comando me permite saber si realice algún tipo de cambio , si lo ejecuto me debería dar una información de los archivos que se han modificado 

#### 2. Verificar la rama en que quieras subir la actualización
```bash
git branch
```
Te permite ver la rama donde subiras y  harás la modificación 

#### 2.1 Si NO aparece la rama 

```bash
git fetch --all
```
Este comando te permite actualizar el estado de las ramas si crearte una nueva y no apaarece 

#### 3. Preparar archivos 

```bash
git add .
```
Te permite preparar Todos archibos los cuales les hiciste modificaciones 
```bash
git add archivo_ejemplo .txt
```
Te permite preparar un archivo en específico el cual hiciste  modificaciones 

#### 4. Guarda los archivos 

```bash
git commit -m "Agrego función de búsqueda"
```
Este comando te permite guardar los archivos que preparaste con " git add " ,  ente las " " coloca un mensaje corto sobre los cambios realizados 

#### 5. Subir cambios 

```bash
git push origin main
```
Este comando hará que los cambios locales (Origin) se suban o actualicen  la rama  main ( puede ser otra y puede tener otro nombre )
