Proyecto Avanzado en SQL Server: Sistema Bancario 💳
---
Este proyecto implementa conceptos avanzados de SQL Server para desarrollar un sistema de base de datos optimizado que gestiona clientes, cuentas, préstamos, sucursales y transacciones bancarias.

📚 Descripción del Proyecto
---
El objetivo principal es construir una base de datos robusta y escalable que integre:

Procedimientos Almacenados: Para automatizar la apertura de cuentas y el registro de préstamos.
Triggers: Para garantizar la consistencia de datos, evitando saldos negativos y actualizando automáticamente los saldos tras cada transacción.
CTE (Common Table Expressions): Para consultas avanzadas, como análisis de clientes con préstamos activos.
Particiones: Mejora del rendimiento para tablas con grandes volúmenes de datos.
Funciones de Ventana: Para análisis detallado de transacciones, como saldos acumulados y rankings de clientes.
Índices: Optimizan la velocidad de las consultas en campos clave.


🔧 Requisitos Previos
---
![SQLServer](https://github.com/user-attachments/assets/e606730a-4003-4bfc-9ced-faa720a87c93)

- SQL Server 2019 o superior.
- SQL Server Management Studio (SSMS).
- Git para el control de versiones.

🛠 Cómo Ejecutar el Proyecto
----
1. Clona el repositorio 
```bash
git clone https://github.com/LuisGerardoTequia/Sistema_Bancario_SQLServer.git  
cd Sistema_Bancario_SQLServer  
```

2. Carga los Scripts en este Orden:

01_Create_Database.sql: Crea la base de datos BancoSQL.
02_Create_Tables.sql: Define las tablas principales (clientes, cuentas, préstamos, etc.).
03_Insert_Data.sql: Inserta datos iniciales para pruebas.
04_Advanced_Functionality.sql: Implementa triggers, funciones y procedimientos.
Prueba Funcionalidades Avanzadas:

3. Ejecuta consultas para validar CTE y Windows Functions.
Realiza inserciones para activar triggers y verificar su funcionamiento.

🌟 Beneficios del Proyecto
---
Automatización: Los triggers y procedimientos almacenados eliminan tareas manuales.
Optimización: Índices y particiones mejoran el rendimiento en conjuntos de datos grandes.
Análisis Avanzado: Funciones de ventana y CTE proporcionan insights profundos sobre los datos.

Y listo hemos terminado, espero les haya gustado mi proyecto😄
---
