
# Materiales de cursada
[![](img/Download.png)](Materiales.zip)



> Docentes: Pablo Tiscornia - Guido Weksler - Diego Kozlowski - Natsumi Shokida.


### Presentación
En los últimos años se han difundido muchas herramientas estadísticas novedosas para el análisis de información socioeconómica. En particular el software denominado "R", por tratarse de un software libre, se extiende cada vez más en diferentes disciplinas y recibe el aporte de investigadores e investigadoras en todo el mundo, multiplicando sistemáticamente sus capacidades.
  
Este programa se destaca, entre varias cosas, por su capacidad de trabajar con grandes volúmenes de información, utilizar múltiples bases de datos en simultáneo,  generar reportes, realizar gráficos a nivel de publicación y por su comunidad de usuarios y usuarias  que publican sus sintaxis y comparten sus problemas, hecho que potencia la capacidad de consulta y de crecimiento. A su vez, la expresividad del lenguaje permite diseñar funciones específicas que permiten optimizar de forma personalizada el trabajo cotidiano con R. 

*** 
  
### Objetivos del curso
El presente Taller tiene como objetivo principal introducirse en el aprendizaje del lenguaje de programación “R” aplicado procesamiento de la Encuesta Permanente de Hogares (EPH) - INDEC. Se apunta a brindar a los y las participantes herramientas prácticas para el procesamiento de datos haciendo énfasis en la producción y el análisis de estadísticas socioeconómicas en pos de abrir puertas para realizar investigaciones propias sobre diversas temáticas relacionadas al mercado de trabajo y las condiciones de vida de la población.
  
La Encuesta Permanente de Hogares será la base de datos de aplicación elegida para el curso, dado que representa un insumo fundamental para realizar estudios sobre el mercado de trabajo y las condiciones de vida de la población. Se hará una introducción a los lineamientos conceptuales principales de la encuesta, en pos de que los y las participantes puedan abordar con datos distintas problemáticas vinculadas al mercado de trabajo y las condiciones de vida de la población.

*** 
  
# Programa

### Clases y contenido


  
__Clase 1 - Conceptos Principales de EPH:__
  
+ Temas de clase: 
  + Presentación del curso.
  + Presentación de la Encuesta Permanente de Hogares: Lineamientos conceptuales y metodología
  + Abordaje del marco teórico y analítico de la EPH y sus aplicaciones prácticas.
  + Síntesis del operativo de campo, cobertura y periodicidad de la Encuesta
  + Definiciones de las principales variables de interés a abordar en el curso: Condición de actividad, categoría ocupacional, precariedad y pobreza
  + Metodología usuaria de las Bases de microdatos. Utilización del Diseño de Registro.
  
