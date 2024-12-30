# API de Pedidos

Esta API permite gestionar clientes, productos y pedidos. Incluye funcionalidades como crear pedidos, actualizar productos y obtener información sobre clientes y productos.

## Entorno 
.net 8.0
EntityFRamework 8.0

## Instalación
consola --

1. Clona el repositorio:
   ```consola
   https://github.com/lagiomAce/pedidosAPI.git

2. Navega al directorio del proyecto:

cd PedidosAPI

3. Restaura las dependencias:

dotnet restore


4. Ejecuta la aplicación:

dotnet run

USO 

console
---------dotnet ef migrations add InitialCreate

---------dotnet ef database update^


Una vez que la API esté en ejecución acceder a los siguientes endpoints:

GET /api/clientes: Obtener todos los clientes.
POST /api/clientes: Crear un nuevo cliente.
GET /api/productos: Obtener todos los productos.
POST /api/pedidos: Crear un nuevo pedido.

Swagger UI
Para ver y probar los endpoints, puedes acceder a la interfaz de Swagger UI en http://localhost:5045/swagger.
