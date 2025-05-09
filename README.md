# Para instalar

**Necesitamos:**

 1. Python 3.11.4 (tildar agregar path y custom install)
 2. pip install cmake
 3. instalar dlib desde: https://www.youtube.com/watch?v=m6VHlvh4dTE
 4. bajar de https://github.com/z-mahmud22/Dlib_Windows_Python3.x
 5. En la barra de dirección de la carpeta donde tengais el archivo, escribid cmd, para que os abra la terminal en esa dirección. En la terminal escribimos pip install dlib-19.24.99-cp312-cp312-win_amd64.whl
 6. pip install opencv-python
 7. pip install pyserial
 8. pip install face-recognition
**

## Importante
OpenCV instala la version 2.xx de numpy necesitamos hacer un downgrade de la siguiente manera

 1. pip uninstall -y numpy
 2. pip install numpy==1.23.5