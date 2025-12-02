# Trabajo Práctico Final - Visión por Computadora II
## CEIA - FI-UBA

### Integrantes
* Calabia, Juan Manuel (a2107)
* Cofré, Francisco (a2112)
* Ceballos, Luciano (a2110)

---

## Descripción del Proyecto

El objetivo de este trabajo es la **detección de anomalías en escáneres de rayos X de equipajes** mediante el uso de aprendizaje profundo.

El modelo desarrollado está entrenado para identificar y localizar 5 clases de objetos potencialmente peligrosos dentro del equipaje:
* Pistola (firearm)
* Cuchillo (knife)
* Alicates (pliers)
* Tijeras (scissors)
* Llave inglesa (wrench)

Esta implementación busca facilitar y automatizar la vigilancia inteligente en los sistemas de seguridad de los aeropuertos, mejorando la precisión y eficiencia de los operadores.

## Dataset: X-Ray Baggage Scanner Anomaly Detection

* **Origen:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/orvile/x-ray-baggage-anomaly-detection)
* **Descripción:** El dataset consiste en imágenes de rayos X de equipajes con sus correspondientes anotaciones (bounding boxes) para las 5 clases de objetos mencionadas. El análisis exploratorio (EDA) reveló que se trata de un dataset con objetos generalmente pequeños, centrados en la imagen y con un desbalanceo moderado en la clase `pliers`. 
```
