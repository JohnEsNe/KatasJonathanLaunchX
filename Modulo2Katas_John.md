
C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X>python -m venv env

C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: DAEE-F9EA

 Directorio de C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X

09/02/2022  11:48 p. m.    <DIR>          .
09/02/2022  11:48 p. m.    <DIR>          ..
09/02/2022  11:37 p. m.           224,961 3. CursoIntroPython_Módulo 2 - Crear y administrar proyectos.md at main · LaunchX-InnovaccionVirtual_CursoIntroPython.pdf
09/02/2022  11:31 p. m.    <DIR>          Crear y Adminstrar proyectos
09/02/2022  11:48 p. m.    <DIR>          env
01/02/2022  07:47 p. m.         1,251,244 LAUNCH X _ CAPÍTULO MÉXICO.pdf
09/02/2022  05:21 p. m.             6,355 Primeros pasos.ipynb
01/02/2022  07:48 p. m.         1,535,388 Registro Launch X.pdf
07/02/2022  11:06 p. m.             7,359 ship-manual.ipynb
               5 archivos      3,025,307 bytes
               4 dirs  750,107,398,144 bytes libres

C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X>cd env

C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X\env>dir
 El volumen de la unidad C es Windows
 El número de serie del volumen es: DAEE-F9EA

 Directorio de C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X\env

09/02/2022  11:48 p. m.    <DIR>          .
09/02/2022  11:48 p. m.    <DIR>          ..
09/02/2022  11:48 p. m.    <DIR>          Include
09/02/2022  11:48 p. m.    <DIR>          Lib
09/02/2022  11:48 p. m.               166 pyvenv.cfg
09/02/2022  11:49 p. m.    <DIR>          Scripts
               1 archivos            166 bytes
               5 dirs  750,107,332,608 bytes libres

C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X\env>cd ..

C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X> env\Scripts\activate.bat

(env) C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X>pip freeze

(env) C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X>pip install python-dateutil
Collecting python-dateutil
  Using cached python_dateutil-2.8.2-py2.py3-none-any.whl (247 kB)
Collecting six>=1.5
  Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
Installing collected packages: six, python-dateutil
Successfully installed python-dateutil-2.8.2 six-1.16.0
WARNING: You are using pip version 21.2.4; however, version 22.0.3 is available.
You should consider upgrading via the 'C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X\env\Scripts\python.exe -m pip install --upgrade pip' command.

(env) C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X>pip freeze
python-dateutil==2.8.2
six==1.16.0

(env) C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X>deactivate
C:\Users\john1\Documents\Jonathan\Cursos\Microsoft Launch X>