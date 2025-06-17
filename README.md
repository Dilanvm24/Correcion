# Correcion
📄 Proyecto: Cálculo de Pago para Programadores
Este programa en Java solicita información de un programador y sus proyectos, calcula la tarifa final por hora, los pagos individuales por cliente, bonificaciones, descuentos e impuestos, y finalmente genera un reporte detallado con el total a recibir.

🛠️ Tecnologías utilizadas
Lenguaje: Java

Versión: Java 8 o superior

Librerías usadas:

java.util.Scanner (entrada de datos)

java.time.LocalDate (fecha actual)

📋 ¿Qué hace el programa?
Solicita al usuario ingresar:

Datos personales (nombre, correo, ciudad, país, edad).

Tipo de contrato (Fulltime/Parttime/Freelance).

Nivel de experiencia (Junior/Senior).

Años de experiencia laboral.

Nombres de 3 clientes.

Horas trabajadas y bonificación de cada cliente.

Calcula:

Tarifa base + bonificación por experiencia y nivel.

Pago por cada cliente.

Subtotal.

Descuentos (3%).

Impuestos (9%).

Total neto a recibir.

Muestra un reporte en consola con toda esta información.

🧮 Fórmulas utilizadas
Tarifa final por hora
tarifaFinal = tarifaBase + tarifaNivel + (añosExperiencia * 1.5)

Pago por proyecto
pago = horasTrabajadas * tarifaFinal + bono

Descuento (3%)
descuento = subtotal * 0.03

Impuesto (9%)
impuesto = subtotal * 0.09

Total a recibir
totalFinal = subtotal - descuento - impuesto