+ [Presentación](https://pablotis.github.io/Presentaciones/clase1_eph.html#1)

<br>

__Clase 2 – Introduciendo a R:__
  
+ Temas de clase:
  + Descripción del programa “R”. Lógica sintáctica del lenguaje y comandos básicos
  + Presentación de la plataforma RStudio para trabajar en “R”
  + Caracteres especiales en “R”
  + Operadores lógicos y aritméticos
  + Definición de Objetos: Valores, Vectores y DataFrames
  + Tipos de variable (numérica, de caracteres, lógicas)
  + Lectura y Escritura de Archivos
  
+ [Presentación](https://pablotis.github.io/Presentaciones/clase2_intro_R.html#1)
+ [Explicación](Clase%202%20-%20R%20Base/Clase%202%20-%20Introduccion%20a%20R.nb.html)
+ [Práctica guiada](Clase%202%20-%20R%20Base/Clase%202%20-%20Practica%20guiada.nb.html)
+ [Práctica independiente](Clase%202%20-%20R%20Base/Clase%202%20-%20Practica%20independiente.nb.html)
  
<br>

__Clase 3 – Clase 3 - Tidyverse - Tasas basicas__
  
+ Temas de clase:
  + Limpieza de Base de datos: Renombrar y recodificar variables, tratamiento de valores faltantes (missing values/ NA´s)
  + Seleccionar variables, ordenar y agrupar la base de datos para realizar cálculos
  + Creación de nuevas variables
  + Aplicar filtros sobre la base de datos
  + Construir medidas de resumen de la información
  + Tratamiento de variables numéricas (edad, ingresos, horas de trabajo, cantidad de hijos / componentes del hogar, entre otras).
  + Ejercicios prácticos para aplicar lo expuesto: Replicar Informe Técnico de Mercado de Trabajo (EPH-INDEC) 
  + Cálculo de tasas básicas del mercado de trabajo (tasa de actividad, empleo, desempleo, entre otras) 
  + Cálculo de tasas para distintos subconjuntos poblacionales (por aglomerado, sexo, grupos de edad)
  
+ [Explicación](Clase%203%20-%20Tidyverse%20-%20Tasas%20basicas/Clase%203%20-%20Bases%20de%20Datos%20y%20Mercado%20de%20Trabajo.nb.html)
+ [Práctica guiada](https://github.com/Guidowe/Curso-R-Flacso/blob/master/Clase%203%20-%20Tidyverse%20-%20Tasas%20basicas/Clase%203%20-%20Practica%20guiada.nb.html)
+ [Práctica Independiente](https://github.com/Guidowe/Curso-R-Flacso/blob/master/Clase%203%20-%20Tidyverse%20-%20Tasas%20basicas/Clase%203%20-%20Practica%20independiente.nb.html)
  
<br>

__Clase 4 - Tidyverse - Pobreza__
  
+ Temas de clase:
  + Definición de la Canasta Básica Alimentaria y Canasta Básica Total
  + Metodología del cálculo de pobreza por línea (para personas y hogares)
  + Ejercicio de estimación de tasas de Pobreza e Indigencia
  + Ejercicio de estimación de tasas de Pobreza e Indigencia para subgrupos poblacionales (Género, Edad, Regiones)

+ [Explicación](Clase%204%20-%20Tidyverse%20-%20Pobreza/Clase%204%20-%20Tidyverse%20y%20Pobreza.nb.html?raw=true)
+ [Práctica guiada](Clase%204%20-%20Tidyverse%20-%20Pobreza/Clase%204%20-%20Practica%20guiada.nb.html?raw=true)
+ [Práctica independiente](Clase%204%20-%20Tidyverse%20-%20Pobreza/Clase%204%20-%20Practica%20Independiente.nb.html?raw=true)
  
<br>

__Clase 5 - Visualización de la información__  

[![](img/Download.png)](Clase%205%20-%20Graficos.rar)

+ Temas de clase:
  + Gráficos básicos de R (función “plot”): Comandos para la visualización ágil de la información
  + Gráficos elaborados en R (función “ggplot”): 
    + Gráficos de línea, barras, Boxplots 
    + Extensiones de ggplot

- [Explicación](Clase%205%20-%20Graficos/05_explicacion.nb.html)
- [Práctica Guiada](Clase%205%20-%20Graficos/05_practica_guiada.nb.html)
- [Práctica independiente](Clase%205%20-%20Graficos/05_practica_independiente.nb.html)
  
<br>

__Clase 6: Documentación en R. Generación de reportes/informes.__
  
+ Temas de clase:
  + Manejo de las extensiones del software “Rmarkdown” y “RNotebook” para elaborar documentos de trabajo, presentaciones interactivas e informes:
    + Opciones para mostrar u ocultar código en los reportes
    + Definición de tamaño, títulos y formato con el cual se despliegan los gráficos y tablas en el informe
    + Caracteres especiales para incluir múltiples recursos en el texto del informe: Links a páginas web, notas al pie, enumeraciones, cambios en el formato de letra (tamaño, negrita, cursiva)
    + Código embebido en el texto para automatización de reportes

- [Explicación](Clase%206%20-%20Markdown/06_explicacion.nb.html)
- [Práctica guiada](Clase%206%20-%20Markdown/06_practica_guiada.nb.html)
- [Práctica guiada - dashboard](Clase%206%20-%20Markdown/06_practica_guiada_dashboard.html)
- [Práctica independiente](Clase%206%20-%20Markdown/06_practica_independiente.nb.html)

<br>

__Clase 7 -Strings__

[![](img/Download.png)](Clase%207%20-%20Strings.rar)

+ Temas de clase: 
  + Acercamiento a técnicas de text mining:
    + Paquete stringr: Localización, substracción, y reemplazo de patrones en variables strings 
    + Expresiones regulares
    + Corpus de texto, Normalización, Armado de DocumentTermMatrix y Nubes de Palabras

- [Explicación](Clase%207%20-%20Strings/Explicacion.nb.html)
- [Práctica Guiada](Clase%207%20-%20Strings/Practica_guiada_stringr_lubridate.nb.html)
- [Pŕactica independiente](Clase%207%20-%20Strings/Practica_independiente.nb.html)
  
<br>

__Clase 8: Programación Funcional:__

[![](img/Download.png)](Clase%208%20-%20Programacion%20funcional.rar)

+ Temas de clase: 
  + Acercamiento a técnicas más sofisticadas en R, útiles para automatizar el procesamiento periódico de la información:
    + Estructuras de código condicionales
    + Loops
    + Creación de funciones a medida del usuario

- [Explicación](Clase%208%20-%20Programacion%20funcional/explicacion.nb.html)
- [Práctica Guiada](Clase%208%20-%20Programacion%20funcional/practica_guiada.nb.html)
- [Pŕactica independiente](Clase%208%20-%20Programacion%20funcional/practica_independiente.nb.html)
  
<br>

__Clase 9: Trabajos prácticos, repaso general y consultas__
  

+ Se presentará a los/as alumnos/as problemas concretos vinculados a la EPH y en relación a las experiencias que se fueron volcando a lo largo de la cursada. Se deberán abordar mediante el uso de R, aplicando lo aprendido en los módulos anteriores. En conjunto se expondrán los desafíos que emergen en el momento y la evaluación de las herramientas adecuadas para su abordaje y resolución. Entre los temas giran aquellos vinculados a la distribución personal del ingreso/Construcción de percentiles de ingreso; el mercado laboral a través de la herramienta Panel de datos; la documentación en R (Estilo de Notas de Clase).
+	Espacio para consultas puntuales sobre los temas vistos durante el curso y presentación del trabajo final a entregar.

__Clase "Yapa" - Regresión Lineal__

[![](img/Download.png)](Clase%20yapa%20-%20Modelo-lineal.rar)

+ Temas de clase:
  + Covarianza
  + Correlación
  + Regresión lineal simple
  + Regresión lineal múltiple
  + Ingeniería de variables
  + Transformaciones log-lineales
  
  
<br>

#### Librerias a instalar

```
install.packages(c("tidyverse","openxlsx",'ggplot2','ggthemes', 'ggrepel','ggalt','kableExtra','GGally','ggridges','fs','purrr','rmarkdown','esquisse','eph','treemapify','gapminder','viridis'))
```
