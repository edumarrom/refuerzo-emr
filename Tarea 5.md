# Entornos de Desarrollo: Tarea 5. Refuerzo GitHub (II)
### Eduardo Martínez Romero - 1º DAW 2020·2021

1. Crear rama
    ```bash
    $ git branch v0.2
    ```
2. añadir fichero.

    ![Crenado una rama](images/rama.png)

3. crear rama remota.

    ![Creando rama en GitHub](images/push_rama.png)

4. Merge directo.
    1. Posicionarse en la rama maestra.
        ```bash
        $ git checkout main
        ```
    2. Hacer un merge de la rama v0.2 en la rama master.
        ![Haciendo merge](images/merge.png)

5. Merge con conflicto.
    1. En la rama master poner “Hola” en el fichero 1.txt y hacer commit.
        ```bash
        $ echo "Hola" > 1.txt
        $ commit -am "Hola main/1.txt"
        ```
    2. Posicionarse en la rama v0.2 y poner “Adios” en el fichero “1.txt” y hacer commit.
        ```bash
        $ git checkout v0.2
        $ echo "Adios" > 1.txt
        $ commit -am "Adios v0.2/1.txt"
        ```
        ![Creando conflicto](images/conflicto1.png)

    3. Posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2.

        ![Conflicto merge](images/conflicto2.png)

6. Listado de ramas.

    ![Ramas merged](images/ramas_merged.png)

7. Arreglar conflicto.

    ![Resolviendo conflicto desde VScode](images/resolver_conflicto.png)
    Hemos aceptado ambos cambios. El resultado es:

        Hola
        Adios

    ![Conflicto resuelto](images/conflicto_resuelto.png)

8. Borrar rama.
    1. Crear un tag v0.2

        ```bash
        $ git tag v0.2
        ```

    2. Borrar la rama v0.2

        ![Conflicto resuelto](images/rama_borrar.png)

9. Lista los distintos commits con sus ramas y sus tags

    ![Log resumido](images/log.png)

10. Crear organización.

    ![Creando organización](images/organizacion_crear.png)

11. Crear equipos.

    ![Invitando miembros](images/organizacion_miembros.png)

    1. Crea dos equipos en la organización refuerzo-edumarrom, uno llamado administradores con más permisos y otro colaboradores con menos permisos.

        ![Creando equipos](images/organizacion_equipo_crear.png)

        ![Permisos de equipo](images/organizacion_privilegios.png)

    2. Meter a github.com/antvazcar y a 2 de vuestros compañeros del grupo de clase en el equipo administradores

        ![Invitando miembros](images/organizacion_administradores.png)

    3. Meter a github.com/antvazcar y a otros 2 compañeros del grupo de clase en el equipo colaboradores

        ![Invitando miembros](images/organizacion_equipos.png)

12. Crea un index.html.

    ![Invitando miembros](images/index.png)
