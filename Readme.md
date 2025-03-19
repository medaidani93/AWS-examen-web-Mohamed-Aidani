# Resumen de la tarea: Configuración de la instancia en AWS y despliegue con Node.js, Vite y Serve

## Objetivos
El objetivo principal de esta tarea fue configurar una instancia en AWS y desplegar una aplicación utilizando **Node.js**, **Vite** y **Serve**.

## Pasos realizados
1. **Configuración de la instancia en AWS**: 
   - Se creó y configuró una instancia EC2 en AWS utilizando un sistema operativo Linux.
   - Se configuraron las reglas de seguridad (Security Groups) para permitir acceso SSH y tráfico HTTP.

2. **Instalación de herramientas en la instancia**:
   - **Node.js**: Se instaló Node.js en la instancia para poder gestionar y ejecutar aplicaciones JavaScript.
   - **Vite**: Se utilizó Vite como bundler para el proyecto, optimizando la velocidad de desarrollo y el proceso de construcción.
   - **Serve**: Se instaló Serve para servir el proyecto estático a través de un servidor HTTP local.

3. **Despliegue de la aplicación**:
   - Se creó un proyecto con Vite, y se subió el código a la instancia de EC2.
   - Se ejecutaron los comandos necesarios para servir el proyecto utilizando Serve y se validó que el proyecto estaba accesible desde la red.

## Herramientas utilizadas
- **AWS EC2**: Para crear y administrar la instancia.
- **Node.js**: Para gestionar la ejecución de código JavaScript.
- **Vite**: Como bundler para mejorar la experiencia de desarrollo y optimizar el código.
- **Serve**: Para servir la aplicación de manera estática.

## Resultados
- La instancia EC2 se configuró correctamente y el proyecto se desplegó con éxito.
- El servidor sirvió la aplicación correctamente a través de la red, accesible desde el navegador.

## Conclusión
Esta tarea permitió configurar correctamente una instancia en AWS, instalar las herramientas necesarias y desplegar una aplicación de manera efectiva utilizando **Node.js**, **Vite** y **Serve**. Esto proporciona una base sólida para el desarrollo y despliegue de aplicaciones en la nube utilizando AWS.

# Resumen de la tarea: Configuración de la instancia en AWS y despliegue con Node.js, Vite y Serve

## Objetivos
El objetivo principal de esta tarea fue configurar una instancia en AWS y desplegar una aplicación utilizando **Node.js**, **Vite** y **Serve**.

## Pasos realizados
1. **Configuración de la instancia en AWS**: 
   - Se creó y configuró una instancia EC2 en AWS utilizando un sistema operativo Linux.
   - Se configuraron las reglas de seguridad (Security Groups) para permitir acceso SSH y tráfico HTTP.

2. **Instalación de herramientas en la instancia**:
   - **Node.js**: Se instaló Node.js en la instancia para poder gestionar y ejecutar aplicaciones JavaScript.
   - **Vite**: Se utilizó Vite como bundler para el proyecto, optimizando la velocidad de desarrollo y el proceso de construcción.
   - **Serve**: Se instaló Serve para servir el proyecto estático a través de un servidor HTTP local.

3. **Despliegue de la aplicación**:
   - Se creó un proyecto con Vite, y se subió el código a la instancia de EC2.
   - Se ejecutaron los comandos necesarios para servir el proyecto utilizando Serve y se validó que el proyecto estaba accesible desde la red.

## Herramientas utilizadas
- **AWS EC2**: Para crear y administrar la instancia.
- **Node.js**: Para gestionar la ejecución de código JavaScript.
- **Vite**: Como bundler para mejorar la experiencia de desarrollo y optimizar el código.
- **Serve**: Para servir la aplicación de manera estática.

## Resultados
- La instancia EC2 se configuró correctamente y el proyecto se desplegó con éxito.
- El servidor sirvió la aplicación correctamente a través de la red, accesible desde el navegador.

## Conclusión
Esta tarea permitió configurar correctamente una instancia en AWS, instalar las herramientas necesarias y desplegar una aplicación de manera efectiva utilizando **Node.js**, **Vite** y **Serve**. Esto proporciona una base sólida para el desarrollo y despliegue de aplicaciones en la nube utilizando AWS.

## Explicacion con capturas de pantalla : 

