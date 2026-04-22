# Software_fj
Sistema Integral de Gestión de Clientes, Servicios y Reservas

# Objetivo general del proyecto
Crear un sistema de gestion integral que este basado en una estructura de objetivos, 
para que sea un sistema eficiente de manejo de clientes, servicios y reservas manteniendo estabilidad
en la operacion del sistema por medio del uso avanzado de excepciones y el registro de archivos locales
sin tener dependencia a una base de datos.

# Objetivos especificos.
1.Crear estructuras modulares de gerarquias implementando clases y metodos especiales
2.Proponer un metodo robusto en el control para mitigar errores
3.Implementar logica mediante metodos sobrecargados para el calculo de costos
4.Realizar escenarios de pruebas de almenos 10 operaciones

# Estructura del sistema
El sistema esta estructurado con los soguientes elementos:
-Bases: define la estructura de los objetos del sistema.
-Gestion de usuarios: Validacion de los datos personales.
-Gestion en los servicios: metodos para calcular el costo y la validacion.
-Gestion de las reservas: integra el usuario, el servicio, el tiempo
y el estado de la reserva
-Control de errores: Captura excepciones

# Demostraciones de las pruebas.
El sistema incluye 10 operaciones de prueba
-Casos no validos: Datos erroneos o datos faltantes, servicio no disponible 
o calculos de costos erroneos
-Casos validos: Registros correctos, creacion de reservas exitosas
-Respuestas: Se captura las excepciones y registra los errores en el log y sigue
su ciclo de operacion sin algun tipo de interrupcion

# Autores

Luna Naranjo
