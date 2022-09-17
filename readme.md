![](https://upload.wikimedia.org/wikipedia/commons/6/62/Git-logo-orange.svg "Logo Git")

### Descripción

CursoGit es una recopilación de ordenes básicas para trabajar con GIT tanto en local, como con repositorios remotos. Estos apuntes son un comienzo, pero hay que tener en cuenta que GIT tiene mas funcionalidades que no están aquí descritas, las cuales puedes encontrar en su [documentación oficial](https://git-scm.com/doc).

### Recursos

Para realizar el contenido de este repositorio se ha utilizado el software de control de versiones Git, diseñado por Linus Torvalds. Que se puede instalar tanto en Linux, como en Windows, o en macOS.

##### Linux

```
Debian/Ubuntu
	apt-get install git

Fedora
	yum install git (up to Fedora 21)
	dnf install git (Fedora 22 and later)

Gentoo
	emerge --ask --verbose dev-vcs/git

Arch Linux
	pacman -S git

openSUSE
	zypper install git

Mageia
	urpmi git
```

#### macOS

```
Homebrew
	brew install git

MacPorts
	sudo port install git
```

#### Windows

```
	https://git-scm.com/download/win
```

### Notas

Para poder utilizar el repositorio remoto basado en Github, se necesita saber el usuario y la contraseña. Pero en los últimos tiempos, por temas de seguridad,  Github ha sustituido la contraseña para el modo de acceso mediante aplicaciones por el Personal Access Token, puedes generar uno siguiendo estas [instrucciones](https://docs.github.com/es/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).

### Agradecimiento

A Diego Bastidas, por haber realizado y publicado un curso de git y github en [youtube](https://www.youtube.com/c/dfbastidas).
