
<img src="power.png">

Nintendo 3DS Kit es un script construido a partir de GodMode9, el explorador avanzado de Nintendo 3DS que se ejecuta a través de un payload por Arm9LoaderHax, SigHax o NtrBootHax. 

Al igual que GodMode9, los requisitos para construir este script son: <br/>
-Python 3.8.5 y Pip3 (ambos en el $PATH y accesibles)<br/>
-FirmTool (Tambien debe estar en el $PATH)<br/>
-devkitARM (es un paquete que forma parte de devkitpro-Pacman, debe estar tambien en el $PATH) <br/>
export DEVKITARM=/opt/devkitpro/devkitARM<br/>
-arm-none-eabi-gcc, cmake y curl (de los que depende devkitpro y GodMode9)

La mejor forma de compilar el script es usando git, descargar este repositorio con <br/>
git clone https://github.com/daviiid99/Nintendo-3DS-Kit.git

Para descargar git, puedes hacerlo con sudo apt-get install git (en Linux)
<br/> <br/>

Una vez descargado el repositorio y descomprimido su contenido, abre un ventana de terminal en la raíz del directorio y construye el script con <br/>
make SCRIPT_RUNNER=1 <br/> El script compilado se encontrará en la ruta /output.
