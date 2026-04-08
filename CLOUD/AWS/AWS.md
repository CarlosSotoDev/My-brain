# <mark style="background:#d4b106">AWS</mark>

AWS (Amazon Web Services) es la plataforma de servicios en la nube más completa y adoptada del mundo. En lugar de que una empresa tenga que comprar, mantener y configurar sus propios servidores físicos o bases de datos en un cuarto refrigerado, simplemente se los "alquila" en Amazon y accede a ellos a través de internet.

---
## <mark style="background:#40a9ff">El concepto de "Computación en la nube"</mark>

AWS funciona bajo un modelo de pago por uso. Esto significa que solo pagas por la potencia de cómputo, el almacenamiento o los ervicios que consumes, exactamente igual que como pagas las factura de luz o el agua.

### **<mark style="background:#affad1">Beneficios clave</mark>**

- **Escalabilidad**: Si tu aplicación pasa de tener 10 usuarios a 10000 en un día , AWS puede añadir recursos automáticamente para soportar la carga.
- **Costo**: Elimina el gasto inicial de comprar hardware costos (CAPEX) y lo convierte en un gasto operativo mensual (OPEX)
- **Alcance Global**: Puedes desplegar tu software en servidores ubicados en casi cualquier parte del mundo en cuestión de minutos
---
## <mark style="background:#40a9ff">Los servicios principales</mark>

AWS ofrece más de 200 servicios integrales, pero los más utilizados se agrupan en estas categorías

| <center>CATEGORIA</center> | <center>SERVICIO POPULAR</center> | <center>FUNCIONAMIENTO</center>                                                         |
| -------------------------- | --------------------------------- | --------------------------------------------------------------------------------------- |
| COMPUTO                    | <center>EC2</center>              | Servidores virtuales donde puedes instalar cualquier software                           |
| ALMACENAMIENTO             | <center>S3</center>               | Un "Contenedor" infinito para guardar archivos (fotos, videos, backups)                 |
| BASES DE DATOS             | <center>RDS</center>              | Bases de datos gestionadas (MySQL, PostgresSQL, etc) sin preocuparte por la instalación |
| REDES                      | <center>VPC</center>              | Crea una sección aislada de la nube de AWS para definir tu propia red virtual           |
| SERVERLESS                 | <center>Lambda</center>           | Ejecuta código solo cuando es necesario, sin gestionar ningún servicio                  |

---
## <mark style="background:#40a9ff">Infraestructura Global</mark>

Para garantizar que las aplicaciones siempre estén disponibles, AWS divide su infraestructura en:
- **Regiones**: El Ubicaciones geográficas en todo el mundo (EE.UU) 
- **Zonas de Disponibilidad**: Dentro de cada región, hay varios centro s de datos físicos aislados, entre sí para que, si uno falla (por un desastre natural, por ejemplo), los otros sigan funcionando
---
## <mark style="background:#40a9ff">Resumen</mark>

- **Computación en la Nube:** AWS opera bajo un modelo de **pago por uso**, eliminando la necesidad de invertir en hardware físico. Permite una **escalabilidad** inmediata y un alcance global, transformando costos fijos en gastos operativos variables según la demanda.
    
- **Servicios Principales:** La plataforma ofrece un ecosistema integral que incluye **Cómputo** (instancias virtuales como EC2), **Almacenamiento** (objetos en S3), **Bases de Datos** gestionadas (RDS) y soluciones **Serverless** (Lambda), permitiendo construir arquitecturas robustas y modulares.
    
- **Infraestructura Global:** La red se organiza en **Regiones** geográficas estratégicas, las cuales contienen múltiples **Zonas de Disponibilidad (AZ)**. Esta estructura garantiza alta disponibilidad y tolerancia a fallos al mantener los centros de datos físicamente aislados entre sí.