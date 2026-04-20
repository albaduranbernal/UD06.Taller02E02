# --DEEP-SPACE: INVENTARIO DE EXOSPLANETAS--
Proyecto de catalogación y visualizacion de exosplanetas mediante **Base x** y tecnologías XML, siguiendo estándares de codigo limpio y semántica web 

# REQUISITOS: 
* **Motor**: Base X (XQuery 3.1).

# ESTRUCTURA: 
'exoplanetas.xml': Sería la "base de datos" de nuestra misión 
'exoplanetas.xsd': Esquema de la validación de datos 
'consultas': Scripts de Xquery 

# INSTRUCCIONES PARA SU USO: 
1. **Configuración del namespaces y rutas:** Declara siempre el namespace de archivos al inicio de tus scripts: declare namespace file= "http://expath.org/ns/file";
2. **IMPORTANTE**: Cambia la sintaxis de file:white() por una ruta absoluta de tu equipo (ej: C:/Users/TuUsuario/Escritorio/...) esto es para evitar que el archivo desaparezca
3. 3. **Ejecucion**: Ejecutamos las consultas en BaseX para generar los archivos '.html' de forma automatica 




