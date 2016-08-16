#Desafío Clase Nro002

_José Daniel López_

###Identificación de permisos

Se deben identificar los siguientes permisos:

1. drwxr-xr-x:
    - **Identificación de tipo**: Es un directorio, por la d inicial.
    - **Permisos de usuario**: El usuario puede leer (r), escribir (w) y ejecutar(x).
    - **Permisos de Grupo**: El grupo puede leer (r), no puede escribir (-) y puede ejecutar (x).
    - **Permisos de Otros**: Otros pueden leer (r), no pueden escribir (-) y pueden ejecutar (x).

2. -rwxr-xr-x:
    - **Identificación de tipo**: Es un archivo por el guión inicial.
    - **Permisos de usuario**: El usuario puede leer (r), escribir (w) y ejecutar(x).
    - **Permisos de Grupo**: El grupo puede leer (r), no puede escribir (-) y puede ejecutar (x).
    - **Permisos de Otros**: Otros pueden leer (r), no pueden escribir (-) y pueden ejecutar (x).

3. dr-xrwx-wx:
    - **Identificación de tipo**: Es un directorio, por la d inicial.
    - **Permisos de usuario**: El usuario puede leer (r), no puede escribir (-) y puede ejecutar(x).
    - **Permisos de Grupo**: El grupo puede leer (r), puede escribir (w) y puede ejecutar (x).
    - **Permisos de Otros**: Otros no pueden leer (-), pueden escribir (w) y pueden ejecutar (x).

4. -rw-rw-rw-:
    - **Identificación de tipo**: Es un archivo por el guión inicial.
    - **Permisos de usuario**: El usuario puede leer (r), puede escribir (w) y no puede ejecutar(-).
    - **Permisos de Grupo**: El grupo puede leer (r), puede escribir (w) y no puede ejecutar(-).
    - **Permisos de Otros**: Otros pueden leer (r), pueden escribir (w) y no pueden ejecutar(-).

5. -rw-r--r--:
    - **Identificación de tipo**: Es un archivo por el guión inicial.
    - **Permisos de usuario**: El usuario puede leer (r), puede escribir (w) y no puede ejecutar(-).
    - **Permisos de Grupo**: El grupo puede leer (r), no puede escribir (-) y no puede ejecutar(-).
    - **Permisos de Otros**: Otros pueden leer (r), no pueden escribir (-) y no pueden ejecutar(-).


6. d-w-rwx-w-:
    - **Identificación de tipo**: Es un directorio, por la d inicial.
    - **Permisos de usuario**: El usuario no puede leer (-), puede escribir (w) y no puede ejecutar(-).
    - **Permisos de Grupo**: El grupo puede leer (r), puede escribir (w) y puede ejecutar(w).
    - **Permisos de Otros**: Otros no pueden leer (-), pueden escribir (w) y no pueden ejecutar(-).


###Asignación de permisos

Se pide:
1. Crear un archivo.
2. Asignar los permisos a usuario tal que éste pueda leer y escribir, y que no tenga privilegios ni grupo ni otros.
3. A ese mismo archivo asignarle permisos de lectura y escritura a grupo.
4. A ese mismo archivo, cambiar el permiso de usuario a que se pueda ejecutar.
5. A ese mismo archivo asignarle permiso de letura a otros.

**Ejecución:**

1. touch rights
2. chmod 600 rights
3. chmod g+rw rights
4. chmod u+x rights
5. chmod o+r rights
6. chmod u-rw rights // quita permisos







