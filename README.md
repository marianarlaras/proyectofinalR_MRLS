# Proyecto Final - Business Performance Analysis
Proyecto final Asignatura R
Profesor: Carlos Gil
EAEBS - BigData2019B

## Resumen 🚀

_El presente proyecto condensa gran parte de lo aprendido en la materia **Business performance analysis**, donde el lenguaje de programación predilecto ha sido R._

* En el apartado de ***"REGEX"***, se comenta un poco acerca de dos páginas webs, comparando su contenido y afinidad a mi gusto. De igual forma, se muestran enlaces adicionales de interés relativos a este tema y se direcciona a una cuenta de twitter de contenido interesante para compartir.
* En el apartado de ***"MarkDown"*** , se realiza la misma comparativa entre dos páginas de interés y se ponen en práctica en el presente documento.
* En el apartado de ***"Análisis Exploratorio"***, se ha seleccionado la información contenida en el Dataset de **FIFA2019**, extraído desde https://github.com/amanthedorkknight/fifa18-all-player-statistics/tree/master/2019 para su respectiva limpieza y evaluación.
* En la sección ***"Visualización con Leaflet"***, extraemos puntos de geolocalización a travee2és de la API de Google Maps Platform (para la cual se necesita una clave de API, se explica en el apartado "API Adicional" como gestionar esta utilidad) y se plotean dichos puntos a través de Leaflet en un mapa dinámico.


## Indice de Contenido
* [Autor](#team-members)
* [Pre-requisitos](#pre-requisitos)
* [API Adicional](#API)
* [Construido con](#Construido-con)
* [Agradecimientos](#Expresiones-de-gratitud)


## <a name="Autor"></a>Autor
* "Mariana Lara" <marianaRlaras@gmail.com> - >>> <https://github.com/marianarlaras/>


## <a name="Pre-requisitos"></a>Pre-requisitos📋
_Para realizar esta practica, se requiere tener instalado previamente los siguientes componentes y la lectura de sus respectivas librerías:_

```r
library("RCurl")
library("dplyr")
library("knitr")
library("kableExtra")
library("viridis")    
library("ggplot2")
library("gridExtra")
library("grid")
library("ggridges")
library("treemap")
library("tidyverse")
library("stringr")
library("ggforce")
library("DT")
library("RgoogleMaps")
library("ggmap")
library("rjson")
library("jsonlite")
library("leaflet")
```

## <a name="API"></a>API 🔧
_Se ha utilizado una de las APIs de [**Google Cloud Platform**](https://console.developers.google.com/) para obtener las coordenadas que se plotean en [Leaflet](https://leafletjs.com/)._

**PASOS IMPORTANTES PARA LA EJECUCIÓN DE LA API**
- Para utilizar la API de *Google Maps Platform* contenida en el apartado **Visualización con Leaflet**, es necesario obtener una **API KEY**, propia de cada usuario (*por temas de seguridad, cada usuario debe utilizar crear su clave*).
- Obten tu clave de seguridad en el enlace de [Google Cloud Platform > credentials](https://console.cloud.google.com/apis/credentials) 
- Posterior a tener tu clave, sobreescribe la información contenida en el documento **my_key-example.txt** que se encuentra en el fichero **secrets**: (secrets/my_key-example.txt), de esta forma puede ejecutarse el código con tus credenciales personales.


## <a name="Construido-con"></a>Construido con 🛠️
* [RStudio](https://rstudio.com/products/rstudio/download/) - Entorno de desarrollo integrado para aprender a usar R. 💻
* [GitHub](http://www.github.com/) - Aprendiend a utilizarlo en la marcha. 💣
* [Slack](https://slack.com/) - Utilizado para consultas.
* [Emojis](https://gist.github.com/rxaviers/7360908/) - Emojis Utilizados para dar un toque de originalidad al trabajo. 🆒
* [Google Cloud Platform](https://console.developers.google.com/) - Utilizado para extraer coordenadas de geolocalización. 🌍 
* [twitter](https://twitter.com/home) - Utilizado para obtener tweets de interés.🐦
* MUCHAS FUENTES DE AYUDA E INTERÉS.


## <a name="Expresiones-de-gratitud"></a> Agradecimientos 🎁
* A las clases de mis profesores y la curiosidad que han despertado en mí.
* A la paciencia y la tecnología. 
* A no rendirse.

> “For the things we have to learn before we can do them, we learn by doing them.”
― Aristotle

