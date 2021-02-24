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
    2. Posicionarse en la rama v0.2 y poner “Adios” en el fichero “1.txt” y hacer commit.
    3. Posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2.
