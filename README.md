# <p align="center"> 📈 Tableau Public para visualizar datos climáticos 📈 | 📍 Martes 21 de diciembre a las 18:00h CET

+ [Introducción](#a-bullet) 
+ [Datos](#b-bullet) 
+ [Resultados](#e-bullet)
+ [Recursos](#c-bullet) 
+ [Desafío](#d-bullet)
            
# :hourglass_flowing_sand: Introducción <a name="a-bullet"/>
El análisis de datos es crucial para que la sociedad pueda encontrar las mejores soluciones a los desafíos ambientales y sociales a los que nos enfentamos 🎯. Sin él, el último informe del IPCC (Panel Intergubernamental sobre Cambio Climático), por ejemplo, no sería posible.

Usaremos Tableau Public para explorar el efecto del confinamiento y parón de actividad en los niveles de contaminantes del aire durante el primer trimestre de 2020.

📌 📌 ¡El taller es apto para principiantes! Todo lo que se necesita es un ordenador, una buena conexión a Internet y configurar un perfil de Tableau Public para guardar tu trabajo y poder usar la herramienta (es fácil de hacer y puedes descargar la versión de escritorio [aquí](https://public.tableau.com/s/)).

# :speech_balloon: Datos <a name="b-bullet"/>
Esta carpeta contiene los materiales para el análisis:
  
Al comienzo del taller puedes encontrar los 
[datos](https://github.com/ang-ferriz/tableau-webinar-21diciembre21/tree/main/Datasets) con los que estamos trabajando:
- :globe_with_meridians: Dataset 1 | `dataset1_global_no2.xlsx` (archivo Excel): cambios globales de los niveles de NO2. Datos editados para dejar solo las columnas que nos interesan para este caso. El conjunto de datos original se puede encontrar en [_Data for: Impact of Lockdown during the COVID-19 Outbreak on Global Air Quality_](https://data.mendeley.com/datasets/wwjnw24xvk/1).
- :chart_with_downwards_trend: Dataset 2 | `data2_filtered.csv` (Comma Separated Values file / archivo de valores separado por comas): algunos datos de NO2, PM 2.5, PM 10 para lugares específicos. El conjunto de datos original, que era un archivo realmente grande con muchas medidas, se editó para facilitar el trabajo. Está disponible en el repositorio el archivo de python Jupyter Notebook, [pre_processing_Q12020_data.ipynb](https://github.com/ang-ferriz/tableau-webinar-21diciembre21/blob/main/pre_processing_Q12020_data.ipynb), con los pasos de limpieza simplemente para mostrar cómo el conjunto de datos original de la [_Air Quality Open Data Platform_](https://aqicn.org/data-platform/covid19/) se filtró.
            
¿¡Preparadxs!? ¡Vamos! 🙌

# 🔍 Resultados <a name="e-bullet"/>
            
En el enlace siguiente podemos acceder al libro de trabajo de Tableau resultante del taller, siguiéndolo veremos el [tablero final](https://public.tableau.com/app/profile/.ngela4803/viz/webinar_tableau_21diciembre21/Cambio-MapaGlobal), es posible descargar el archivo y abrirlo en local o con el software online para ver cómo se han hecho los gráficos.
¿Cómo descargarlo?
Siguiendo el enlace y clicando en el botón que sale bajo la barra horizontal azul oscura, arriba a la derecha de la página, en tono claro, con una caja horizontal y una flecha, este:
<p align="center"> <img src="https://github.com/ang-ferriz/tableau-webinar-21diciembre21/blob/main/Imagenes/boton_descarga.PNG" width="1000px" height="auto">


Algunas de las ideas extraídas de las visualizaciones:

📅 Los valores de NO2 durante el primer trimestre de 2020 muestran que el confinamiento tuvo un efecto positivo (reducción) sobre muchos de los indicadores globales. En la mayoría de los casos las variaciones (aumento o disminución) fueron pequeñas y cabe destacar que los lugares en los que aumentó de forma significativa la presencia del contaminante en aire durante 2020 son minoría.
            
🛑 La elección de Italia como caso de estudio se debe a la notable disminución de los niveles de los indicadores de contaminación donde, según los datos de variación de NO2 globales, el porcentaje de variación en comparando 2015-2019 y 2020 estuvo cerca del -35%, probablemente se redujo significativamente durante el bloqueo de actividad debido al cierre del transporte y la baja movilidad.

🚗 Las reducciones significativas de los niveles de contaminantes fueron claras a pesar de que el confinamiento aún no había comenzado, esto podría ser una señal de desaceleración en las actividades económicas. Dado que el dióxido de nitrógeno se emite como resultado de los procesos de combustión de combustibles fósiles, principalmente de las actividades de los vehículos de calle en las zonas urbanas, tiene sentido que se muestre una reducción en el gráfico.
            

# :books: Recursos <a name="c-bullet"/>
Algunos recursos para aprender más:
            
- [Calidad del aire ambiente (exterior) y salud.](https://www.who.int/es/news-room/fact-sheets/detail/ambient-(outdoor)-air-quality-and-health) Organización Mundial de la Salud
- [Pandemia de COVID-19 en Italia.](https://es.wikipedia.org/wiki/Pandemia_de_COVID-19_en_Italia) Wikipedia, la enciclopedia libre. 
- [Prácticas recomendadas del análisis visual: guía.](https://www.tableau.com/es-es/learn/whitepapers/tableau-visual-guidebook?_ga=2.44606116.1623985826.1640252347-1210415786.1635244401) y [Prácticas recomendadas de análisis visual.](https://help.tableau.com/current/blueprint/es-es/bp_visual_best_practices.htm) Tableau. 
            
# :fire: Desafío <a name="d-bullet"/>
Algunas tareas relacionadas con el taller para ampliar y practicar con los datos y Tableau:
            
- Reduce el tamaño de los puntos del mapa de comparaciones globales
            
- Añade leyenda de colores para mostrar
            
- Añade etiquetas a los valores máximo y mínimo en las hojas de los ranking
            
- Anota la barra de Italia en el ranking
            
- Quita las líneas verticales de cuadrícula del fondo
            
- En el dasboard edita el formato de los títulos (tamaño de las letras y color) como prefieras que se muestren

El aspecto final quedaría como la imagen de abajo pero puedes hacer que luzca como quieras. 
            
<p align="center"> <img src="https://github.com/ang-ferriz/tableau-webinar-21diciembre21/blob/main/Imagenes/dashboard_tableau.png" width="1000px" height="auto">


Os animo a que practiquéis editando los gráficos y el tablero. Si queréis explorar más allá, es interesante escoger, filtrando los mismos dataset, otro país/países y realizar una comparación de si la tendencia que muestran los datos globales se corresponde con los datos de los contaminantes por separado para el primer cuarto de año 2020 o si resultan ser diferentes a lo esperado. 👀

            
🚀🚀🚀¡¡Seguimos!!🚀🚀🚀


<p align="right"> ¿Conectamos en <a href="https://www.linkedin.com/in/ang-sanchez/" target="blank"><img align="right" src="https://github.com/ang-ferriz/tableau-webinar-21diciembre21/blob/main/Imagenes/linkedin_logo.png" alt="Ángela S." height="30" width="30" /> Linkedin </a> ?

<p align="right"> ¿Por mail?   <a href="mailto:angela.s.ferriz@gmail.com " target="blank"><img align="right" src="https://github.com/ang-ferriz/tableau-webinar-21diciembre21/blob/main/Imagenes/gmail_logo.png" alt="Ángela S." height="25" width="30" /> angela.s.ferriz@gmail.com </a> o clica en el logo

</p>
