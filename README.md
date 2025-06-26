# Proyecto 7: Observabilidad de cluster Kubernetes local(mini-monitoring).

### Jesus Diego Osorio Tello - jesus.osorio.t@uni.pe

Con mi grupo trabajamos en una organización de GitHub, en el cual creamos nuestro repositorio para esta PC4: https://github.com/grupo10-CC3S2

Link del repositorio principal de la PC4: https://github.com/grupo10-CC3S2/Proyecto7-PC4.git

## Sprint 1

Hasta el momento en el Sprint 1 me he encargado de implementar los hooks `pre-commit`, `commit-msg` y `pre-push`, los cuales nos hacen tener commits que sigan las convenciones. También implementé el script `install_hooks.sh` que automatiza la instalación de los hooks.

### Instrucciones

- Para clonar mi repositorio, usamos el comando `git clone`.

    ```bash
    git clone https://github.com/JesusOsorio-19/Observabilidad-de-cluster-Kubernetes-local.git
    ```

- Para usar los hooks que implementé lo hacemos de la siguiente manera.

    Los hooks `pre-push`, `pre-commit` y `commit-msg` lo coloque en la subcarpeta `hooks`, ahora solo es necesario ejecutar el script `install_hooks.sh` para que todos nuestros hooks funcionen. 

    ```bash
    chmod +x chmod +x install_hooks.sh
    ./install_hooks.sh
    ```
