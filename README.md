# face-recognition

Para utilizar face-recognition se requiere:
 
 1. Cmake instalado via ```sudo apt install cmake```
 2. Python 3
 3. face-recognition instalado via ```pip3 install face-recognition```
 4. imutils instalado via ```pip3 install impiputils```
 5. opencv instalado via ```pip3 install opencv-python```

Procedimiento:
1. Crear una carpeta con el nombre de la persona cuyo rostro van a reconocer en la carpeta ```database```  
2. Sustituir su nombre en la linea 3 de ```headshots.py```
3. Ejecutar ```headshots.py``` y sacar las fotos que hagan falta para entrenar el modelo
4. Entrenar el modelo ejecutando ```train_model.py```
5. Al ejecutar ```facial_recognition.py``` se abrira una camara en la cual se va a detectar los rostros de aquellos que se encuentren en la base de datos
