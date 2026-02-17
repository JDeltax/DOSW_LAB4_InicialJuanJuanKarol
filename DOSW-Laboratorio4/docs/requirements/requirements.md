# 📄 Requerimientos del Sistema

## 1. Lista general de requerimientos

El sistema de Bankify tiene los siguientes requerimientos (descripción a alto nivel):

### 1.1 Requerimientos funcionales

El sistema de Bankify debe tener la capacidad de:

1. Validar estructura de cuenta
2. Gestionar el estado de la cuenta
3. Procesar depósitos
4. Generar los reportes tributarios
5. Eliminar registro de clientes
 
### 1.2 Requerimientos No funcionales

El sistema de Bankify debe tener:

1. Seguridad
2. Udsabilidad
3. Integridad de los Datos
4. Disponibilidad de operación
5. Interoperabilidad 

## 2. Diagramas de caso de uso

### 2.1 Requerimiento Funcional 1

| Campo | Descripción |
|------|-------------|
| **ID** | RF-01 |
| **Nombre del requerimiento** | Gestionar estado de la cuenta |
| **Descripción** | El sistema debe permitir al cliente ver el saldo y datos básicos que posee de sus cuentas vinculadas |
| **Precondiciones** | Para que el sistema cumpla con este requerimiento, Bankify debe tener previamente al cliente autentificado y con al menos una cuenta activa asociada |
| **Actor** | Cliente |
| **Flujo principal** | 1. El actor selecciona la opcion de consular saldo <br>2. El sistema recupera la info de las cuentas asociadas (id del cliente) <br>3. El sistema muestra en la pantalla el numero de la cuenta y el saldo disponible|
| **Diagrama de caso de uso** | *imagen y link*|
| **Poscondiciones** | Se espera como resultado que el cliente utilizando el sistema pueda ver su info financiera sin alterar los datos que ya tiene |


### 2.2 Requerimiento Funcional 2

| Campo | Descripción |
|------|-------------|
| **ID** | RF-02 |
| **Nombre del requerimiento** | Realizar depósitos |
| **Descripción** | El sistema debe permitir registrar ingresos del dinero en una especifica cuenta validando así, la existencia de la cuenta antes de la transacción. |
| **Precondiciones** | Para que el sistema cumpla con este requerimiento, Bankify debe tener previamente la cuenta destino existente y validada.  |
| **Actor** | Cliente o usuario externo |
| **Flujo principal** | 1. El actor ingresa el numero de cuenta donde va a depositar y el respectivo monto <br>2. El sistema validar que la cuenta exista y esté activas <br>3. El sistema suma el monto al saldo de la cuenta depositada y  registra en un historial la transaccion |
| **Diagrama de caso de uso** | *imagen y link*|
| **Poscondiciones** | Se espera como resultado que el saldo de la cuenta a depositar incremente y se genere el combrobante. |

### 2.3 Requerimiento Funcional 3

| Campo | Descripción |
|------|-------------|
| **ID** | RF-03 |
| **Nombre del requerimiento** | Generar reportes tributarios |
| **Descripción** | El sistema debe generar un documento con el resumen de movimientos anuales para tramites legales.  |
| **Precondiciones** | Para que el sistema cumpla con este requerimiento, Bankify debe tener previamente consolidados los movimientos financieros del año correspondiente a generar. |
| **Actor** | cliente |
| **Flujo principal** | 1. El actor solicita la generación del reporte tributario seleccionando el año correspondiente <br>2. El sistema compila la info de todas las cuentas pertenecientes al clientes <br>3. El sistema exporta la información y genera el archivo en formato PDF |
| **Diagrama de caso de uso** | *imagen y link*|
| **Poscondiciones** | Se espera como resultado un PDF con la info recolectada y correcta de los movimientos bancarios del año seleccionado por el actor |

## 3. Preguntas





