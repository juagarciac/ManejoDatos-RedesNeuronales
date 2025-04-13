# Trabajo02 - Juan Pablo Garcia Carballo

## Miembros
- Juan Pablo Garcia Carballo

## Descripción del Proyecto
Este proyecto consiste en el desarrollo de una red neuronal que pueda predecir la posibilidad de no pagar una deuda contraída a partir de la siguiente [base de datos](https://www.kaggle.com/datasets/ranadeep/credit-risk-dataset/data). El objetivo principal es probar la capacidad para analizar bases de datos para creación de productos de predicción y crear redes neuronales con tensor Flow.

## Tecnologías Utilizadas
- Python utilizando las librerías Panda, matplotlib y seaborn para graficar la distribución de los datos
- Tensor Flow para realizar la red neuronal

## Utilizar la red neuronal
Se podrá utilizar la red neuronal entrenada utilizando el modelo llamado best_model.h5 y scaler.joblib, utilizando el código añadido en archivo UsoRedNeuronal.ipynb

## Desafíos y Soluciones
Los principales problemas fueron la gran cantidad de datos que no eran representativos para la predicción objetivo, siendo necesario un registro en cada variable para ver su utilidad, además del gran desbalance que tienen los datos para la clase de los prestamos no pagados.

Para solucionar estos problemas fue necesario utilizar ia para revisar la utilidad de manera rápida y hacer una revisión manual, para el desbalance se utilizaron múltiples técnicas, la primera disminuir la clase mayoritaria utilizando tomek link para mejorar la separación entre las dos clases, aumentar los ejemplos de la clase mayoritaria utilizando Smote para tener ejemplos representativos y por último se tomó en cuenta la diferencia para el entrenamiento de la red neuronal.

Por último, para aumentar el rendimiento se utilizó un script que evalúa en un rango de distintas configuraciones de redes neuronales para ver cuál fue la más eficaz.

## Contacto
Juan Pablo Garcia Carballo 
[Linkedin](https://www.linkedin.com/in/juan-pablo-garcia-carballo/)

[Github](https://github.com/juagarciac)  [Correo](mailto:juanpablogarciacarballo@gmail.com)
