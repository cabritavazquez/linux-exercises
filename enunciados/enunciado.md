# Enunciados de Ejercicios Moded

## 1. Crear y Exportar una Variable

Vamos a crear una variable local llamada `gato` y exportarla.

Sigue estos pasos:

1. Crea una variable local llamada `gato` y asígnale el valor que quieras.
2. Muestra su valor por pantalla con el comando `echo`.
3. Mira si es una variable de entorno con el comando `env`.
4. Expórtala con `export`.
5. Comprueba de nuevo si es una variable de entorno.
6. Borra la variable.

## 2. Comprobar tu SHELL y Ver Shells Disponibles

Comprueba tu SHELL actual y luego verifica qué shells están disponibles en el sistema.

## 3. Variables de Entorno Más Usadas

Averigua qué contienen las siguientes variables de entorno más usadas:

- `HOME`
- `USER`
- `SHELL`
- `HOSTNAME`
- `TERM`
- `LOGNAME`
- `PATH`
- `PWD`
- `OLDPWD`
- `PS1`
- `PS2`

## 4. Encontrar Errores en Scripts

Encuentra los errores que hay en los siguientes lineas:

```bash
minombre=Alfonso
miapellido = Sanz
miedad=41
echo "Mi nombre es $minombre"
echo "Mi apellido es $miapellido"
echo "Mi edad es miedad"
```

## 5. Cambiar el valor de la variable PATH

Cambiar el valor de la variable PATH para que incluya nuestro directorio personal.

## 6. Modificar Archivos de Configuración de Shell

Modificar el archivo `/home/user/.bash_profile` o el `.profile` (`.profile` se ejecuta si no hay `.bash_profile`) para añadir la ruta de nuestros scripts.

## 7. Cambiar el Prompt

Cambiar el prompt para que muestre la fecha, nombre de usuario y la carpeta actual. 

Nota: Si se cambia en el `$HOME/.bashrc` se hará permanente.

## 8. Crear un Shell Script

Crear un shell script que:

- Borre la pantalla
- Diga “Hola, nombre de usuario. La fecha actual es: .”
- Indique que estás en el “directorio actual”

## 9. Hacer que el Script se Ejecute Siempre al Iniciar Sesión

Hacer que el script anterior se ejecute siempre cuando hagamos login con nuestro usuario.

## 10. Crear un Shell Script Informativo

Crear un shell script que:

- Diga su nombre
- Indique con cuántos parámetros lo han llamado
- Muestre todos los parámetros
- Muestre el PID del proceso

## 11. Realizar un Script Informativo

Realizar un script que muestre:

- El nombre del script
- El número de parámetros que se le pasan
- Una lista con los parámetros recibidos
- El identificador del usuario que ejecuta el script
- El nombre de usuario
- El directorio home del usuario
- El directorio actual

## 12. Practicar las Opciones del Comando Echo

Crear un script que practique las diferentes opciones del comando `echo`.

## 13. Leer Varias Variables del Teclado

Lee con un solo comando `read` varias variables del teclado. Cada valor se introduce separado por espacios. Si hay más variables que valores introducidos, a las variables que sobran se les asigna `NULL`. Si se introducen más palabras que variables, los datos que sobran se le asignan a la última variable.

## 14. Unir Nombre y Apellidos en una Variable Única

Script que pide nombre y apellidos y lo une todo en una variable única, que muestra por pantalla.

## 15. Mostrar la IP de un Dominio

Script que pide al usuario introducir una dirección de internet por ejemplo: `www.cyberciti.biz`. A continuación muestra la IP de ese dominio.

## 16. Uso de la Orden Printf

Crea un script sencillo que use la orden `printf` (salida formateada).

## 17. Días Restantes Hasta el 31 de Diciembre

Script que nos dice cuántos días quedan hasta el 31 de diciembre.

## 18. Operaciones Matemáticas Básicas

Shell script que recibe como parámetros dos números enteros. Luego los multiplica, suma, resta y divide.

## 19. Calcular la Propina

Script donde el usuario introduce el importe total y el script muestra la propina del 10%.

## 20. Calculadora Simple

Escribe una calculadora simple que permita al usuario ingresar dos valores numéricos y la operación: (`+`, `-`, `/`, `*`), y a continuación realice la operación introducida.

## 21. División de Variables y Almacenamiento

Realizar un script que defina dos variables, `a=20` y `b=5`. Muestra el resultado de la división de `a` entre `b` por pantalla. Después, guarda el resultado en una variable llamada `resultado`.

