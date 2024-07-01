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
