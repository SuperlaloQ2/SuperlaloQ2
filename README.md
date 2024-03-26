- 👋 Hi, I’m @SuperlaloQ2

<!---
SuperlaloQ2/SuperlaloQ2 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

SlQ Token ERC20 es :

contrato estándar de un token ERC20 en Ethereum. Las funcionalidades principales que proporciona este contrato son las siguientes:

Transferencias de Tokens: Permite a los usuarios transferir tokens entre cuentas.

Aprobación de Gastos: Permite a los titulares de tokens aprobar a otros

usuarios (gastadores) para gastar tokens en su nombre dentro de ciertos límites.

Consulta de Saldo: Permite a los usuarios consultar el saldo de tokens de una cuenta específica.

Consulta de Asignación: Permite a los usuarios consultar cuántos tokens han aprobado para ser gastados por un gastador específico.

Suministro Total: Proporciona una función para consultar el suministro total de tokens.

Eventos: Emite eventos cuando se realizan transferencias de tokens o se aprueba el gasto de tokens.

Seguridad: Utiliza la biblioteca SafeMath para realizar operaciones aritméticas seguras y evitar desbordamientos o subdesbordamientos.

Función Fallback: Rechaza cualquier intento de enviar ether (ETH) al contrato, evitando que se envíen accidentalmente fondos al contrato.
