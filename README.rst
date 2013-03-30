=====================
 laughing-dangerzone
=====================

Sitio Web de PyVE

Instrucciones para probar el sitio
==================================

La siguiente secuencia de comandos debería ser suficiente para probar el sitio::

    $ git clone git://github.com/pyve/laughing-dangerzone.git
    $ cd laughing-dangerzone
    $ mkvirtualenv pyve
    (pyve) $ pip install -r requirements/project.txt
    (pyve) $ python manage.py createdb # Responda NO a la carga de datos iniciales
    (pyve) $ python manage.py gnottify 

    # En otra terminal
    (pyve) $ python manage.py runserver

Vaya a http://127.0.0.1:8000 para ver el sitio.
