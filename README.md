Recomendaciones
===============

Las publicaciones de Acid Labs tienen como objetivo integrarnos como equipo a la comunidad de desarrolladores de código abierto con el fin de aprender, compartir conocimiento y ganar visibilidad como empresa.


Indispensables
--------------

### README

Es indispensable que todo proyecto publicado tenga un `README` en el que se describa el proyecto, su uso y se mencionen los copyrights y licencias a los que está sometido.

Se recomienda escribirlo [antes de comenzar el proyecto][1] cuando están todas las ganas para hacerlo. Además, eso ayuda a mantener los objetivos claros a lo largo del desarrollo.

  [1]: http://tom.preston-werner.com/2010/08/23/readme-driven-development.html

### LICENSE.txt

La licencia en texto plano (`LICENSE.txt`). Se recomienda usar la [GLPv3][GPLv3], o eventualmente la licencia X11 (conocida como licencia [MIT][MIT]).

  [GPLv3]: http://www.gnu.org/licenses/gpl-3.0.txt
  [MIT]: http://opensource.org/licenses/MIT

El `README` debe comportar una sección *License* en la que se reproduzca el **disclaimer** correspondiente a la licencia (ver el [disclaimer de la GPLv3][disclaimer]).

  [disclaimer]: http://gplv3.fsf.org/wiki/index.php/Howto

### Copyrights

Legalmente, quienes poseen el _copyright_ son quienes tienen derecho a decidir sobre la licencia bajo la cual se publica algo. Es necesario mencionar los _copyrights_ de Acid Labs y de los autores y autoras en la sección _License_ del `README` y donde sea necesario de la siguiente forma:

    Copyright (C) 2011-2013 Acid Labs
    Copyright (C) 2011 Carlos Gardel
    Copyright (C) 2011-2013 Antonia López Quiroga


Fuertemente recomendados
------------------------

### Travis-ci

[Travis-ci][travis] es un servicio de integración contínua de código libre. Es gratuito, está integrado con Github.

  [travis]: https://travis-ci.org/

Trabajar con _Travis-ci_ es sencillo, así se usaría para agregarle funcionalidad a la gema `tbk-rails`:

 1. Crear el branch `feature-bootstrap-option-for-views-generator`
 1. Desarrollar ejecutando los test relativos a los generadores de vistas.
 1. Una vez que la funcionalidad está completa, subir el branch a Github: `git push -u origin feature-bootstrap-option-for-views-generator` para gatillar _Travis-ci_
 1. Travis informa automáticamente en cuanto haya terminado de correr la suite de tests entera
 1. Si el resultado es positivo se puede hacer el _merge_ de `feature-bootstrap-option-for-views-generator` en `master`


Sugeridos
---------

### Para Ruby: Code Climate

[Code Climate][code-climate] es un servicio ([gratuito para proyectos open-source][code-climate-oss]) que inspecciona código en Ruby en busqueda de repeticiones, _code smells_ e identifica áreas candidatas para refatorizar. Tal como _Travis-ci_, tiene muy buena integración con Github.

  [code-climate]: https://codeclimate.com/
  [code-climate-oss]: https://codeclimate.com/github/signup
