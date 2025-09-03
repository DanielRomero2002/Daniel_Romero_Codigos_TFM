# 📚 Códigos TFM – Daniel Romero

Bienvenido/a a este repositorio, donde encontrarás todos los notebooks y scripts desarrollados para mi Trabajo de Fin de Máster (TFM).

## 📝 Descripción

Este proyecto recopila el código utilizado para el TFM realizado en el Máster en Nuevas Tecnologías Electrónicas y Fotónicas de la Universidad Complutense de Madrid. Aquí podrás consultar, ejecutar y adaptar los notebooks que sustentan las distintas fases del trabajo: desde la exploración de datos y el procesamiento, hasta el modelado y la presentación de resultados.

## ⚙️ Elementos del repositorio

- **Notebooks:** Documentos interactivos con el desarrollo paso a paso de los experimentos y análisis. Tener en cuenta que los notebooks que se muestran son los usados sin ningún tipo de retoque, por lo que se ve cual fue la evolución de las herramientas y normalmente en las últimas líneas se llega al código que finalmente se emplea. Además, hay notebooks que debido a su tamaño hemos tenido que eliminar los resultados gráficos que proporcionaban ya que sino resultaba imposible subirlo a Github.

- **Librerías:** para este proyecto ha resultado fundamental emplear librerías de python las cuales han ayudado profundamente a realizar con mayor rapidez y simpleza todos los códigos. Entre estas librerías podemos destacar a numpy, scipy y orientationpy.

- **Datos (no incluidos):** Los notebooks están preparados para trabajar con los datos del TFM, que por razones de privacidad no se distribuyen en este repositorio.


- **Resultados:** Gráficas, resultados cuantitativos y tablas.


## Estructura del proyecto


```bash
.
├── fiber_viz/
├── visualizaciones/
├── main
├── 2D-TF_Espectro_Energia
├── 2D-TF_adaptativo
├── 3D_TF_para_volumen
├── Intensidad_y_Anisotropia
├── Orientacional_2D
├── Orientacional_3D
├── Prueba_Orientacional_ventanas
├── Hough_transform
├── Intento_visualizacion_3D
├── ChangesInCollagenStructureAndPermeability
├── diameter_fibers

```


## Información de cada apartado


Resaltamos que se ha dejado los códigos tal y como se desarrollaron. De esta manera hay códigos que su intento de implementación fue fallido y no aportó resultados pero que también fue importante el intentarlo para descartar ese tipo de análisis. Por lo que así, si uno lo desea, se puede observar detenidamente cual fue el proceso para desarrollar las distintas herramientas computacionales y apreciarse el tiempo dedicado a ello. 

-**main:** Código empleado para hacer de forma automática el tratamiento de las imágenes teniendo como entrada las carpetas con las imágenes tanto del ojo sin tratar como el tratado.

- **2D-TF_Espectro_Energia:** Se encuentra el desarrollo seguido para desarrollar los filtros de energía.

- **2D-TF_adaptativo:**  Definición de los filtros de línea adaptativos según la morfología del espectro filtrado de energía.


- **3D_TF_para_volumen:** Análisis de la transformada de Fourier tridimensional.


- **Intensidad_y_Anisotropia:** En el encontramos los mapas de DoI, los histogramas de PO, el DoI cuantitativo y la evolución de la intensidad.

-**Orientacional_2D:** Donde se emplea elementos análisis como la direccionalidad.

-**Orientacional_3D:** Contiene todas las herramientas computacionales del análisis orientacional tridimensional a excepción de las relacionadas con la Tranformada de Fourier.

-**Prueba_Orientacional_ventanas:** Primer intento de probar a analizar orientacionalmente en regiones locales de ventans de píxeles.

- **Hough_transform:** Implementación de las ventanas de píxeles automatizadas usando la transformada de Hough y el algorítmo de K-means clustering. 


-**Intento_visualizacion_3D:** Intento prematuro de realizar el mapeo tridimensional del comportamiento del colágeno basándose en un paper que lo hacía con las imagenes filtradas donde solo se tenía su esqueleto (usando skeletonize).



- **ChangesInCollagenStructureAndPermeability:** Intento fallido de ver un comportamiento o tendencia al filtrar gausianamente las imágenes.


- **diameter_fibers:** Código prematura por iniciativa del alumno para determinar el diámetro de las fibras escleróticas. 

- **fiber_viz y visualizaciones:** Carpetas con los resultados de los análisis de los diámetros fibrilares. Aunque no se ha añadido al TFM por recomendación del CSIC al haber muchos análisis de diametros en artículos científicos, se ha dejado porque fue un intento de la iniciativa del alumno
durante un pequeño periodo de tiempo.

## 🖥️ Tecnologías utilizadas

- Jupyter Notebook

- Python (principales librerías científicas: NumPy, Pandas, Matplotlib, Scikit-learn, orientationpy, etc.)

## 📈 Objetivos del TFM

El objetivo principal de este TFM fue el de desarrollar herramientas computacionales capaces de distinguir cambios en el comportamiento estructural y fibrilar del colágeno escleral cuando se le aplicaba el tratamiento SCXL a ojos de cerdo. Para poder extraer conclusiones y entender que ocurre a un nivel más profundo cuando se aplica esta técnica y, al ser esta efectiva con el tratamiento de la miopía, ayudar a comprender esta enfermedad ocular.

## 🏅 Autor

Daniel Romero Ruiz

Estudiante del Máster en Nuevas Tecnologías Electrónicas y Fotónicas

Universidad Complutense de Madrid

## 🚀 Cómo empezar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/DanielRomero2002/Codigos_TFM_Daniel_Romero.git
   ```
2. Abre los notebooks con Jupyter y sigue las instrucciones incluidas en cada uno.

3. Se pueden en la mayoría ver los códigos directamente en el github, pero algunos debido a su peso se tienen que descargar y verlos en tu ordenador. Algunos casos particulares no tienen las imágenes con los resultados ya que excedían el peso para publicarlos en github.
---

> Si tienes alguna duda, sugerencia o quieres colaborar, no dudes en contactar conmigo.
