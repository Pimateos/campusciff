# Ejercios GitHub 
## Patricia Iglesias Mateos

## 2.1 REPOSITORIO
**1. Crear un repositorio en vuestro GitHub llamado campusciff**
    git config --global user.email "pimateos@yahoo.com"
    git config --global user.name "pimateos"
    mkdir campusciff_practica
    cd campusciff_practica
    git init


![crear_repositorio_github](creacion_repositorio.png)

##2.2 REPOSITORIO CAMPUSCIFF(II)
**2. Clonar vuestro repositorio en local**

    git clone git@github.com:Pimateos/campusciff_practica.git
![clonar repositorio](git_clone_remoto_local.png)


##2.3 README
**3.Crear (si no lo habéis creado ya) en vuestro
repositorio local un documento README.md.**
> Notas: en este documento tendreís
que ir poniendo los comandos que
habéis tenido que utilizar durante
todos los ejercicios y las
explicaciones y capturas de
pantalla que consideréis
necesarias.

##2.4 COMMIT INICIAL
**1.Añadir al README.md los comandos utilizados hasta ahora y hacer un commit inicial con el mensaje commit inicial**

Ver imagen inicial


##2.5 PUSH INICIAL
**1.Subir los cambios al repositorio remoto**

Ver los pasos anteriores

##2.6 IGNORAR ARCHIVOS(I)
**1.Crear en el repositorio local un fichero llamado privado.txt**

    touch privado.txt
**2.Crear en el repositorio local una carpeta llamada privada**
    mkdir privada

##2.7 IGNORAR ARCHIVOS(II)
**1.Realizar los cambios oportunos para que tanto el archivo como la carpeta sean ignorados por git**

    vi .gitignore

He añadido privado.txt y privada en otra linea
Despues he sincronizado y no aparecen.

##2.8 AÑADIR FICHERO 1.TXT
**1.Añadir fichero 1.txt al repositorio local**
    touch 1.txt
    git add .
	git commit -m "1.txt añadido"
	git push

##2.9 CREAR EL TAG V0.1
**1.Crear un tag v0.1**
    git tag -a v0.1 -m "Crear el tag v0.1"

##2.10 SUBIR EL TAG V0.1
**1.Subir los cambios al repositorio remoto**
    git push --tag origin master
![Etiqueta](etiquetas.png)

