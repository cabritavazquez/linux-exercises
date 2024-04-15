## Ejercicio 1

```bash
luisk@luisk-VirtualBox:~$ gato=octocat
luisk@luisk-VirtualBox:~$ echo $gato
octocat
luisk@luisk-VirtualBox:~$ env | grep "gato"
luisk@luisk-VirtualBox:~$ export gato
luisk@luisk-VirtualBox:~$ env | grep "gato"
gato=octocat
luisk@luisk-VirtualBox:~$ unset gato
luisk@luisk-VirtualBox:~$ env | grep "gato"
```

## Ejercicio 2

```bash
luisk@luisk-VirtualBox:~$ echo $SHELL
/bin/bash
luisk@luisk-VirtualBox:~$ cat /etc/shells
# /etc/shells: valid login shells
/bin/sh
/bin/bash
/usr/bin/bash
/bin/rbash
/usr/bin/rbash
/bin/dash
/usr/bin/dash
luisk@luisk-VirtualBox:~$ grep luisk /etc/passwd
luisk:x:1000:1000:luisk,,,:/home/luisk:/bin/bash
```

## Ejercicio 3

| Variable  | Contenido                             | ColumnaVacia |
|-----------|---------------------------------------|--------------|
| HOME      | Directorio de inicio del usuario      |      /home/luisk        |
| USER      | Nombre del usuario                    |       luisk       |
| SHELL     | Ruta a la shell del usuario           |        /bin/bash      |
| HOSTNAME  | Nombre del host (nombre del equipo)   |       luisk-VirtualBox       |
| TERM      | Tipo de terminal o emulador de terminal |      xterm-256color     |
| LOGNAME   | Nombre de usuario de inicio de sesión |      luisk        |
| PATH      | Lista de directorios de búsqueda de ejecutables (separados por :) |  /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/snap/bin  |
| PWD       | Directorio de trabajo actual          |       /home/luisk       |
| OLDPWD    | Directorio de trabajo anterior        |              |
| PS1       | Formato del prompt del shell primario (normalmente '$' para usuario normal y '#' para root) |       \[\e]0;\u@\h: \w\a\]${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\w\[\033[00m\]\$       |
| PS2       | Formato del prompt secundario         |       >       |

## Ejercicio 4

```bash
minombre=Alfonso
miapellido=Sanz
miedad=41
echo "Mi nombre es $minombre"
echo "Mi apellido es $miapellido"
echo "Mi edad es $miedad"
```

## Ejercicio 5

