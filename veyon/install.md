

 
Tabla de contenidoss
INSTALACIÓN DE VEYON	2
¿QUÉ HACER SI WINGET NO INSTALA VEYON?	2
CONFIGURACIÓN DEL VEYON ALUMNADO	3
AGREGAR LA CLAVE PÚBLICA	3
CAMBIAR IDIOMA Y AUTENTIFICACIÓN	4
CAMBIAR NOMBRE AL EQUIPO	5
CONFIGURACIÓN DEL VEYON PROFESORADO	6
CREAR GRUPO Y AÑADIR PORTÁTILES	6




 
Instalación de Veyon
Veyon es una herramienta de software libre que permite la supervisión y el control de estaciones de trabajo en redes locales, ideal para entornos educativos. A continuación, te guiaré para instalar Veyon utilizando el gestor de paquetes Winget en Windows.
1.	Podemos hacerlo más rápido desde terminal abrimos el PowerShell en modo administrador y usamoes el gestor de paquetes winget:
 
2.	Si recibes la versión de Winget, puedes continuar con la instalación. Si no tienes Winget instalado, sigue las instrucciones de Microsoft para instalar Winget o asegúrate de tener una versión de Windows 10/11 actualizada.
A continuación, instalamos Veyon con el comando que se muestra en la captura:
 
¿Qué hacer si winget no instala Veyon?
En algunos casos, la instalación a través de winget puede no funcionar debido a que no encuentra la última versión disponible o el paquete no está actualizado. Si esto ocurre tendrás que descargarlo desde la web oficial: https://veyon.io/en/. Descarga la última versión estable del instalador manualmente para Windows. Sigue las instrucciones de instalación que aparecen durante el proceso de configuración para completar la instalación de manera manual.
 
Configuración del Veyon alumnado
Buscamos la aplicación Veyon Configurator:
 
Agregar la clave pública
El alumnado tendrá que descargarse la clave pública en el siguiente enlace (https://drive.google.com/file/d/12t_tRxboFRjtL_m_GFqNCgr700u8i0_X/view?usp=sharing)  y agregarla en la sección de claves de autentificación, hay que descargarla en documentos si la pones en el escritorio podría no funcionar.
 

Cambiar idioma y autentificación
Seguidamente cambiamos el idioma de la interfaz de usuario a español y en la sección de Autentificación ponemos como método “Autentificación mediante archivo de clave” por último solo nos queda aplicar al final de la ventana y aceptar el reinicio para que se apliquen los cambios:
 








Cambiar nombre al equipo
Para ello usamos el siguiente comando:
 
Hay que cambiar los asteriscos por el nuevo nombre del equipo la sintaxis Aula-PC00, ejemplo 301-PC01, R03-PC01…una vez sejecutado el comando se reiniciara el equipo con el nuevo nombre.


 
Configuración del Veyon profesorado
Seguimos los mismos pasos que el alumnado, pero en vez de añadir la clave pública, añadimos solo la clave privada que se encuentra en la siguiente ruta: 
 
Crear grupo y añadir portátiles
Para ello hay que abrir la el veyon configurator y en la sección de ubicaciones creamos los grupos (aula, ASIR1, ASIR2...) y vamos añadiendo los equipos con añadir el nombre del equipo en la segunda columna es suficiente, en caso de tener alumno con portátiles hay que poner aquí el nombre del portátil del alumno:
(No se obliga en ningún momento a instalarlo en los equipos personales, para todo ello están los equipos de clase en caso de querer hacer el examen en sus propios equipos se ha de instalar este aplicativo)
 
