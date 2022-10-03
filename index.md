# Despliegue de aplicaciones web - JOB 2

David Gómez Redondo

Comparación entre montaje de stack tecnológico para servidor web (`WAMP`) por módulos o a través de una distribución.

## Montaje modular

1. ¿En qué sitios web se descargan los distintos módulos fundamentales?

2. ¿Qué versiones se descargan de cada módulo? Tener en cuenta la compatibilidad.

3. ¿Qué ficheros de configuración tiene cada módulo? Indicar nombre y contenido.

## Montaje por distribución

1. Indicar 3 o 4 de las distribuciones `WAMP` disponibles en el mercado.

Algunos ejemplos de distribuciones `WAMP` son los siguientes: `EasyPHP`, `AppServ`, `XAMPP`, `WampServer`.

2. ¿Qué contienen dichas distribuciones?

  Todas incluyen `Apache`, `PHP` y `phpMyAdmin`, además de eso:

  - `EasyPHP` incluye `MySQL` y `Nginx`. Su web destaca que viene con dos servidores: uno destinado a producción y otro para desarrollo.
  - `XAMPP` integra `MariaDB`, `Webalizer`, `Mercury Mail Transport System`, `FileZilla`, `Tomcat` y `Perl`.
  - `WampServer` agrega `MariaDB` o `MySQL`, `Adminer` y `phpSysInfo`.

3. ¿Qué distribución emplearía? Justifique su respuesta.

## ¿Cuál sería su elección? Justifique su respuesta

`WampServer` es desde mi punto de vista la mejor alternativa. Soporta múltiples versiones de las distintas tecnologías que ofrece y permite escoger entre `MariaDB` y `MySQL`. La otra alternativa sugerente es `XAMPP`, sin embargo ofrece tantas tecnologías *out of the box* que puede resultar innecesariamente pesado o complejo.
