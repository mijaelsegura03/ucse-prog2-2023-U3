## Como iniciar
Primero, abrimos un cmd/Powershell y nos dirigimos a la carpeta raíz de ambas aplicaciones, donde se encuentra el archivo docker-compose.yml
<br><br>
Segundo, ejecutamos el comando docker-compose up --build

## App1
Prueba con la siguiente URL: http://localhost:4000/tz?zone=America/New_York
<br> <br>
![image](https://github.com/user-attachments/assets/753d4535-e7fe-4df6-ba16-f85e32700f68)
<br><br>
Otra prueba: http://localhost:4000/tz?zone=Europe/Madrid
<br><br>
![image](https://github.com/user-attachments/assets/01802799-bf0b-43e7-a656-1e8fc5fbc053)

## App2
Prueba con la siguiente URL: http://localhost:4001/checker?url=app1&zone=America/New_York
<br> <br>
![image](https://github.com/user-attachments/assets/ea6df178-b1ee-4316-b6c7-c7f75ee98d16)




