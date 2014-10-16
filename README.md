# GDG DevFest Lima 2014 site template


### Licence
Project is published under the [MIT licence](https://github.com/gdg-x/zeppelin/blob/master/LICENSE.txt).

Clonar el repo:

$ git clone http://github.com/GDGLima/DevFestLima2014

Actualizar el _config.yml

Requerimientos:

Instalar Ruby y Rails, recomiendo via RVM: 

$ \curl -L https://get.rvm.io | bash -s stable --rails

$ source ~/.rvm/scripts/rvm

Actualizar gemas:

gem update -system

--------

En la ruta que clonaron el repo, ingresar al directorio e instalar jekyll

$ gem install jekyll

Run: (port default 4000)

 $ jekyll serve -w

Run en :80 (chequear antes que ningun servicio use el 80)

 $ jekyll serve -w --port 80

*correrá en http://localhost:4000/devfestlima/
*correrá en http://localhost/devfestlima/

*si en caso no arranca es porque por el java runtime necesitan instalar la gema: gem install therubyracer