## 22. Calcular Índice de Masa Corporal (IMC)

Realizar un script que solicite al usuario por teclado su peso y su estatura y muestre la siguiente salida por pantalla (respetando los saltos de línea y las tabulaciones): 

            Peso: [peso del usuario]
            Estatura: [estatura del usuario]
            Índice de Masa Corporal (IMC): [resultado del cálculo]


## 23. Extraer Subcadenas

Dada la cadena `cadena=abcdeABCDE1234567`, extraer diferentes subcadenas.

## 24. Búsqueda de Palabra en Ficheros

¿En qué ficheros aparece la palabra `FILE`? (En mayúscula o minúscula)

## 25. Filtrar Procesos de Usuario

Script que filtra los procesos de un usuario.

## 26. Uso de grep con el Fichero /etc/passwd

El fichero `/etc/passwd` tiene el siguiente formato:            
login:password:UID:GID:comentario:HOME:Shell`

    a) Mostrad la línea correspondiente a la cuenta `man`.

    b) Mostrad las cuentas que empiecen por `a`.

    c) Mostrad las cuentas que empiecen por `a` o `r`.

    d) Mostrad las cuentas que terminen por `c`.

    e) Mostrad las cuentas que usen `bash` como intérprete de comandos.

    f) Mostrad las cuentas que NO usen `bash` como intérprete de comandos.

    g) Mostrad las cuentas que no empiecen por vocal.

    h) Mostrad las cuentas que empiecen por mayúscula.

    i) Mostrad las líneas cuyo tercer campo tenga una sola cifra.

    j) Mostrad las líneas que tengan cifras de 3 a 5 dígitos.

    k) Mostrad las líneas que tengan cifras de 3 dígitos en el cuarto campo.

    l) Mostrad las cuentas `root` o de `ftp`.

    m) ¿Qué ficheros de cabecera usan la constante `MAXDOUBLE`?

    n) ¿En qué ficheros aparece la palabra `bash`? (En mayúscula o minúscula)

## 27. Uso de sort

1. Ordenad el fichero `/etc/passwd` por orden alfabético.
2. Ordenadlo en sentido inverso.
3. Ordenadlo ignorando mayúsculas.
4. Ordenadlo según el tercer campo.
5. Ordenadlo según el tercer campo en orden numérico.
6. Ordenadlo según el cuarto campo en orden numérico y eliminando repeticiones.

## 28. Uso de Arrays

- Crea un menú empleando arrays. En cada posición del array introduce un plato (ej. Espaguetis; melón con jamón… etc.). Emplea 4 platos diferentes.
- Después modifica un plato (ej. El plato n1 2 por otro diferente).
- Añade un 5º plato al array.
- Muestra todo el menú del día con una orden (todos los elementos del array).

## 29. Generador de Frases Aleatorias para Galleta de la Fortuna

Script que genera una frase aleatoria entre 10 para una galleta de la fortuna. Debes crear un array de 10 elementos, donde cada frase es uno de los elementos. Después con `RANDOM`, selecciona aleatoriamente una de las frases.

## 30. Creación de Usuarios y Grupos

Crear un usuario con el Id 999 y el nombre `navin`. 
Crear el grupo `oficina1`.
Cambiarle el nombre a `oficina2`. 
Crear usuario `sonia` en `oficina2`.

## 31. Uso de > y >>

Crea un archivo llamado `redirreciones.txt` y añade  en la primera linea **mi Nombre es**,ahora prueba a concatenar tu nombre con los dos operadores y comprueba la diferencia de su uso.  

## 32. Uso de la redirrecion

Lista todos archivos de tu directorio actual y usa el operador de redirrecion `|` para filtrar su salida y buscar el archivo `redirreciones.txt`.

## 33. Uso de &

Crea tres directorios y un archivo llamado `mensaje.txt` ahora copia el archivo de texto en los tres directorios con una sola linea de comando usando el operador **&&**.

## 34. Crea un script que reciba como parámetro la ruta a un fichero y que nos indique si tiene permisos de ejecución.

El script deberá verificar que se ha introducido algún parámetro, y en el caso de que se haya introducido, verificar antes de comprobar los permisos que el fichero existe.

## 35. Crea un script que reciba como parámetros el nombre de uno o varios usuarios, y nos indique si existen en el sistema.

Consejo utiliza el archivo `/etc/passwd` y realiza filtros con grep.