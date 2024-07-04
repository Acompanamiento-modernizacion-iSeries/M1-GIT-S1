# Requisitos sistema bancario Banco Futuro.

## Funcionalidades:

### 1. Registro de usuarios:

Yo como usuario requiero poder registrarme en la app y que está información quede registrada.

#### Criterios de aceptación:

- Se debe tener la opción de registrarse como usuario nuevo
- Se solicitan los datos básicos de cada persona.
- Se asigna por defecto un nombre de usuario compuesto por nombres y apellidos.
- Se guarda toda la información del usuarios en base de datos

### 2. Logs de auditoria:

Yo como administrador de la app, requiero visualizar un log de auditoria en el cual pueda encontrar toda la información relacionada a las transacciones realizadas por el usuario en la app.

#### Criterios de aceptación:

- Se debe guardar cada transacción realizada en la app en un archivo de log.
- Debe contener datos de fecha, hora, tipo de transacción, cuentas origen y destino, monto, estado.

### 3. Recomendaciones de seguridad:

Yo como administrador de la app, requiero contar con un paso a paso de buenas prácticas y sugerencias de seguridad a la hora de implementar la app.

#### Criterios de aceptación:

- Se debe contar con una guía de paso a paso de buenas practicas, sugerencias y demás consideraciones de seguridad.

### 4. Contabilidad

Yo como area contable requiero acceso a los movimientos contables de cada día.

#### Criterios de aceptación:

- Se debe contar con logs de cada uno de los días del año y su movimiento contable al cierre.
- Debe incluir información de cuentas afectadas, movimiento, valores.


### 5. Consulta saldos

Yo como usuario de la app requiero consultar los saldos actuales de mis diferentes productos bancarios.

#### Criterios de aceptación:

- Se requier una opción en la cual se pueda consultar el detalle de saldos y productos asociados a un cliente.
- Debe incluir información tipo de cuenta/producto y su saldo actual.

### 6. Información Cajeros

Yo como administrador de la app requiero la información actualizada de todos los cajeros disponibles.

#### Criterios de aceptación:

- Se requier un log con la información de todos los cajeros automaticos disponibles.
- Debe incluir información de ubicación, horario, servicios disponibles, contacto de soporte.