### Universidad Continental  
**Maestría en Economía**  
**Curso:** Herramientas Informáticas I  
**Profesor:** Joel Turco Quinto

---

##  Integrantes

- Rafael Marcos Lapa Camargo  
- Danilo Milenio Cueva Santos  
- Paola Jessyca Bibians Jara Loayza  
- Edison Marcavillaca Niño de Guzmán

---

##  Proyecto: Visualización y Dashboard - Gapminder

Este proyecto consiste en el desarrollo de una aplicación interactiva en R con **Shiny**, utilizando el dataset `gapminder`. A través del dashboard, se exploran temas de estadística descriptiva, análisis exploratorio y econometría básica y múltiple.

Se emplean técnicas de visualización avanzadas con **Plotly**, **ggplot2**, y **gganimate**, junto a herramientas de transformación de datos con **dplyr** y **janitor**.

---

##  Tecnologías utilizadas

- R y RStudio
- Paquetes: `shiny`, `ggplot2`, `plotly`, `dplyr`, `gapminder`, `broom`, `janitor`, `tidyverse`, `ggthemes`, `scales`, `viridis`, `gganimate`, `patchwork`, `ggrepel`, `ggridges`

---

## Funcionalidades del Dashboard

-  Visualización de esperanza de vida y PIB per cápita por país  
-  Gráficos comparativos por continente  
-  Animación tipo Gapminder con evolución histórica  
-  Histogramas, boxplots y regresiones simples y múltiples  
-  Identificación del país más rico por continente  

---

##  Demo en línea

 Puedes ver la aplicación funcionando aquí:  
 [https://rlapac.shinyapps.io/herramientas_informticas_i-25mdtam002-psma-01043-2336-202501/](https://rlapac.shinyapps.io/herramientas_informticas_i-25mdtam002-psma-01043-2336-202501/)

---

##  Estructura del repositorio

 app.R # Código principal de la app
 gapminder-pbi-vida_.Rproj # Proyecto RStudio
 README.md # Este archivo

---

##  Instrucciones de uso

1. Clona el repositorio con Git o descarga el ZIP.
2. Abre el archivo `.Rproj` en RStudio.
3. Asegúrate de tener instalados los paquetes necesarios (ver código en `app.R`).
4. Ejecuta `shinyApp(ui = ui, server = server)` o presiona Run App en RStudio.

---

> Proyecto desarrollado con fines académicos para la Maestría en Economía — Universidad


