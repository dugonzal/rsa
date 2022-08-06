# rsa

## Introduction

	 1. Un cliente (por ejemplo, un navegador) envía su clave pública al servidor y solicita algunos datos.
	 2. El servidor cifra los datos utilizando la clave pública del cliente y envía los datos cifrados.
	 3. El cliente recibe estos datos y los descifra con su clave privada.
   
 # uso de rsa
 	- primero debemos crear un entrono virtual para instalar los paquetese necesarios, si tienes instalado pip
	  puedes hacerlo con pip virtualenv, una vez echo esto, usamos el comando virtualenv venv,  para crear el entorno virtual
	  activamos el entorno virtual con: source venv/bin/activate intalamos requirements.txt con el comando pip install -r requirements.txt,
	  una vez echo, ya podemos ejecutar el programa con pyrhon3 rsa.py 
