# Práctico 12

## 1- Configurando Heroku

![image](./Imagenes/Heroku1.png)

![image](./Imagenes/Heroku2.png)

## 2- Creando y Desplegando la aplicación Payroll
heroku container:release web --app=stormy-fjord-53254

![image](./Imagenes/BuildHeroku.png)

Una vez terminada la operación, procedemos a desplegar la aplicación
![image](./Imagenes/ReleaseHeroku.png)

Con esto vemos que está retornando el mensaje esperado.
![image](./Imagenes/RunApp.png)

## 3- Integrar el despliegue en Jenkins