1. Como primer paso es necesario acceder a la página de Terraform

```URL de Terraform para descargar
https://developer.hashicorp.com/terraform/install
```
2. A continuación seleccionamos el SO, y descargamos el archivo, en este caso es windows

<img width="1267" height="291" alt="Captura de pantalla 2025-10-29 172009" src="https://github.com/user-attachments/assets/9a3bf12b-e8e3-41b4-bf2f-b7eaea41c2ce" />

3. Descomprimir el Archivo Una vez descargado el archivo comprimido (normalmente en formato .zip), es necesario descomprimirlo. Al hacerlo, obtendrás un único archivo ejecutable: terraform.exe.

4. Crear Carpeta de Destino Crea una carpeta dedicada para Terraform en una ubicación permanente de tu disco local. Se recomienda usar una ruta simple y fácil de recordar, por ejemplo: C:\terraform o D:\terraform.

5. Mover el Ejecutable Mueve el archivo terraform.exe que descomprimiste a la nueva carpeta que creaste (ej. D:\terraform).

6. Añadir Terraform al PATH del Sistema (Paso Crítico) Para que la terminal de Windows (CMD, PowerShell, etc.) pueda reconocer el comando terraform desde cualquier ubicación, debes agregar la ruta de tu carpeta a las Variables de Entorno del sistema:

7. En el menú de inicio, busca y abre "Editar las variables de entorno del sistema".

<img width="307" height="430" alt="image" src="https://github.com/user-attachments/assets/695e0a7e-619e-47a1-a316-c6136a8e2343" />

8. En la ventana que aparece, haz clic en el botón "Variables de entorno...".

9. En la sección "Variables del sistema", busca y selecciona la variable llamada Path.

10. Haz clic en "Editar...".

11. Haz clic en "Nuevo" y pega la ruta completa de la carpeta donde guardaste el .exe (ejemplo: D:\terraform).

12. Presiona "Aceptar" en todas las ventanas para guardar los cambios.

13. Verificar la Instalación Cierra cualquier ventana de terminal que tengas abierta y abre una nueva. Escribe el siguiente comando para confirmar que Windows ahora reconoce Terraform:
```Verificación de Instalación
terraform -v
```
14. Si la instalación fue exitosa, verás la versión de Terraform que instalaste.

<img width="1340" height="156" alt="image" src="https://github.com/user-attachments/assets/dbcdcb8e-296b-4e23-b44d-2fbe7bd2cff8" />

15. Lo siguiente es instalar Visual Studio Code desde el siguiente enlace
```URL de VSC
https://code.visualstudio.com/
```
16. Una vez descargado lo instalamos
17. Terminada la instalación debemos de instalar la extención de HashiCorp Terraform, como se muestra en la imagen de abajo

<img width="1623" height="301" alt="image" src="https://github.com/user-attachments/assets/bb39f756-4926-4449-965e-dcfa351dc26e" />

Una vez instalado realizamos lo siguiente:

1. Creamos una carpeta global, donde dentro crearemos las diferentes carpetas donde guardaremos los diferentes proyectos que realicemos con terraform
2. Dentro de Visual Studio Code abrimos la carpeta donde guardaremos el proyecto de terraform
3. Una vez dentro de la carpeta creamos un archivo de extención .tf

Una vez creado el archvivo .tf, y que se aya reconocido la extención del archvio con la aparición del icono de terraform a lado del nombre, la instalación del interprete de terraform ha sido exitosa.

<img width="432" height="97" alt="image" src="https://github.com/user-attachments/assets/70ba1eca-9123-4043-b4fd-e65bce814530" />
