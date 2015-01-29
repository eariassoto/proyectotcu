# Lista de Materiales #
https://docs.google.com/document/d/1NKidaqosijoujj6fp2B99qCqkjTao7hXGNjHMD-J_-o/edit?usp=sharing


# Sobre hardware #
http://www.instructables.com/id/The-EyeWriter-20/?ALLSTEPS Versión 2
Nota: en esta pagina esta el diseño de una montura en madera que ellos hicieron, talvez la podamos modelar para la impresora


# Sobre el software #
Importante: Ubicar la carpeta de este repositorio en C:, osea tiene que quedar C:\proyectotcu de lo contrario no reconoce librerías

## Versión 2 ##
Para **correr el programa** ubicar el folder C:\proyectotcu\of\of61\apps\eyewriter-eyewriter-4c1fb73\eyewritertracker\bin el archivo RemoteEyeTracker.exe y ejecutarlo

Para **compilar el programa** usar esta versión de Code blocks 10.05 https://mega.co.nz/#!www0lIoD!BoiPElDJ7RJQFbDAjorlxjf4YmMVjHVz_ee817kog_8 y abrir con ella el archivo RemoteEyeTracker.workspace en la carpeta C:\proyectotcu\of\of61\apps\eyewriter-eyewriter-4c1fb73\eyewritertracker ya con esto se puede construir el proyecto.

Para **cambiar la entrada** entre video (de ejemplo) y entrada de cámara web o para utilizar la **simulacion del mouse** ubicar la carpeta C:\proyectotcu\of\of61\apps\eyewriter-eyewriter-4c1fb73\eyewritertracker\bin\data\Settings y modificar el archivo inputSettings.xml 

## Notas ##
**Importante**: se tiene que instalar el reproductor Quicktime https://www.apple.com/es/quicktime/download/ y copiar el archivo QTFC.dll (esta en el repo) en la carpeta C:\Windows\System32 porque el eyewriter usa librerías de este programa para reproducir video.

## Enlaces ##
http://www.eyewriter.org/ Página del proyecto

https://github.com/eyewriter Repositorio código fuente

http://openframeworks.cc/ Librería

http://www.apple.com/es/quicktime/download/thankyou/index.html Quicktime
