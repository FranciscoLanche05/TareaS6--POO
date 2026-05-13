# Tarea: Interfaces en Java - POO
Este repositorio contiene la resolución de la tarea de la semana 6 sobre **Interfaces en Java**, desarrollada para la asignatura de Programación Orientada a Objetos en la Escuela Politécnica Nacional.

## 🚀 Contenido del Proyecto

El proyecto está dividido en tres niveles de complejidad, aplicando los conceptos de contratos de comportamiento y polimorfismo.

### 1. Sistema Académico de Documentos (Nivel Medio)
Implementación de la interfaz `Imprimible` para la gestión de:
* Certificados.
* Actas de Notas.
* Horarios Académicos.
Cada clase gestiona sus propios atributos (como número de documento o carrera) y personaliza su método de impresión.

### 2. Sistema Bancario de Pagos (Nivel Medio)
Uso de la interfaz `Pagable` para procesar pagos por diferentes medios:
* Efectivo.
* Tarjeta (con comisión).
* Transferencia (con comisión).
Incluye validaciones de montos mayores a cero y lógica de negocio específica para cada canal.

### 3. Sistema de Roles Empresariales (Nivel Avanzado Plus)
Este es el núcleo del proyecto, donde se diferencia la responsabilidad mediante múltiples interfaces
* **Autenticable:** Gestión de inicio de sesión.
* **Reportable:** Capacidad de generar reportes.
* **Gestionable:** Acceso a la gestión de datos.

[cite_start]**Roles implementados:** Cajero, Administrador y Supervisor

## 🛠️ Buenas Prácticas Aplicadas
* **Encapsulamiento:** Atributos privados y constructores adecuados.
* **Polimorfismo:** Declaración de variables utilizando el tipo de la interfaz.
* **Validaciones:** Control de valores nulos, negativos o fuera de rango.
---
**Estudiante:** Francisco 
**Institución:** Escuela Politécnica Nacional (EPN) 
**Periodo:** 2026-A
