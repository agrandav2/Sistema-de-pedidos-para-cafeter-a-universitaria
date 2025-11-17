# Propuesta de mantenimiento correctivo  
## Sistema de pedidos para cafetería universitaria

---

### 1. Descripción general
El mantenimiento correctivo tiene como finalidad **resolver fallos o defectos** detectados en el sistema de pedidos utilizado en la cafetería universitaria.  
Estas acciones buscan restaurar el funcionamiento normal del sistema y asegurar que los usuarios (estudiantes, personal y operadores) puedan realizar pedidos sin interrupciones.

---

## 2. Objetivos del mantenimiento correctivo
- Restablecer la **operación normal** del sistema ante errores o fallos.  
- **Eliminar defectos** que afectan el registro de pedidos, la visualización del menú o el procesamiento de órdenes.  
- Reducir tiempos de inactividad que impacten en la atención al cliente.  
- Garantizar la **fiabilidad y estabilidad** del sistema.  

---

## 3. Alcance
El mantenimiento abarca los módulos de:
- **Registro de pedidos**  
- **Visualización del menú**  
- **Edición y cancelación de pedidos**  
- **Base de datos**  
- **Interfaz gráfica** y flujos de navegación  

> *No incluye nuevas funciones ni mejoras evolutivas; corresponde únicamente a la corrección de fallos existentes.*

---

## 4. Actividades de mantenimiento correctivo

### 🔧 4.1. Identificación y diagnóstico de fallos
- Análisis de reportes de errores generados por los usuarios y el sistema.  
- Revisión de logs para detectar excepciones, fallos de conexión o errores de consulta.  
- Ejecución de pruebas de regresión para reproducir el problema.

### 🔧 4.2. Corrección de errores
Se realizarán correcciones en problemas como:
- Fallos al registrar pedidos (duplicados, validaciones incorrectas).  
- Problemas en la carga del menú (desorden en categorías, tiempos lentos).  
- Errores en la edición o cancelación de pedidos antes de la confirmación final.  
- Inconsistencias en la base de datos.  
- Caídas del sistema por errores no controlados.

### 🔧 4.3. Pruebas posteriores a la corrección
- Pruebas unitarias en módulos corregidos.  
- Pruebas de integración para asegurar que las correcciones no afecten otras funciones.  
- Validación con usuarios reales de la cafetería.

### 🔧 4.4. Documentación de cambios
- Actualización del registro de incidencias.  
- Documentación de modificaciones en código, scripts SQL y configuraciones.  
- Actualización del manual técnico si aplica.

---

## 5. Responsables
- **Equipo de desarrollo:** diagnóstico, corrección y pruebas técnicas.  
- **Administrador del sistema:** validación y despliegue.  
- **Personal de cafetería:** reporte de fallos y pruebas funcionales finales.

---

## 6. Tiempo estimado
| Tipo de fallo | Tiempo estimado |
|---------------|-----------------|
| Crítico (impide procesar pedidos) | 2–4 horas |
| Alto (afecta un módulo entero) | 1 día |
| Medio (fallo aislado) | 3–6 horas |
| Bajo (visual o menor) | 1–2 horas |

---

## 7. Resultados esperados
- Restablecimiento completo del sistema sin errores detectados.  
- Reducción de interrupciones en el servicio de atención.  
- Mayor fiabilidad al procesar pedidos.  
- Incremento en la satisfacción de los usuarios y del personal.

---

## 8. Recomendación adicional
Se recomienda implementar un **mantenimiento preventivo mensual** para identificar fallos antes de que afecten la operación diaria y reducir futuros costos de reparación.
