# Challenge2_WWC_ML
Reto 2 :computer: Women Who Code :computer:

# Linea Python y DS
## Reto: Diccionarios y Dataframes
### Descripción:
Cuando estamos trabajando con datos existen 2 estructuras de datos que se convierten de mucha utilidad en nuestro día a
día. Estan son: diccionarios y dataframes.
Los diccionarios nos permiten almacenar datos en un formato clave valor, por ejemplo:
```python
mi_diccionario = {'estudiantes': 12, 'profesionales': 40, 'pensionados': 5}
```
Y los datasets son estructuras de datos que nos permiten representar nuestra informacion como tablas:

|   | categoria     | cantidad |
|---|---------------|----------|
| 0 | estudiantes   | 12       |
| 1 | profesionales | 40       |
| 2 | pensionados   | 5        |

y hacer uso de funciones especificas para este tipo de datos que nos permiten hacer cambios en nuestros datos de forma facil.

### Objetivo:
Completar la función `generar_dataframe_palabras` para que dado un texto genere un diccionario que nos indique cuantas
veces se repite cada palabra. El diccionario resultante debe lucir de la siguiente manera:
````python
results = {
    'puedo': 2,
    'noche': 1,
    'y': 5,
    ...
}
````
Una vez logremos saber cuantas ocurrecias hay en el texto de cada palabra la idea es usar este diccionario para convertirlo
en un Dataframe usando la libreria **pandas**. Aun no vamos a hacer cambios con el dataframe, solo lo queremos generar
para trabajar facilmente con el.

##### Input: 
Una cadena de texto

#### Output:
Un Dataframe construido desde un diccionario que contiene cada palabra con sus respectivas repeticiones.


### Preparacion entorno:
Antes de comenzar con el reto es importante que instalemos las librerías que vamos a usar. Para esto haremos uso del 
siguiente comando:
```shell script
$ pip install -r requirements.txt
```


### Comprobar resultados:
Para comprobar los resultados puedes ejecutar el script main.py usando:
```shell script
$ python main.py
```
Y deberías de ver los siguiente:
```shell script
Excelente, has convertido un poema en un Dataframe para trabajar con el!
```
