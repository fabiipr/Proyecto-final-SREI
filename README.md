# Proyecto-final-SREI

Instalación del servidor web apache. Usaremos dos dominios mediante el archivo hosts: 
centro.intranet y departamentos.centro.intranet. El primero servirá el contenido mediante wordpress y el segundo mediante una aplicación en python 
lo primero que todo haremos un (apt update) y (apt update) para actualizar, una vez actualizado todo procedemos a instalar Apache 

![1](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/4e29ac21-9879-4ae0-808c-99a8a32bff8b)

![2](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/465d0529-9708-4273-ba98-3cfd4e2eef76)

Crearemos los directorios "centro.intranet" y "departamentos.centro.intranet"con el comando mkdir 
![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/584a4562-a542-4377-bc59-9ed3f10edc9d)

nos movemos dentro de centro.intranet y creamos el archivo index.html 

![creamos la pagina index html](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/70911d66-927c-4231-a0eb-4f693f42b704)

y luego editaremos el archivo que hemos creado, tanto centro.intranet como de departamentos.centro.intra

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/2b878223-ee7c-48c6-b88b-b74778a26e00)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/f594c26b-80da-4f63-87fe-a5636c2bf064)

usaremos centro.intranet.conf para entrar en la configuración 

![entramos en centro intranet conf](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/48dd9717-0223-4022-97e6-a0fbd6c34773)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/b05cfcc9-4e7c-416e-ac73-411db2eecb88)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/16b01c59-17f1-435e-8bfc-cb7f093bebb3)

entramos en el archivo host y lo modificamos 
![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/180cd7e6-1d9c-491f-8e52-325f92d3693b)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/dbe67488-00f0-4851-bec7-711833986d15)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/df2ca30e-909d-475d-aae2-637bf021e36f)

activamos los nodulos necearios para ejecutar el rograma de php y acceder a mysql 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/64323203-1469-4475-9cc9-0651f3985a0e)

con el comando mysql entraríamos en él 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/98df4859-0ab1-4fe9-9bc4-5efa2e752c62)

ponemos el comando php libapache2-mod -php php-mysql para descargarlo 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/6a723ffc-9e95-449b-8f37-e8e60fd4175a)

php -v y vemos la versión instalada 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/ace3f6c3-c8a4-49db-8b67-6151c6ea8f29)

a continuación instalamos y configuraremos WordPress

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/4dad06ad-83f0-4c62-aae9-15adc5e361ad)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/1f001d3c-b426-4033-9f47-736f01a718da)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/fc63748f-c4a3-42a5-aec8-c4aa972f2ef2)

le damos permisos a la carpeta de wordpress con wl comando chmod -R 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/813d0b95-5a8b-4497-98b9-829f0ec78125)

y ahora crearemos la base de datos 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/4f82a9d1-1657-42a0-9d18-2487c2a4aa20)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/d0f2719d-285b-40a7-9398-73a005eb3b81)

![creamos usuario](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/d511d3b4-06bf-422f-8cff-d501eba9192a)

comando FLUSH PRIVILEGE 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/12c582c3-e0c2-4123-8471-c0a44271e2f1)

exit

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/336d91e8-fb97-4742-bc84-ea565d5ba331)

copiamos el wp.config-sample.php en el wp-config.php

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/487a151d-a3f6-4dc1-9473-0e70b60c6786)

y modificamos el wp-config.php

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/83efea63-7ac4-43c0-9ae9-e4ad6fa40e64)

![edicion database](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/3368532a-9646-425a-be33-387936a34fdc)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/1c62e2bc-c037-4128-9fc5-439be83868c3)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/39663fb1-f750-4895-bcb6-81192b5262d2)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/303e511c-2500-46e1-a5ba-ef584c790fc4)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/e5af1ae7-d41b-463f-b669-52ee48805a29)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/b3719eb5-a2ee-4b21-861a-a02ee484e93d)

![install wordpress](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/333f3ee9-ae59-4a87-94c5-2f50cad90132)

![login wordpress](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/e0dc2745-477c-4e97-83a6-444ab927267a)

![dashboard wprdpress](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/f87fd476-13cf-4a25-8f26-3b1ca1ce17c2)


![dashboard wprdpress](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/5ec75726-790a-4e23-a2d5-24e27586ed98)

Activamos el módulo'wsdgi' para permitir ejecutar Python 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/d0b5ffa1-f686-4ea7-92a4-ed10f1bb2ac4)

Creamos las carpetas curso-python/trunk/python-web 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/c9f4ba71-9810-4e1c-96a2-f04215d0302f)

creamos los mismo y public.html  dentro de departamentos.centro.intranet

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/931d9e5f-f9cb-4164-bb32-4da9e194bf48)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/cf65b36d-7a0f-4692-b640-d3cdad2cc09c)

![controller py](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/38ea2db1-fbd7-4c71-9e19-f7fcb67787f0)

codigo de pythpn 

![codigo del controller py](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/d7008651-86ad-42fc-8ee9-576ab9b3c7f8)

nos meteremos en la configuración de departamentos.centro.intranet 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/9a56d136-1e21-4ae8-b9a2-b58a60a35a9f)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/75c89d69-57c7-447e-bed2-6dee87cb8c79)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/fbd32770-dc18-4f2a-ac4d-9cb237a08e14)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/07811ed3-5da8-4e78-9eee-63ad29ba6af4)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/5c5b91a5-7b0f-4b4e-8f31-4a4c0d6df50b)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/aed5c5ac-5ebf-4a82-890f-e7d516246c4b)

/etc/hosts 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/1a5940de-5a9d-4e99-91f4-70b97e90558f)

vemos la pagina de Python 

![vista depagina python](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/a2c75221-d209-43e6-a924-e89dc6338945)

Ahora protegeremos el acceso a la aplicación de Python 

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/1ad43445-d9e2-46ce-8234-bdc54fcf3287)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/d203bf71-e5cd-4d65-b95f-b009166f2764)

![image](https://github.com/fabiipr/Proyecto-final-SREI/assets/91718499/b625adc8-ccda-48ec-97a5-4f5112fcca9e)
