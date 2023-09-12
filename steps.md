# Pasos para enlazar el proyecto local con GitHub por medio de Git
1. Abrimos Git e inicializamos con ```git init```
   
   <img width="367" alt="image" src="https://github.com/CarlosGiles/python-pip/assets/92232878/9e44db9d-63bd-4ee1-aae4-5fb68e48b310">
   
2. Enlazamos el repositorio deseado por medio de la linea de código ```git remote add origin https://github.com/CarlosGiles/python-pip.git```

   <img width="392" alt="image" src="https://github.com/CarlosGiles/python-pip/assets/92232878/d2349ac8-b168-4703-bd0c-e3f83f554c30">

3. Verificamos la conexión con el comando ```git remote -v```

   <img width="343" alt="image" src="https://github.com/CarlosGiles/python-pip/assets/92232878/41821d30-49a7-4137-900e-74803a27f84f">

4. Aunque tenemos enlazado el repositorio, debemos guardar y agregar mensaje de los cambios manualmente. Guardamos todo con ```git add *``` y enviamos con ```git commit -m "Enviando cambio"```

   <img width="302" alt="image" src="https://github.com/CarlosGiles/python-pip/assets/92232878/51f795ce-879a-4a64-b20e-f63906fdf537">
   
   <img width="307" alt="image" src="https://github.com/CarlosGiles/python-pip/assets/92232878/2c290338-ea04-4ef1-933d-9705c0b31b73">

5. Enviamos el cambio con ```git push origin master```

   <img width="303" alt="image" src="https://github.com/CarlosGiles/python-pip/assets/92232878/5200343d-3f7c-4ce1-9427-bb19a669313b">

La siguiente imaagen muestra el proceso completo:

<img width="400" alt="image" src="https://github.com/CarlosGiles/python-pip/assets/92232878/b483f3f9-5937-4cfd-84f8-18125a1146c4">

Lo que se hizo en la última imágen:

* Creamos el archivo **hello.py** con ```touch hello.py```
* Inicializamos la branch con ```git init```
* Guardamos los cambios con ```git add hello.py``` o ```git add *```
* Agregamos un mensaje para describir el cambio ```git commit -m "Subiendo hello.py"```
* Creamos la conexión con el repositorio en específico con ```git remote add origin https://github.com/CarlosGiles/python-pip.git```
* Verificamos la conexión con ```git remote -v```
* Mandamos el cambio con ```git push origin master```
  
Si vamos al repositorio veremos que tenemos el cambio para comparar y aceptar:

<img width="670" alt="image" src="https://github.com/CarlosGiles/python-pip/assets/92232878/117b332e-c916-4047-9e01-78b480945109">

Si fuese un cambio y no la creación del archivo, podríamos ver la comparación del antes y el después:

<img width="907" alt="image" src="https://github.com/CarlosGiles/python-pip/assets/92232878/9619d3b1-2945-49e7-bf45-41ee4c372da3">
