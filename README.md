# Bacterial Colony Segmentation using Computer Vision Techniques in Python

---
Autores:

- Cardona Duque, David
- Marín Roa, Rubén Santiago
- Martin Acosta, David Esteban
- Sanchez Gonzalez, Jose Miguel
- Agudelo Gonzalez, Gabriel
---

## Objetivos

### Objetivo general 

Emplear técnicas de visión artificial para procesar de manera eficaz imágenes de un cumulo de bacterias y predecir una mascara para las mismas.

### Objetivos especificos

-	Procesar las imágenes del dataset de tal manera que podamos facilitar el proceso de segmentación, intentando hacer que las características de las células resalten mas a la hora de extraer bordes.

- Usar las imagenes procesadas para generar un treshold mediante el metodo de otsu y producir una segmentacion por umbralizacion

-	Usar las imágenes preprocesadas para alimentar una red neuronal la cual se encargará de realizar el proceso de segmentación prediciendo la máscara de las bacterias

## Justificación 

Los cultivos de bacterias son imágenes con las que es interesante trabajar puesto que la manera en la que estas se agrupan crea el reto de intentar extraer aquellas partes de un cultivo en las que se encuentran bacterias y en las que no.
La idea de este proyecto es intentar crear una mascara que ayude a diferenciar las bacterias ya sean aisladas o en un cumulo de un cultivo dado. Para esto usamos un dataset con 1200 imágenes las cuales contienen tanto imágenes con bacterias aisladas como agrupadas en un lugar del cultivo, y usando herramientas de visión artificial buscamos preparar las imágenes de la mejor manera posible para poder obtener las características que hacen que podamos identificar la ubicación de las bacterias en el cultivo.
