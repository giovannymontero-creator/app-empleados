# Prueba Empleado

### Aplicacion 

Es una api restful que contiene el crear, actualizar, listar y eliminar un empleado comprendido
con un nombre y la funcion.

#### Funcionamiento en Angular

##### Listar Empleados
Se muestran el listado de empleados, en este momento solo existe uno que se deja inicial para
verificar que funciona correctamente.
![listar](https://user-images.githubusercontent.com/66186685/132244989-12b11e14-6c0d-4651-ab41-fbbd60b190bd.png)

##### Crear empleado
Se muestra para crear un empleado, con su nombre y funcion
![Crear](https://user-images.githubusercontent.com/66186685/132245292-f06ab2a8-8be2-49fe-93ee-f56c72f40d44.png)

##### Editar o actualizar empleado
Se muestra para actualizar un empleado, con su nombre y funcion cargados y listos para editar
![editar](https://user-images.githubusercontent.com/66186685/132245352-8acce9fa-7b52-4030-948e-3b4a19219ab2.png)

##### Eliminar empleado
Se muestra un botón para eliminar empleado y su respectiva confirmación
![Confirmareliminar](https://user-images.githubusercontent.com/66186685/132245369-ff229894-58f3-46cf-8793-2145ac3c7c8f.png)

## Notas importantes
Lastimosamente no he manejado docker para los proyectos, por lo tanto no se logro persistir la base
 de datos y se debe crear en MySql que es el motor escogido.

## Creación de base de datos
Unicamente se debe crear la base de datos con el nombre db_prueba en cualquier gestor de MySQL por ejemplo Workbench, logearse con usuario root y la contraseña respectiva.
###Script: create database db_prueba;

## Clave de usuario root de MySql
Las claves del usuario root se pueden cambiar en la siguiente ubicación del proyecto de Spring Boot
 src/main/resources -> application.properties -> spring.datasource.password
 y se debe colocar la contraseña correspondiente

## Clonar y ejecutar
- Realizar git clone del repositorio en cualquier carpeta.
- Abrir proyecto con Spring Tools Suite.
- Ejecutar aplicación con Spring Boot app: empleados-backend
- Seguir con las instrucciones del repositorio de angular
