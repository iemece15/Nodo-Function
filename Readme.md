## Requisitos previos

    Arrancar el sistema de docker

    docker ps -a
    docker start $(docker ps -a -q)
    netstat -an | grep tcp

## Nodo function

    Entrar a localhost:1880
    Exportar el flow 1 haciendo clic en Menu > Exportar > Current Flow > JSON > formatted > download. Opcional, tomarlo del repositorio de clase anterior.
    Importar el flow 1 haciendo clic en Menu > Importar > Seleccionar un archivo para importar > Importar > Importar una copia
    Configurar el nodo function haciendo doble clic sobre el
    Agregar el codigo del ejemplo a la pestaña On Message
    Activar el nodo Debug y asegurarse de que el nodo inject este lanzando mensajes cada 5 segundos
    Hacer clic en Deploy.

