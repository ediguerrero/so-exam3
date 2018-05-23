# so-exam3

**Universidad Icesi**  
**Curso:** Sistemas Operativos  
**Estudiante:** edisson guerrero londoño    
**Codigo:**  A00328068  
**Correo:**  edixon_guerrero96@hotmail.com  
**Repositorio:**  https://github.com/ediguerrero/so-exam3.git

### punto 3:

se hacen dos archivos llamados requirements.txt y requirements_dev.txt dentro del repositorio para implementar el servicio web Flask.  

- Se crea un programa en python la cual contiene los metodos para saber el consumo de CPU, la memoria disponible y
el espacio en disco libre.   


![](imagenes/vistats.PNG)

Se crea un archivo app.py con el cual se presta el servicio web flask 


![](imagenes/viapp.PNG)


 Se ejecuta el servicio  

 ![](imagenes/apprun.PNG)
 
 
  
 Se realizan peticiones usando la aplicación **Postman:**
 
 ## Servicio cpu_info : muestra el porcentaje de consumo de CPU
 
   ![](imagenes/cpu.PNG) 

## Servicio available_memory: muestra la cantidad de memoria ram disponible en MB

  ![](imagenes/memory.PNG) 
  
## Servicio disk_space: Muestra la cantidad de espacio del disco disponible en MB

  ![](imagenes/disk.PNG) 
  
  
## punto 4:

para probar el servicio se crea un archivo llamado test_stats.py

![](imagenes/vitestepy.PNG) 

Se ejecutan las pruebas usando el comando de py.test -v

![](imagenes/tests.PNG) 



## Punto 5:

para la integración continua se crea un archivo tox.ini en el cual se especifica, la libreria pra pruebas
el lenguaje base, el cual es python3 y por ultimo se especifica las dependencias que se van a usar
y el comando para realizar las pruebas: 

![](imagenes/vitox.PNG) 

se ejecutan las pruebas:  

![](imagenes/tox.PNG)

Por ultimo crea un archivo **.travis.yml**, es cual guarda la configuracion basica para correr las 
pruebas realizadas por travis-ci.org, aqui se especifica el lenguaje , si se quieren recibir notificaciones por correo, version de
python y las dependencias

![](imagenes/vitravis.PNG)

por ultimo vemos las pruebas pasar sin problemas

![](imagenes/1.jpg)

![](imagenes/w2.jpg)

![](imagenes/l3.jpg)




