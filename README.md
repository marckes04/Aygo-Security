# Aygo-Security

1. Codigo para correr la aplicacion Web de prueba con hola mundo en su respectivo puerto 5000
![image](https://user-images.githubusercontent.com/71477601/142749270-ec07f0e3-0db7-4a72-a4f6-a87cc8b3a507.png)
2. Por medio de la maquina virtual se crea un certificado de seguridad propio en formato PKCS12
![image](https://user-images.githubusercontent.com/71477601/142749314-0971b615-336f-48b3-b750-9c6bf2099eb8.png)
3. Por medio de las siguientes siguientes imagenes se observa el contenido del certificado en el navegador
![image](https://user-images.githubusercontent.com/71477601/142749357-d836e60b-7c48-40e3-b186-e51829b9149f.png)
![image](https://user-images.githubusercontent.com/71477601/142749363-4d59fd52-a738-4261-96ce-b12b6a40fb9e.png)
4. Por medio del siguiente comando se crea otro certificado mytruestore para dar validez prioritaria sobre el certificado google por defecto.


![image](https://user-images.githubusercontent.com/71477601/142749448-1d6c9e7d-d045-41b2-ba94-bc0ed0e9331f.png)


5. Por medio de la linea señalada del codigo "SecureUrlRead" se puede escoger si da prioridad a mi certificado creado o al de google respectivamente,
   linea comentada para mi certificado, no comentada para el de google
   

![image](https://user-images.githubusercontent.com/71477601/142749649-f5fa66e6-07d6-42b1-8afd-aab901568c67.png)




6. Acontinuacion se verifica el resultado del paso anterior viendo su funcionalidad.

Cuando mi certificado tiene validez.

![image](https://user-images.githubusercontent.com/71477601/142749603-3aefb87a-10c1-479b-8bc4-3c092d682b4f.png)

Cuando el certificado de Google tiene ahora la validez

![image](https://user-images.githubusercontent.com/71477601/142749613-f1398942-a776-4288-ae6a-5412be64acc5.png)


Cuando se le da validez a un certificado, el otro no es reconocido como valido en el navegador. 


