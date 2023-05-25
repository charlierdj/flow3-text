# flow3-text
Tercer flow donde probamos el UI del local host con la funcion text de dashboard

## Introducción

El flow 3 muestra el uso de los nodos dashboard. Un nodo de texto presenta la información del timestamp convertido a un string de fecha del flow 2.

## Material Necesario

Para realizar este flow necesitas lo siguiente

- [Ubuntu 20.04](https://releases.ubuntu.com/20.04/)
- [Docker Engine](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)
- [NodeRed](https://nodered.org/docs/getting-started/local)
- [Nodos Dashboard](https://flows.nodered.org/node/node-red-dashboard)

## Material de referencia

En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com que te permitirán realizar las configuraciones necesarias

- [Instalación de Virtual Box y Ubuntu 22.04 LTS](https://edu.codigoiot.com/course/view.php?id=812)
- [Introducción a Docker](https://edu.codigoiot.com/course/view.php?id=996)
- [Aplicacion multicontenedor de servidor IoT con Docker compose](https://edu.codigoiot.com/mod/lesson/view.php?id=3889&pageid=3804&startlastseen=no)
- [Servidor del Internet de las Cosas con nodeRed](https://edu.codigoiot.com/course/view.php?id=997)


## Instrucciones

Estas son las instrucciones para crear el flow desde cero. Este repositorio incluye el archivo JSON con el Flow funcional.

1. Duplicar el flow 2 con las mecanicas de exportar e importar
2. Renombrar el flow a Flow 3
3. Agregar el nodo texto
4. Crear una pestaña en la sección Dashboard
5. Crear un grupo
6. Configurar el nodo texto para que se visualice en el grupo recien creado
7. Hacer clic en Deploy y consultar el [Dashboard](http://localhost:1880/ui)

### Requisitos previos

Para que este flow funcione, debes cumplir con los siguientes requisitos previos
1. Tener instalado Docker Engine.
2. Tener instaldo nodeRed por Docker Compose
3. Tener el contenedor de NodeRed con el volumen de data activado

### Instrucciones de preparación del entorno

Para ejecutar este flow, es necesario lo siguiente
1. Arrancar el contenedor de NodeRed con el comando
        
        docker start $(docker ps -a -q)
2. Dirigirse a [localhost:1880](localhost:1880)
3. Importar el flow desde el repositorio
4. Hacer clic en el boton Deploy

### Instrucciones de operación

Para observar el resutlado de este flow, sólo es necesario abrir la pestaña Debug.

## Resultados

A continuación puede verse una vista previa del resultado de este flow.

![]()

## Evidencias

![](https://github.com/hugoescalpelo/flow3-nodeRed-Docker-Compose/blob/main/imagenes/Screenshot%20from%202023-05-24%2020-41-21.png)

![](https://github.com/hugoescalpelo/flow3-nodeRed-Docker-Compose/blob/main/imagenes/Screenshot%20from%202023-05-24%2020-42-30.png)

# Notas
- Este repositorio cuenta con las instrucciones para crear el flow pero también incluye el archivo JSON resultante, así que solo tienes que importarlo a nodeRed.

# Créditos

Desarrollado por Hugo Escalpelo
- [hugoescalpelo.com](https://hugoescalpelo.com/)
- [Página en Facebook](https://www.facebook.com/Hugo-Escalpelo-Profesional-337708683840136)
- [GitHub](https://github.com/hugoescalpelo)

Copiado por **Carlos Rosales de Jesus**
- [Letterboxd](https://letterboxd.com/charlie_rdj/)