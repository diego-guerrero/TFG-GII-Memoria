# Trabajo Fin de Grado - Grado en Ingeniería Informática

**Título del trabajo**: VSCode4Teaching: implementación de interfaz web para el ecosistema para la docencia de la programación en línea.  
**Autor**: Diego Guerrero Carrasco ([correo electrónico](mailto:diegogcarrasco@icloud.com), [perfil en GitHub](https://github.com/diego-guerrero), [perfil en LinkedIn](https://www.linkedin.com/in/diego-guerrero-carrasco/)).  
**Titulación**: Grado en Ingeniería Informática (dentro del Doble grado en Ingeniería Informática e Ingeniería del *Software*), Escuela Técnica Superior de Ingeniería Informática, Universidad Rey Juan Carlos (Madrid, España).  
**Defendido** el martes 16 de julio de 2024 en el Campus de Móstoles de la Universidad Rey Juan Carlos.

El presente repositorio contiene los ficheros fuente empleados para la generación de la memoria del Trabajo Fin de Grado correspondiente al Grado en Ingeniería Informática.


## Resumen
Desde su origen, [*VSCode4Teaching*](https://github.com/codeurjc-students/2019-VSCode4Teaching) ha venido siendo una extensión web para Visual Studio Code, un entorno de desarrollo integrado, que tiene como objetivo facilitar y potenciar la docencia de la programación informática para mejorar la educación en competencias digitales y en el ámbito de la informática, área en pleno crecimiento y promulgación a nivel global.

Para ello, *VSCode4Teaching* permite a los profesores crear y gestionar cursos con ejercicios de programación que se basan en una plantilla inicial propuesta por ellos y, opcionalmente, una propuesta de solución al ejercicio. Los alumnos inscritos en los cursos completarán los ejercicios descargándose la plantilla y realizando sobre ella su propuesta propia de resolución, sincronizándola con el servidor para guardarla e informar en tiempo real a sus profesores de los avances realizados hasta finalizarla.

La memoria de este Trabajo Fin de Grado describe en profundidad el ciclo de desarrollo relativo al cuarto hito evolutivo del proyecto *VSCode4Teaching*, en el que se implementa una aplicación web de navegador que incorpora los procesos de negocio que los usuarios ejecutaban en la extensión de Visual Studio Code, eliminando la obligatoriedad de uso de este entorno para alcanzar a un público objetivo mayor.

El *software* del proyecto se organiza en una arquitectura cliente-servidor. El servidor, encargado del suministro, persistencia e interpretación de los datos, intercambia información con dos clientes: la extensión para Visual Studio Code y la aplicación web de navegador, que disponen en consecuencia las interfaces gráficas necesarias para la interacción con la aplicación.

El proyecto *VSCode4Teaching* es *software* libre divulgado bajo licencia Apache 2.0 a través de un [repositorio público en GitHub](https://github.com/codeurjc-students/2019-VSCode4Teaching) que contiene, además, documentación sobre el proyecto para favorecer la libre ejecución, utilización y adaptación del proyecto a toda la comunidad de desarrolladores.


## Recursos asociados
- Código fuente del proyecto VSCode4Teaching tras finalizar este Trabajo Fin de Grado: [https://github.com/diego-guerrero/TFG-GII-VSCode4Teaching](https://github.com/diego-guerrero/TFG-GII-VSCode4Teaching).


## Publicación en abierto
La memoria queda publicada en abierto en el Repositorio Institucional de la Universidad Rey Juan Carlos, siendo públicamente consultable a través del siguiente enlace: [https://hdl.handle.net/10115/38213](https://hdl.handle.net/10115/38213).

Este repositorio complementa esta publicación mediante la divulgación en abierto de todos los recursos empleados para generar la memoria.


## Licencia
Este documento y todos los recursos de elaboración propia empleados para su confección se divulgan bajo licencia **CC-4.0-BY-SA** (*Atribución-CompartirIgual 4.0 Internacional* de Creative Commons), tal como se constata dentro del propio documento y como se especifica detalladamente en el fichero anexo [`LICENSE`](LICENSE).


## Organización del repositorio
El presente repositorio incluye todo el código fuente y recursos empleados para la confección de la memoria de este Trabajo Fin de Grado. Se distribuyen de la siguiente forma:
- [`2024_TFG_GII_DiegoGuerreroCarrasco.pdf`](2024_TFG_GII_DiegoGuerreroCarrasco.pdf). Es el documento compilado de LaTeX que contiene la memoria íntegra. Esta misma memoria ha sido la depositada en la Universidad Rey Juan Carlos para su defensa y calificación.
- [`2024_TFG_GII_DiegoGuerreroCarrasco.tex`](2024_TFG_GII_DiegoGuerreroCarrasco.tex). Es el fichero raíz de LaTeX que determina los datos básicos y la estructura de la memoria.
- [`secciones`](secciones/). Es la carpeta que recoge todos los contenidos textuales de la memoria de forma jerarquizada en ficheros `.tex` separados por la sección y subsecciones a las que pertenecen. Se puede seguir la jerarquía de importaciones desde el fichero raíz hacia abajo de forma arborescente.
- [`imagenes`](imagenes/). Es el directorio que incluye todas las imágenes utilizadas para la memoria. Contiene dos subdirectorios:
    - [`utilizadas`](imagenes/utilizadas/). Recoge todas las imágenes empleadas en la memoria, categorizándolas por la sección y/o subsección en que se ubican dentro de la estructura de la memoria.
    - [`originales`](imagenes/originales/). Incluye todos los recursos originales que han dado lugar a las imágenes finalmente empleadas. Entre estos recursos hay capturas de pantalla originales, montajes realizados utilizando Pixelmator Pro (`*.pxd`) y otrs recursos de interés para la generación de las figuras y tablas incluidas.
