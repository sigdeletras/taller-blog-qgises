# Comandos

## Git

### Instalación Ubuntu
```
sudo apt-get update
sudo apt-get install git
```
### Configuración git

Podemos comprobar que todo ha ido ok escribiendo en un terminal

```
git --version
```

Si es la primera vez [necesitaremos configurarlo](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Configurando-Git-por-primera-vez). Lo primero que deberás hacer cuando instales Git es establecer tu nombre de usuario y dirección de correo electrónico. 

Esto es importante porque los "commits" de Git usan esta información, y es introducida de manera inmutable en los commits que envías.

Abrimos un terminal y escribimos

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

## Flujo de Git

[Pro Git book de Scott Chacon](https://git-scm.com/book/es/v2/)

**Clonar un repositorio de existente***
```
git clone
```
**Crear una rama (branch)**
```
git branch nombre-rama
```
**Cambiar de rama (checkout)**

```
git checkout nombre-rama
```
**Crear y cambiar de rama (checkout)** 
```
git checkout -b nombre-rama
```
**Añadir ficheros (add)**
```
$ git add *
$ git add LICENSE
```
**Confirmaciones de cambios (commit)**
```
git commit -m 'Texto descriptivo'
```
**Añadir y commit**
```
git commit -a -m 'Texto descriptivo'
```
**Revertir cambios (revert)** 

**Subir cambios a repositorio remoto (push)
```
git push origin master
````

**Descargar cambios de repositorio remoto (pull)**
```
git pull <remote>
```

**Unir rama desarrollo a rama principal (merge)**

```
git checkout master
git merge nombre-rama
```

**Borrar rama**
```
git branch -d nombre-rama
```

**Iniciar git (init)**

**Ver estado de archivos**
```
git status
```
**Historial (log)**
```
git log
git log --pretty=oneline
git log --pretty=format:"%h - %an, %ar : %s"
```

