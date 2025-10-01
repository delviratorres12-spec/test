# test de shiny app en GitHub pages

$$\text{Esta es una prueba para construir un html estable que contenga una shiny app}$$


install.packages("shinylive")\
library(shinylive)\
Exporta la app a HTML y recursos estáticos\
shinylive::export(appdir = "test_app", destdir = "docs")\