![Lanzamiento de laboratorio ](/capturas/img1.png) 

    Primero he empezado por lanzar el laboratorio 

![Creacion de la VPC ](/capturas/img2.png) 

    Vamos a crear la VPC 

![VPC creada  ](/capturas/img3Mi_VPC.png)

    He creado la VPC con el nombre mi-vpc-Mohamed-Aidani

![Creacion de 2 subrede ](/capturas/img4Mis_Subredes.png) 

    He creado dos subredes una para Linux y otra para Windows

![Creacion de Internet GeteWay ](/capturas/img5InternetIGW.png) 

![Conectar a la VPC ](/capturas/img6AsociarGW_VPC.png) 

    Conectando Interner GeteWay a la VPC

![Confirmacion de la conexion ](/capturas/img7IgwAsociados.png) 

    Como aparece en la foto se ha conectado correctamente la conexion entre Internet Getewey y la VPC

![Creacion de la tabla de enrutamiento](/capturas/img8TablaRt.png) 

    He creado la tabla de enrutamiento y la asociado a la VPC 

![Agregacion de la tabla a Internet ](/capturas/img9AgregarRutaIntenet.png) 

    He agregado y actualizado la tabla de enrutamiento 

![Asociacion de subredes](/capturas/img10AsociarSubredes.png) 

    He asociado correctamente las subredes a mi vpc 

![Lanzamiento de la instancia ](/capturas/img11LanzarInstancia.png)

    Como aparece en la foto he lanzado correctamente la INSTANCIA 

![Conexcion de la instancia ](/capturas/img12Actualizacion.png)

    He actualizado la instancia utilizando los comandos SUDO APT UPDATE y SUDO APT INSTALL NODE.JS NPM

![Resumen de la instacia ](/capturas/img12InstanciaEC2Linux.png) 

    Aqui tenemos el resumen de la instancia que se llama EC2 Linux con sus informaciones ..

![Conectando Instancia SSH ](/capturas/img13ConectandoInstanciaSSH.png)

    He conectado la instancia EC2 Linux

![Actualizando la instancia y instalando ](/capturas/img1.png) 

    He instalado la correctamente la NPM - V

![instalar NODE_SERVE ](/capturas/img16IntalacionNode_Serve.png)

    Como se ve en la captura he instalado con exito NODE_SERVE


![Datos de Vite ](/capturas/img17Vite.png) 

    He obtenido el vite para tener la pagina web de Vite (llevo con mucho intentos pero no me funciona la pagina de vite )

![Vite v6.2.2 ](/capturas/img18ViteLocalHost.png) 

    Aparece vite con su http//localhost:5173
    y con su http//192.168.0.44.5173

![Creacion de archivo ](/capturas/img19CrearArchivo.png) 

    He creado el archivo web-Mohamed-Aidani

![Inicializar Proyecto ](/capturas/img20InicializarProyecto.png) 

![Proyecto](/capturas/img21Proyecto.png) 

    He craeado mi paquete web-mohamed-aidani , en el framework her seleccinado vanilla y luego a javascript

![Confirmacion de la intalacion](/capturas/img22Instalando.png) 

    El npm se ha intalado y funciona de manera correcta

![Terminar](/capturas/img23SirviendoProyecto.png)

    Terminando el proyecto con exito ! 

![Creacion del grupo de seguridad ](/capturas/img24SecurityGroup.png) 

    Creacion del grupo de seguridad se VITE , SSH y HTTP 

![Pagina web (html) ](/capturas/img25PaginaWeb.png)

    La pagina web que he creado , intentaba varias veces crearla con Vite pero no lo lograba .. 


![Empezar Pull&&Request ](/capturas/img27CreandoRamaRepoFernando.png)

    Aqui he empezado a clonar la ruta de Fernando para hacer Pull&&Request , he creado una rama , la he agregado y luego un commit con un comentario .. y al final lo he subido en su repositorio ...

![Resultado en el repositorio ](/capturas/img28Pull&&Request.png)

    Aqui he hecho merge para la rama que he creado en el repositorio del compañero .. 

![Confirmacion de MERGE](/capturas/img29MergedRepositorio.png)

        Se ha confirmado la operacion de MERGE en su repositorio .. 

![Resultado final ](/capturas/img30MergeRepoFernando.png)

    Aqui tenemos el resultado final del Pull&&Quest creando mi rama en su repositorio .. 











