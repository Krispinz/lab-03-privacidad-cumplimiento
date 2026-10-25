

| Problema | Principio afectado | Riesgo | Control propuesto |
| :---: | :---: | :---: | :---: |
| Mal orden de información | Minimización | Alto | Realizar un examen de qué información es realmente necesaria |
| Sin roles y/o accesos específicos | Autenticación | Alto | Limitar quiénes pueden acceder a la base de datos y/o sus respectivas tablas. |
| Sin control de accesos | Confidencialidad | Alto | Limitar en gran medida la cantidad de personas que pueden acceder a la base de datos. |
| Sin control de acciones | Integridad | Alto | Mantener un orden respectivo entre tablas y copias para evitar el borrado de información repetitiva. |
| Riesgo en la disponibilidad | Disponibilidad | Medio | Aunque no haya mucho riesgo, mantener la base de datos lo más accesible posible en caso de ser necesario, limitando las acciones. |
| No hay integralidad en las acciones de cada trabajador de cada área | Rendición de cuentas | Alto | Como no hay un control de quién realiza qué, ordenar realizar un registro de todas las acciones que afecten directamente la base de datos y las tablas de la misma. |
| Inyecciones SQL | Integridad | Alto | Realizar un correcto enlace entre variables para evitar las inyecciones SQL lo mejor que sea posible. |
| Datos en exceso causando ruido | Minimización | Medio | Eliminar el exceso de atributos de datos que sean considerados “necesarios” y dejando solo los indispensables. |
| Confidencialidad mal empleada | Confidencialidad | Alto | Mantener la confidencialidad entre las pocas personas con acceso entre las tablas de la bases de datos evitando compartir datos innecesarios con otras áreas. |
| Falta laboral de área | Autenticación | Bajo | Ordenar la carga de trabajo a sus respectivas áreas, aprovechándolas tanto como sea posible para evitar compartir accesos a más áreas distintas. |

