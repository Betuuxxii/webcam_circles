# webcam_circleis
Circle detection from online webcam images

# Exercise 1.4. Circle detection

In the Git repository  https://github.com/beta-robots/webcam_circles

1. Fork it
2. Build the circle_detector example. (mkdir build & cd build & cmake .. & make)
3. Play with it
4. Find out information about how The Hough Transform works, and interpret and explain  the behaviour when changing the parameters. 


# Hough Line Transform

Hough Line Transform és un algoritme que detecta línies rectes en una imatge. 

### Com funciona?
L'equació d'una recta es pot escriure de la següent manera: 

$$y = (\frac{cosO}{sinO})x + \frac{r}{sinO}$$

Si per una {xo, yo} representem la familia de línies obtenim una senyal sinusoïdal. 
Hough Line Transform, fa el mateix per tots els punts d'una imatge.

Si trobem dues senyals diferents que coincideixen en el mateix punt, vol dir que aquests dos punts es troben en la mateixa línia. 

Això significa que, en general, una línia pot ser detectada trobant el número de interseccions entre les corbes. 

El que fa Hough Line Transform, és calcular les transaccions entre totes les corbes per a cada pixel de la imatge.


Bibliografia: 
OpenCV, Hough Line Transform <https://docs.opencv.org/2.4/doc/tutorials/imgproc/imgtrans/hough_lines/hough_lines.html>



