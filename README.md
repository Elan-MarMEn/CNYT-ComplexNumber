# CNYT-ComplexNumber
## Description
```
Este programa simula las propiedades y operaciones basicas que
se aplican a los numeros complejos haciendo uso una clase del mismo nombre, cada funcion se describe acontinuacion:
1. Suma
2. Producto
3. Resta
4. División
5. Módulo
6. Conjugado
7. Conversión entre representaciones polar y cartesiano
8. Retornar la fase de un número complejo.
```
1.Suma:
  - Se recive un numero complejo como argumento que se suma con el complejo deseado(No retorna nada):
  ```
  ComplexNumber c= new ComplexNumber(12,14);
  ComplexNumber c2= new ComplexNumber(26,34);
  
  c2.add(c);
  ```
2.Producto:
  - Se recive un numero complejo como argumento que opera con los atributos del segundo complejo(No retorna nada):
  ```
  c.multiply(c2);
  
  ```
3.Resta:
  - Opera de la misma manera que la suma solo que cambiando el signo del argumento(No retorna nada):
  ```
  c2.rest(c);
  ```
4.División:
  - Se recive un numero complejo como argumento que realiza las operaciones necesarias con los atributos del segundo complejo(No retorna nada):
  ```
  c.div(c2);
  
  ```
5.Módulo:
  - No recive ningun argumento y retorna el modulo del numero deseado:
  ```
  c.modull()
  
  ```
6.Conjugado:
  - No recive ningun argumento y cambia el signo del atributo imginario(No retorna nada):
  ```
  c.conjugate();
  
  ```
7.Conversión polar y cartesiana:
  - No recive ningun argumento y haciendo uso del modulo y la fase se encarga de convertir el numero de cartesiano a polar o de polar a cartesiano (No retorna nada):
  ```
  c.to_polar();
  
  c.to_cartesian();
  ```
  
8.Retornar la fase:
  - No recive ningun argumento y retorna el fase del numero deseado:
  ```
  c.phase();
  ```
* NOTA: *Este programa se encuentra escrito en lenguaje JAVA, haciendo uso de la herramienta IntelliJ, por lo tanto en caso de no llegar a compilar este programa en algun otro editor se recomienda instalar IntelliJ Comunity*
