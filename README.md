# Tarea 4. Refuerzo GitHub

1. Crear un repositorio.

    ![1. Creando repo desde GitHub](images/crear_repo.jpg)

2. Clonar repositorio.

    ```bash
    $ git clone https://github.com/edumarrom/refuerzo-emr.git
    ```
    ![2. Clonando repo](images/clonar_repo.png)

3. Readme

    ![3. Creando archivo README.d](images/readme.png)

4. Commit Inicial.

    ```bash
    $ git add .
    $ git commit -m "Commit inicial"
    ```

5. Push inicial.

    ```bash
    $ git push
    ```
6. Ignorar archivos.
    1. Crea en el repositorio local un fichero llamado privado.txt
        ```bash
        $ echo "" > privado.txt
        ```
    2. Crea en el repositorio local una carpeta llamada privada
        ```bash
        $ mkdir privada
        ```
    3. Realiza los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git.
        ```bash
        $ echo "privado.txt" > .gitignore
        $ echo "privado/" >> .gitignore
        ```

7. Añadir fichero.

    ```bash
    $ echo "" > 1.txt
    ```

8. Crear tag.

    ```bash
    $ git tag -a v0.1 -m "8. Crear tag"
    ```

9. Subir tag.

    ```bash
    $ git push --tags
    ```

10. Cuenta de github.

    ![10. Foto de perfil](images/foto_perfil.png)

11. Uso social de github.

    1. Poned vuestros nombres de usuario en el canal de discord “github”. Busca tus compañeros de grupo y del primer trimestre y sígueles.

        ![11.1 Compartiendo user en Discord](images/discord.png)

        ![11.1 Compañeros en GitHub](images/companyeros.png)

    2. Seguir los repositorios refuerzo-XXX del resto de tus compañeros.

        ![11.2 Repositorios destacados](images/watched.png)

    3. Añadir una estrella a los repositorios refuerzo-XXX del resto de tus compañeros.

        ![11.3 Repositorios destacados](images/starred.png)

12. Crea una tabla.

    | NOMBRE | GITHUB |
    | - | - |
    | Laura Alcón | [axrynz en GitHub](https://github.com/axrynz) |
    | Pablo Leal | [Pabloleabr en GitHub](https://github.com/Pabloleabr) |

13. Poner a github.com/antvazcar como colaborador de refuerzo.

    ![13. Asignanto a un colaborador](images/collaborator.png)
