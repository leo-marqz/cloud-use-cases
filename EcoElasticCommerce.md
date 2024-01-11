# Proyecto EcoElasticCommerce
---

Datos del client
--
Cliente: ABC Child

Direccion: San Salvador, San Salvador, El Salvador.

Descripcion: ABC Child es un ecommerce de producto para niños y adolecentes en el cual se ofrecen productos de categorias como entretenimiento, creatividad, ciencia basica, control familiar, etc. El servicio ha permitido un crecimiento nacional y ahora nos extendemos a nivel internacional creando la necesidad de mejorar el servicio a nivel de logistica, infraestructura y aplicaciones para tener resiliciencia, baja latencia y escalabilidad.


Datelles de infraestructura y aplicativo actual
--
Aplicativo ecommerce:
- Base de Datos: Microsoft SQL Server
- Back-End: Api asp.net en .net 6
- Front-End: Angular

Aplicativo de administracion:
- Aplicacion Blazor Hybrid para administrar la parte local como lo son empleados e inventarios de productos de ecommerce
- Conexion a la base de datos del ecommerce para administrar Stock, Promociones, seguimiento de entrega, etc.

Infraestructura:
- 4 servidores windows server para aplicativo frontend
- 6 servidores windows server para aplicativo backend
- 

Requisitos de solucion
--
- Alta dispobibilidad.
- Escalabilidad automatica.
- Balanceo de trafico.
- Almacenamiento de archivos estaticos redundante
- Seguridad contra ataques Dos y DDos.
- Servidores Linux Ubuntu para reduccion de costos.
- Monitoreo de red y de Aplicaciones.
- ...

Objetivos
--
- Infraestructura resiliente, escalable y flexible ante eventos o demanda del servicio.
- ....


## Solucion
---

### Propuesta de despliegue en Microsoft Azure

Servicios Cloud:
- Azure Resource Group
- Azure Virtual Network
- Azure Network Security Group
- Azure Image
- Azure Virtual Machine
- Azure Virtual Machine Scale Sets
- Azure Application Gateway
- Azure Firewall
- Azure SQL Database
- Azure App Service Plan
- Azure App Service
- Azure Monitor

<div style="margin-bottom:15px">
    <a style="text-decoration:none;color:white;background:blue;display:block-inline;padding:5px;border-radius:3px;cursor:pointer;" href="https://azure.calculator.com/estimate?id=knadfkloinaso44848-33">
        Calculadora de estimacion de costo > 
    </a>
</div>
Diseño de solucion de alto nivel

![Azure HLD](https://learn.microsoft.com/en-us/azure/architecture/browse/thumbs/aks.png)

### Propuesta de despliegue en Amazon Web Service


