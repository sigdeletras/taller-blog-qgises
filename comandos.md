# Comandos

## Git

### Instalación
```
sudo apt-get update
sudo apt-get install git
```

O bien descargarlo [https://git-scm.com/downloads]

Podemos comprobar que todo ha ido ok escribiendo en un terminal

```
git --version
```

## Configuración

Si es la primera vez [necesitaremos configurarlo](https://git-scm.com/book/es/v2/Inicio---Sobre-el-Control-de-Versiones-Configurando-Git-por-primera-vez). Lo primero que deberás hacer cuando instales Git es establecer tu nombre de usuario y dirección de correo electrónico. 

Esto es importante porque los "commits" de Git usan esta información, y es introducida de manera inmutable en los commits que envías.

Abrimos un terminal y escribimos

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
