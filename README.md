# Actividad-Github
Creación de un repositorio de Github para aprendizaje del uso de la página.
# Tasa de riesgo por tratamiento de explantes in vitro
En el presente trabajo procedemos a realizar un análisis de tasas de riesgo para cada factor de tratamientos de cultivo de tejidos vegetales.
## Data
La data introducida corresponde a un experimento de viabilidad por un periodo de 17 meses correspondiente a medios de cultivo con 4 factores variables entre las formulaciones: concentración de sucrosa, concentración de sorbitol, concentración de ácido ascórbico y genotipos.
El archivo **supervivencia.txt** tiene una estructura con factores como genotipo, sucrosa, sorbitol y acido ascorbico, futime que corresponde al tiempo de evaluación y fustat que corresponde al estado de viabilidad:

| **Genotype** | **Treatment** |    **Sucrose**   | **Sorbitol**  | **Ascorbic_Acid** | **futime** | **fustat** |
|:------------:|:-------------:|:----------------:|:-------------:|:-----------------:|:----------:|:----------:|
| MU_51        |        1      |        20        |       0       |         0         |     240    |      1     |
| MU_51        |        1      |        20        |       0       |         0         |     330    |      1     |
| MU_51        |        1      |        20        |       0       |         0         |     330    |      1     |

##Resultado
La tasa de riesgo calculada ha sido obtenida mediante la modelización de un modelo de regresión de Andersen y Gill, el modelo generado será util para realizar la gráfica de tasas de riesgo por factor obteniendo como resultados que el ácido ascorbico y el sorbitol a 20 g/L aumenta la viabilidad de explantes.
![alt text](prueba.png)
