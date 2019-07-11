

# Reconocimiento-facial-en-Python3-y-OpenCV


_En la actualidad la tecnologia representa un constante crecimiento en las diversas áreas de nuestras vidas, prácticamente todo aquello que solíamos hacer mediante un grupo de personas o herramienta física, se esta viendo reemplazada por un software o pieza de hardware cada vez mas potente, que "facilita" de cierta forma las tareas cotidianas._

_!_

- Este proyecto esta hecho en python 3.7.3 y opencv
- Se recomienda trabajar en un entorno Virtual. Mas imformacion https://medium.com/@m.monroyc22/configurar-entorno-virtual-python-a860e820aace En los requimientos le dejare los repositorios directos.
- Este programa esta compilado en una MacBook Pro (MacOs) no tendria problemas en GNU Linux.



## Requerimientos:

```
  $pip install opencv-python==3.4.2.16
  
  $pip install pillow

  $pip install numpy
  
  $pip install opencv-contrib-python==3.4.2.16
```



## Si tienen estos errores comunes tambien los tuve yo:

$ error 1

(xx) (base) MacBook-Pro-de-User:rec user$ python3 02.py
Traceback (most recent call last):
  File "02.py", line 11, in <module>
    recognizer = cv2.face.LBPHFaceRecognizer_create()
AttributeError: module 'cv2.cv2' has no attribute 'face'

solucion 1:

MacBook-Pro-de-User:rec user$ pip install opencv-contrib-python==3.4.2.16


$ error2 :

cuando no encuentra el archivo DS_

solucion 2:
borrar la carpeta o crear otra otra vez, denuevo puede causar conflicto: 
  -Data set y Trainer.
  
  
  
  
  
  # UNIVERSIDAD NACIONAL DE MOQUEGUA #
  







