
# Complementos

----------

- �Qu� son? �C�mo se instalan?
- En esta parte vamos a ver 5 plugins imprescindibles si trabajas con QGIS,y algunos plugins desarrollados por los miembros del curso.

Los complementos son accesorios a la instalaci�n b�sica de QGIS que expanden su funcionalidad. Hay incontables complementos de libre acceso, pero en este curso hemos seleccionado s�lo cinco con fines demostrativos.

###Open Layers Plugin   ![](img/plugins/0.png?raw=true)

El primer complemento que debemos instalar es �**Open Layers**� plugin, que permite visualizar las capas de Google,Open Street Maps y otros, en el fondo de nuestro canvas.

Hacer clic en **Complementos/Administrar e instalar complementos**.

![](img/plugins/1.png?raw=true)

En el buscador superior pod�is escribir su nombre para filtrar los resultados.

![](img/plugins/2.png?raw=true)

Seleccionar e instalar **Open Layers**

| ***Ejercicio:A�adir la base im�genes sat�lite de Google al canvas de la sesi�n de QGIS*** |

### XYTools ![](img/plugins/3.png?raw=true)

Este complemento nos ayudar� a manejar tablas de Excel que contienen coordenadas x e y. Utilizaremos esta herramienta cuando queramos crear un shapefile de puntos a partir de coordenadas.

Para instalarlo, volvemos a **Complementos/Administrar e instalar complementos** y buscamos **xytools**

![](img/plugins/4.png?raw=true)

Esta herramienta puede accederse desde el men� **Vectorial-XY Tools**

**Nota**: Este complemento solo trabaja con archivos .xls (Excel 97-2003). Si tenemos una tabla .xlsx hay que convertirla a .xls primero.

| ***Ejercicio:Importar a excel el shapefile de rios.*** |

###CadTools  ![](img/plugins/5.png?raw=true)

Herramientas para llevar a cabo funciones de tipo cad.

Al igual que el resto, volvemos a **Complementos/Administrar e instalar complementos** y buscamos **CadTools** 
.
| ***Ejercicio: Con los datos proporcionados de la comunidad de Madrid ver que hacen las herramientas.*** |

###Qgis2treejs ![](img/plugins/6.png?raw=true)

Gracias al plugin **Qgis2treejs** podemos crear f�cilmente visualizaciones en 3D de nuestros datos geogr�ficos. Qgis2threejs es un plugin de Minoru Akagi que exporta los datos del terreno combinados con la imagen del canvas de QGIS y opcionalmente datos vectoriales a un archivo HTML que se puede ver en 3D en cualquier navegador web que soporte WebGL. Este complemento hace uso de la librer�a Three.js.

![](img/plugins/7.png?raw=true)

Basta con introducir el r�ster que contiene los datos de elevaci�n, el complemento utiliza los valores de elevaciones y los combina con la imagen de QGIS para crear un archivo HTML. la imagen 3D es din�mica, podemos ampliar, alejar y movernos por el mapa.Se muestran algunos ejemplos.

![](img/plugins/8.png?raw=true)

![](img/plugins/9.png?raw=true)

Aplicado a **Geolog�a** para ver sondeos.

![](img/plugins/10.png?raw=true)

| ***Ejercicio: Con la informaci�n vectorial y la capa base descargado de OLPlugin,realizar una visi�n en 3D.*** |

###MMQGIS

Es una colecci�n de  plugins para realizar operaciones con capas vectoriales. Contiene:

- Herramientas de animaci�n.
- Herramientas de creaci�n (buffer, grids, etiquetas,  hub, diagramas de voronoi).
- Herramientas de geocodificaci�n (Geocodificaci�n de CSV desde un servicio web, geocodificar desde una capa de carreteras).
- Herramientas de modificaci�n (mapas de colores, eliminaci�n de columnas, eliminaci�n de columnas duplicadas, conversi�n de geometr�as).
- Herramientas de combinaci�n (*merge layers, spatial join*).
- Herramientas de  importaci�n/ exportaci�n (de tabla de atributos a CSV, join desde CSV, geocodificaci�n, importaci�n /exportaci�n de geometr�as desde y a CSV).

| ***Ejercicio: Con la informaci�n vectorial suministrada realizar todo tipo de operaciones.*** |

##Otros Plugins

Acceder a **Complementos/Administrar e instalar complementos**, como en el resto y buscarlo por su nombre.

###CartoDB  ![](img/plugins/11.png?raw=true)

Permite ver,crear,editar o borrar datos desde tu cuenta de CartoDb usando Qgis.
[Enlace](http://plugins.qgis.org/plugins/QgisCartoDB/)

###QuickOSM ![](img/plugins/12.png?raw=true)

Permite ejecutar consultas desde Qgis para obtener datos de OSM.
[Enlace](http://plugins.qgis.org/plugins/QuickOSM/)

###Customize ToolBars![](img/plugins/13.png?raw=true)

Permite crear barras de herramientas personalizadas con los botones que el usuario quiera. Solo es necesario arrastrar y soltar los botones desde la parte izquierda a la barra creada en la parte derecha que el usuario quiera.
[Enlace](http://plugins.qgis.org/plugins/CustomToolBar/)

###Instagram2qgis![](img/plugins/14.png?raw=true)

Permite buscar y descargar imagenes de Instagram y crea un shapefile puntual con las mismas.
[Enlace](http://plugins.qgis.org/plugins/instagram2qgis/)

###Load QSS - UI themes![](img/plugins/15.png?raw=true)

Permite cargar archivos de estilo �*.qss� y cambiar el �look and feel� de Qgis.Se proporcionan algunos ejemplos.
[Enlace](http://plugins.qgis.org/plugins/LoadQSS/)