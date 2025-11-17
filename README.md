# Sistema de pedidos para cafetería universitaria

## 📝 Descripción del caso
Este proyecto consiste en el desarrollo de un sistema digital de pedidos para una cafetería universitaria.

---

## 🏆 Objetivo
Mejorar la experiencia de los estudiantes y del personal universitario al permitirles realizar pedidos de manera rápida y evitando aglomeraciones

---

## 📌 Requerimientos
### REQUERIMIENTOS FUNCIONALES
**Registro de pedidos:** El usuario puede seleccionar productos del menú, indicar cantidades y registrar el nombre del cliente.
**Visualización del menú:** El sistema mostrará todos los productos disponibles, clasificados por categorías y precios.
**Edición/cancelación de pedidos:** El sistema permitirá modificar o cancelar pedidos antes de la confirmación final.

### REQUERIMIENTOS NO FUNCIONALES
- **Rendimiento:** Respuesta menor a 3 segundos al registrar pedidos y menor a 2 segundos al mostrar el menú.
- **Disponibilidad:** Recuperación ante fallos y funcionamiento continuo durante horas de alta demanda.
- **Cumplimiento de estándares:** Aplicación de buenas prácticas de desarrollo, seguridad y manejo de datos.

---

## 🧪 Tabla de pruebas
| Caso de prueba | Requerimiento asociado | Datos de entrada | Resultado esperado | Resultado obtenido |
|----------------|------------------------|------------------|--------------------|--------------------|
| Registrar un pedido exitosamente | RF01 | Producto: “Café”, Cant: 2, Cliente: Ana | Pedido registrado y mensaje en < 3 s | ✔ Funciona según lo esperado |
| Visualizar menú completo | RF02 | — | Menú cargado en < 2 s sin errores | ✔ Funciona según lo esperado |
| Editar un pedido antes de confirmar | RF03 | Cambiar cantidad de 1 → 3 | Pedido actualizado y mensaje de confirmación | ✔ Funciona según lo esperado |

---

## 🛠️ Tipo de mantenimiento propuesto

### **🔧 Mantenimiento correctivo**
Se propone implementar mantenimiento correctivo para:

- Corregir fallos en conexión con base de datos.
- Resolver errores en el proceso de registro y actualización de pedidos.
- Reparar fallas de visualización del menú durante alta demanda.
- Arreglar bugs en la edición o cancelación de pedidos antes de la confirmación.
- Ajustar mensajes de confirmación inconsistentes o tardíos.

Este mantenimiento garantiza que el sistema cumpla con los requerimientos y brinde una experiencia estable y confiable.

---

## 🔄 Reflexión sobre el control de versiones

El uso de herramientas de control de versiones como **Git** y plataformas como **GitHub** aporta múltiples beneficios:

- Permite llevar un **historial claro de cambios**, facilitando el seguimiento de errores.
- Ayuda a organizar el trabajo mediante ramas (branches) para nuevas funciones o correcciones.
- Facilita la colaboración entre varios desarrolladores sin riesgo de sobrescribir código.
- Mejora la mantenibilidad mediante revisiones (pull requests) y control de versiones de documentación.
- Permite revertir cambios en caso de errores, aumentando la seguridad del desarrollo.

El control de versiones es fundamental para asegurar la evolución ordenada y profesional del sistema.
