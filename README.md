# Proyecto Calvin Klein – Aplicación Web de Gestión

Este proyecto fue desarrollado por cuatro estudiantes de Ingeniería en Sistemas como parte de un curso universitario. Se trata de una aplicación web diseñada para facilitar la gestión de productos, facturas, clientes y usuarios, con una temática inspirada en Calvin Klein.

##Tecnologías utilizadas##

- Visual Studio 2022
- ASP.NET MVC (C#)
- Entity Framework (Code First)
- SQL Server (base de datos)
- Bootstrap (interfaz)

##Funcionalidades principales##

##Facturas##
- Crear facturas para ventas.
- Editar o eliminar facturas existentes.
- Asociar facturas a clientes registrados.

##Productos##
- Agregar nuevos productos.
- Editar la cantidad de productos disponibles.
- Eliminar productos del inventario.
- Visualización de productos fuera de stock.

##Clientes##
- Agregar nuevos clientes.
- Editar su categoría (Frecuente o Normal).
- Asociarlos a facturas para el historial de compras.

##Usuarios (Empleados)##
- Gestión de empleados que pueden iniciar sesión.
- Cambiar el estado del usuario entre **Activo/Inactivo**.
- Si el usuario está **inactivo**, no podrá iniciar sesión en el sistema.

##Pantalla de bienvenida##
- Mensaje de saludo personalizado para el usuario autenticado.

###Acerca de##
- Apartado con información general del proyecto, los participantes y el objetivo.

##Base de datos##

- **Nombre:** `CalvinKlein`
- **Tablas:**
  - `Facturas`
  - `Clientes`
  - `Usuarios`
  - `Productos`

El modelo de datos fue desarrollado con Entity Framework bajo el enfoque **Code First**.

---

##Comandos de Entity Framework (Package Manager Console)##

### 1. Crear una migración (por primera vez o tras cambios en los modelos):

```bash
Add-Migration Update-Database

### 2. Crear o actualizar la Base de Datos
UpdateDatabase
