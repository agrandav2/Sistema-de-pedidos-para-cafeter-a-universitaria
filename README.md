# Sistema de pedidos para cafetería universitaria

## 📝 Descripción del caso
Este proyecto consiste en el desarrollo de un sistema digital de pedidos para una cafetería universitaria.

---

## 🏆 Objetivo
Mejorar la experiencia de los estudiantes y del personal universitario al permitirles realizar pedidos de manera rápida y evitando aglomeraciones

---

## 📌 Requerimientos
### REQUERIMIENTOS FUNCIONALES
- **Registro de pedidos:** El usuario puede seleccionar productos del menú, indicar cantidades y registrar el nombre del cliente
- **Visualización del menú:** El sistema mostrará todos los productos disponibles, clasificados por categorías y precios
- **Edición/cancelación de pedidos:** El sistema permitirá modificar o cancelar pedidos antes de la confirmación final

### REQUERIMIENTOS NO FUNCIONALES
- **Rendimiento:** Respuesta menor a 3 segundos al registrar pedidos y al mostrar el menú
- **Disponibilidad:** Recuperación ante fallos y funcionamiento continuo durante horas de alta demanda

---

## 🧪 Tabla de pruebas
| Tipo de prueba          | Requerimiento asociado | Datos de entrada                          | Resultado esperado                                             | Resultado obtenido                          |
|-------------------------|-------------------------|--------------------------------------------|------------------------------------------------------------------|----------------------------------------------|
| Con resultado esperado  | Registro de usuario     | Nombre de usuario: agrandav2<br>Contraseña: tortugamarina | El sistema registra y guarda el usuario y la contraseña          | ¡Cuenta creada correctamente!                |
| Con resultado esperado  | Realización de pedidos  | Café con leche                             | El producto aparece en el carrito                                | **Café con leche** ha sido añadido al carrito.   |
| Con resultado esperado  | Seguimiento de pedidos  | Finalizar la compra del producto           | El sistema notifica el estado reciente del producto              | ¡Listo para recoger!                         |
| De validación           | Seguridad               | Contraseña: 1234                           | La contraseña se guarda cifrada                                  | 4321                                         |
| De validación           | Usabilidad              | Accedió desde Chrome                       | El sistema carga y muestra la interfaz según el dispositivo      | —                                            |
| De validación           | Mantenibilidad          | Agregar una nueva funcionalidad            | El nuevo módulo funciona correctamente y es individual           | 🌐 PEDIDOS EN LÍNEA                            |

---

## 🛠️ Tipo de mantenimiento propuesto
Correctivo

---

## 🔄 Reflexión sobre el control de versiones
El uso de herramientas de control de versiones como *Git* y plataformas como *[GitHub](https://github.com)* aporta múltiples beneficios:

- Permite llevar un historial claro de cambios, facilitando el seguimiento de errores
- Facilita la colaboración entre varios desarrolladores sin riesgo de sobrescribir código
- Mejora la mantenibilidad mediante revisiones y control de versiones de documentación
- Permite revertir cambios en caso de errores, aumentando la seguridad del desarrollo
