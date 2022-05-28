# labBigData
# Lab 0
Para este laboratorio se creó un cluster EMR(Cree el cluster antes de que salieran los lineamientos por tanto mostraré el cluster final con su summary y los puertos) siguiendo los lineamientos propuestos por el Profe Edwin Montoya en los videos compartidos por el profesor Juan Carlos Montoya
![image](https://user-images.githubusercontent.com/73863024/170804209-33abe987-97ce-4f4a-bf32-d976e5dce150.png)

Hundimos el botón de clonar en la parte superior

![image](https://user-images.githubusercontent.com/73863024/170804336-453dd0fc-4a67-4b15-af62-a7060584e59c.png)

Le damos a NO incluir los pasos

Y la configuración queda así

![image](https://user-images.githubusercontent.com/73863024/170804466-0cf38f0d-bb84-4a52-8f46-270d48c7e246.png)

![image](https://user-images.githubusercontent.com/73863024/170804489-382af743-359d-4e59-880f-547ef676f526.png)

![image](https://user-images.githubusercontent.com/73863024/170804497-ff92a9ef-22ca-4840-9f87-76f7331a1792.png)

![image](https://user-images.githubusercontent.com/73863024/170804509-b7fde9c3-7e1a-4319-9926-72a0d31e08b9.png)

![image](https://user-images.githubusercontent.com/73863024/170804529-de4d7091-587c-40bd-8aaf-1728f2bebf63.png)

Editamos el grupo de seguridad e inclumos los puertos 8888,8890, 9443 y el 22 para el ssh si no está activo

### Esperamos que el cluster se levante
![image](https://user-images.githubusercontent.com/73863024/170804716-49ca1ff9-696f-4c29-9e05-64df1ed15b0a.png)

## Nota
Creo también el bucket para persistencia de datos
![image](https://user-images.githubusercontent.com/73863024/170804808-394dd745-ea94-4313-a4cb-a4ab78a03b55.png)

## Hue
![image](https://user-images.githubusercontent.com/73863024/170805177-bb6d33e2-5a4a-4dbb-863c-1f76edc44541.png)
## JupyterHub
![image](https://user-images.githubusercontent.com/73863024/170805224-f681d241-4700-412b-9f77-5d1430f12e34.png)
## Zeppelin
![image](https://user-images.githubusercontent.com/73863024/170805244-8105b754-3bfc-4c20-8670-9db14e714a63.png)
## SSH
![image](https://user-images.githubusercontent.com/73863024/170805141-27ca3468-6cd5-4f2f-9e1a-652a544d0208.png)

# Lab 1
![image](https://user-images.githubusercontent.com/73863024/170807426-6b7db931-8741-45e9-9235-f54c1d959487.png)
 
## S3 desde Hue
![image](https://user-images.githubusercontent.com/73863024/170807715-cd21eba7-4dc2-4396-808d-edef65e67c8f.png)
## Files locales desde Hue
![image](https://user-images.githubusercontent.com/73863024/170807914-75676119-4d40-4cd2-acce-72d6ff3c3f95.png)

## Creando usuario hadoop para datasets desde CLI
![image](https://user-images.githubusercontent.com/73863024/170808250-32e0105f-fa43-464e-aa25-d40e23755540.png)
### Correción
Usar chmod 777 en vez de 755
## Creamos directorio Datasets
![image](https://user-images.githubusercontent.com/73863024/170808500-d3eb1309-a349-4c59-94f3-e7b3ddcfbec0.png)
## Creación de carpetas
![image](https://user-images.githubusercontent.com/73863024/170808610-873e5521-236f-4d7e-9024-27f2a4fe1b65.png)
## ingresamos datos en el sistema de archivos local
![image](https://user-images.githubusercontent.com/73863024/170832571-a043dd6a-1898-49f7-9f95-d8adb47f7025.png)
Repetimos para todas las carpetas.
## insertando en s3 desde consola 
![image](https://user-images.githubusercontent.com/73863024/170832960-52108cb9-a1bb-4c70-a36e-3cbd2150d306.png)
## Por último hacemos el bucket publico
![image](https://user-images.githubusercontent.com/73863024/170833271-91d59e1a-8f7e-4e1a-98b5-1fab4e935215.png)

