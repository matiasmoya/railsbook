# Readme (beta)

Para sugerencias o solicitar algun tema para el libro en particular, por favor cree un [Issue](https://github.com/matiasmoya/railsbook/issues)

Si deseas contribuir a este repositorio deberas hacer un fork, instalar [Softcover](http://softcover.io/), y abrir un pull request una vez lista tu contribucion.

La gema de softcover tiene algunas dependencias que pueden no estar instaladas en tu OS tales como curb y texlive (for unix environments)
Para verificar si tienes la gema curb puedes hacerlo con `gem list curb`, si no aparece en la lista simplemente procede con `gem install curb`
Si tienes problemas instalando curb, probablemente necesitas instalar *libcurl4* usando `sudo apt-get install libcurl4-openssl-dev` 

La segunda dependencia es latex. Puedes revisar si esta instalda con `which xelatex`. Si el comando no devuelve nada deberas instalar latex siguiendo los pasos que se encuentran en [Latex Project](http://latex-project.org/ftp.html). (Usando apt basta con tipear `sudo apt-get install texlive-full`).

Latex pesa un poco mas de 1gb, por lo que la descarga e instalacion pueden demorar.

Una ves listas las dependencias puedes instalar la gema softcover con `gem install softcover`.

Instrucciones mas detalladas podras encontrar en [Softcover quickstart](https://www.softcover.io/start) o leyendo el [Manual de softcover](http://manual.softcover.io/book)
