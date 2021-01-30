# CVDSLAB2

## La Herramienta Maven
### Cual es su mayor utilidad?

Manejar la creación, los informes y la documentación de un proyecto a partir de una pieza central de información.

Consultado en [Apache Maven](https://maven.apache.org/)

### Fases de maven:

Las fases de Maven son las siguientes:
1. Validar: Revisar si toda la información necesaria para el constructor esta disponible.
2. Compilar: Compilar el código base.
3. Compilar-test: Compilar los tests del código base.
4. Test: Compilar pruebas de Unidad.
5. Package: Paquete del código compilado en el formato seleccionado (jar, entre otros).
6. Test de Integración: Procesa y despliega el paquete si necesita correr pruebas de integración.
7. Instalación: Instala el paquete en un repositorio local.
8. Despliegue: Copiar el paquete en un repositorio local.

### Ciclos de vida de la construccion:
Maven se basa en el concepto central de un ciclo de vida de construcción. Lo que esto significa es que el proceso para construir y distribuir un artefacto en particular (proyecto) está claramente definido. Para la persona que crea un proyecto, esto significa que solo es necesario aprender un pequeño conjunto de comandos para construir cualquier proyecto Maven, y el POM se asegurará de que obtenga los resultados que desea. Hay tres ciclos de vida de compilación integrados: `default`, `clean`, `site`.


