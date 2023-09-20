# Proyecto_N1

## 1. DIAGRAMA UML

### Tabla Taller
Atributos: ID_Taller (clave primaria), nombre, dirección, teléfono, fecha_inicio, descripción.

### Tabla Empleado
Atributos: ID_Empleado (clave primaria), nombre, apellido, teléfono, puesto, fecha_contratación, salario.

### Tabla Cliente
Atributos: ID_Cliente (clave primaria), nombre, apellido, teléfono, dirección, correo_electrónico.

### Tabla Vehículo
Atributos: ID_Vehículo (clave primaria), marca, modelo, año, número_chasis, número_placa.

### Tabla Servicio
Atributos: ID_Servicio (clave primaria), nombre_servicio, descripción, precio, duración.

### RELACIONES

Puede haber una relación "es_cliente_de" entre Taller y Cliente para indicar qué cliente está relacionado con qué taller.

Puede haber una relación "trabaja_en" entre Taller y Empleado para indicar qué empleado trabaja en qué taller.

Puede haber una relación "pertenece_a" entre Cliente y Vehículo para indicar qué vehículos pertenecen a qué clientes.

Puede haber una relación "ofrecido_por" entre Taller y Servicio para indicar qué servicios ofrece el taller.
