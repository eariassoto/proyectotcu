# Sobre hardware #
http://www.instructables.com/id/The-EyeWriter/ Versión 1

http://www.instructables.com/id/The-EyeWriter-20/ Versión 2

# Sobre el software #
Importante: Ubicar la carpeta de este repositorio en C:, osea tiene que quedar C:\proyectotcu de lo contrario no reconoce librerías

## Versión 1 ##
Para **correr el programa** ubicar el folder C:\proyectotcu\of\of74\apps\eyewriter\eyewriter-1.0\bin el archivo eyewriter.exe y ejecutarlo

Para **compilar el programa** usar esta versión de Code blocks 12.11 https://mega.co.nz/#!o5J2nRBA!Cccq4t0M9NZ7OAGObBOyIzQB1ktw5Qqbg8WhDcsJB0k y abrir con ella el archivo eyewriter.workspace en la carpeta C:\proyectotcu\of\of74\apps\eyewriter\eyewriter-1.0 ya con esto se puede construir el proyecto.

Para **cambiar la entrada** entre video (de ejemplo) y entrada de cámara web ubicar la carpeta C:\proyectotcu\of\of74\apps\eyewriter\eyewriter-1.0\bin\data\settings y modificar el archivo globalSettings.xml 

## Versión 2 ##
Para **correr el programa** ubicar el folder C:\proyectotcu\of\of61\apps\eyewriter-eyewriter-4c1fb73\eyewritertracker\bin el archivo RemoteEyeTracker.exe y ejecutarlo

Para **compilar el programa** usar esta versión de Code blocks 10.05 https://mega.co.nz/#!www0lIoD!BoiPElDJ7RJQFbDAjorlxjf4YmMVjHVz_ee817kog_8 y abrir con ella el archivo RemoteEyeTracker.workspace en la carpeta C:\proyectotcu\of\of61\apps\eyewriter-eyewriter-4c1fb73\eyewritertracker ya con esto se puede construir el proyecto.

Para **cambiar la entrada** entre video (de ejemplo) y entrada de cámara web ubicar la carpeta C:\proyectotcu\of\of61\apps\eyewriter-eyewriter-4c1fb73\eyewritertracker\bin\data\Settings y modificar el archivo inputSettings.xml 

## Notas ##
**Importante**: se tiene que instalar el reproductor Quicktime https://www.apple.com/es/quicktime/download/ y copiar el archivo QTFC.dll (esta en el repo) en la carpeta C:\Windows\System32 porque el eyewriter usa librerías de este programa para reproducir video.

**Nota**: Como Code blocks es tan extraño al abrir una versión y luego abrir otra el segundo reconoce el compilador de la primera y por tanto no se puede compílar el proyecto, en caso de que esto pase, ir a Settings -> Compiler and debugger -> Toolchain executables y en Compiler's installation directory ubicar la carpeta MinGW correspondiente a la versión de Codeblocks.

## Enlaces ##
http://www.eyewriter.org/ Página del proyecto

https://github.com/eyewriter Repositorio código fuente

http://openframeworks.cc/ Librería
