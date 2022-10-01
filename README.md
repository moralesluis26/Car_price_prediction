# Car_price_prediction

**Nombre**: Luis David Morales Aguilar

**CC**: 1214746438

**Programa**: Ingeniería de materiales

**Enlace al dataset de Kaggle**:
https://www.kaggle.com/datasets/hellbuoy/car-price-prediction?select=CarPrice_Assignment.csv

## Datos

**Pasos para ejecutar el dataset en google Colab**:

- Ir Kaggle y entrar al perfil, luego seleccionar la opción ``Account``

- Bajar hasta la opción ``API`` y presionar ``Create New API Token`` esto provocará que se descargue un archivo llamado ``Kaggle.json``

- Dentro del google Colab, cargar el archivo ``Kaggle.json`` desde la carperta `Archivos`

- Posteriormente se ejecuta el siguiente bloque de código:
```
! pip install kaggle
! mkdir ~/.kaggle
cp kaggle.json ~/.kaggle/
! chmod 600 ~/.kaggle/kaggle.json
! kaggle datasets download hellbuoy/car-price-prediction
! unzip car-price-prediction.zip

import pandas as np
np.read_csv("CarPrice_Assignment.csv")

```

En este punto, se puede visualizar el dataset completo, y modificar según los requerimientos.


## Videos

Video de la segunda entrega: https://www.youtube.com/watch?v=5wVU5wUt4JQ

Video entrega final: https://youtu.be/dHOA3ZKtB6c

