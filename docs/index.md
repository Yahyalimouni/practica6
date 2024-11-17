# Practica 2.6

## Introduccion
 En esta practica vamos a Desplegar con Tomcat9 y Maven. 


## Primero descargamos tomcat9:
Usando el comando wget y la ruta del gz

## Luego lo extraemos y le cambiamos el nombre

![](assets/02_extraer_gz.png)
![](assets/03_cambiarle_nombre.png)

## Establecimos el propietario

![](assets/04_camiar_propietario.png)

## Decargamos JDK:

![](assets/05_descargar_java.png)

## Instalamos Tomcat manualmente:
### Establecimos las variables de entorno:

![](assets/07_variable_entorno_iniciar_tomcat.png)

### Accedemos a la interfaz de tomcat.

![](assets/08_acceder_tomcat9.png)

### Creamos el usuario admin que seria yahya en mi caso

![](assets/09_crear_usuario_admin.png)

### Desplegamos el .war de ejemplo para probar

![](assets/10_desplegar_war_tomcat9.png)

![](assets/11_despliegue_war.png)

## Pasamos ya a la instalacion de Maven

![](assets/12_instalar_maven.png)

## Estalbecimos lso roles de usuarios

![](assets/13_roles_xml.png)

## Establecimos el ID del servidor en ```/etc/maven/settings.xml```

![](assets/14_ponemos_id_maven.png)

## Generamos un proyecto Marven

![](assets/16_desplegas_maven.png)

![](assets/17_proj_built.png)


## Configuramos el pom.xml de nuestro proyecto generado por Maven.

![](assets/18_confpom_xml.png)

Lo demas no me ha ido bien creo que era por la version del plugin de marven.
