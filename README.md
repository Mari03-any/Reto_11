# Reto_11
---
1. Métodos de strings en python: 
- **endswith** <br>
  Evalua si la cadena acaba con una subcadena:
   ```python
  "Hola mundo".endswith('mundo')
  #True
   ```
- **startswith** <br>
  Evalua si la cadena empieza con una subcadena:
  ```python
  "Hola mundo".startswith("Mola")
  #False
   ``` 
- **isalpha** <br>
  Devuelve True si la cadena es todo carácteres alfabéticos:
  ```python
  c = "ABC10034po"
  c.isalpha()
  #False
   ``` 
- **isalnum** <br>
  Devuelve True si la cadena es todo números o carácteres alfabéticos:
  ```python
  c = "ABC10034po"
  c.isalnum()
  #True
   ```
- **isdigit** <br>
  Evalua si la cadena propuesta es todo números (False or True):
  ```python
  c = "100"
  c.isdigit()
  #True
   ```  
- **isspace** <br>
  Devuelve True si la cadena es todo espacios:
  ```python
  "  -  ".isspace()
  #False
   ```  
- **istitle** <br>
  Evalua si la primera letra de cada palabra es mayúscula, si es así devuelve True:
  ```python
  "Hola Mundo".istitle()
  #True
   ```  
- **islower** <br>
  Devuelve True si la cadena es todo minúsculas:
  ```python
  "Hola mundo".islower()
  #False
   ```  
- **isupper** <br>
  Evalua si la cadena es todo mayúsculas:
  ```python
  "Hola mundo".isupper()
  #False
   ```  
Tomado de: Métodos de las cadenas | curso de python | hektor profe. (s. f.). Recuperado 23 de febrero de 2025, de https://docs.hektorprofe.net/python/metodos-de-las-colecciones/metodos-de-las-cadenas/ <br>

2. Procesar el archivo y extraer:

- Cantidad de vocales
- Cantidad de consonantes
- Listado de las 50 palabras que más se repiten
