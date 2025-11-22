# despr2_2_nginx
> Repositorio para desplegar una página con Nginx

## Tarea paso a paso
1. Creación de la Vm
    - Crear un clon de la mv
    ![clon mv](image.png)
    - Configuración la red
    ![configuracion red](image-1.png)
    -inicio de la mv y acceso por ssh al host
    ![inicio de la mv](image-2.png)
    ![acceso ssh](image-3.png)

2. Preparación del entorno
    - Arrancar vm y actualización de paquetes
    ![update y upgrade](image-4.png)
    - Intalación Nginx
    ![instalacion nginx](image-5.png)
    - Configuración del firewall para permitir tráfico HTTP y HTTPS:
    ![alt text](image-6.png)

3.Comprobación básica:
    + Comprobación que el servicio está activo:
    ![alt text](image-7.png)
    + Visualización de http://localhost:8082/
    ![alt text](image-8.png)
    
4. Desplegación del sitio de ejemplo:
    + Copiar archivos: 
    ![alt text](image-9.png)

5. Configurar bloque de servidor: 
    + Creación de la configuración:
    ![alt text](image-14.png)
    ![alt text](image-11.png)

6. Verificación final: 
    ![alt text](image-10.png)

## Problemas encontrados 
En esta tarea tuve varios problemas en el paso 4 (no estaban dentro del apartado de troubleshooting), ya que el ssh no me estaba funcionando y a priori todo lo tenía bien configurado (aunque creo que el error venía por aquí), traté de seguir la actividad desde la propia máquina virtual pero me seguía dando bastantes errores. Lo solucioné borrando la mv y volviendo a empezar ya que las opciones que encontraba en internet me estaban dando todavía más fallos. 
