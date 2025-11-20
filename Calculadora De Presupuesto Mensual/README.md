# Calculadora de Presupuesto Mensual — README

##  Descripción del Caso
La aplicación **Calculadora de Presupuesto Mensual** permite registrar ingresos y gastos para generar un balance financiero mensual. Su propósito es ayudar a los usuarios a gestionar su economía personal, ofreciendo un informe claro y detallado del estado de sus finanzas.

---

##  Objetivos
- Garantizar cálculos precisos del balance mensual.
- Prevenir pérdida de datos mediante almacenamiento persistente.
- Mejorar la accesibilidad del sistema adaptándolo a múltiples plataformas.
- Incrementar la confiabilidad y mantenibilidad del software.

---

##  Requerimientos del Sistema

### **Requerimientos Funcionales**
1. Registrar ingresos y gastos.
2. Calcular balance mensual automáticamente.
3. Validar datos ingresados (solo números, montos positivos, campos completos).
4. Guardar información entre sesiones mediante base de datos o archivos.
5. Generar informe mensual consultable.

### **Requerimientos No Funcionales**
1. Interfaz simple y entendible para el usuario.
2. Compatibilidad multiplataforma.
3. Respuesta rápida en cálculos y carga de datos.
4. Mantenibilidad del código para futuras mejoras.

---

##  Tabla de Pruebas

| Nº | Prueba | Entrada | Resultado Esperado | Tipo |
|----|--------|---------|---------------------|------|
| 1 | Validación de datos | Monto negativo | Rechazar y mostrar advertencia | Correctivo |
| 2 | Cálculo correcto | Ingresos: 1000, Gastos: 400 | Balance = 600 | Correctivo |
| 3 | Persistencia | Cerrar y abrir app | Datos deben mantenerse | Preventivo |
| 4 | Compatibilidad móvil | Acceso desde smartphone | Interfaz adaptable | Adaptativo |
| 5 | Registro incompleto | Falta un campo | Bloqueo del registro | Correctivo |

---

##  Tipo de Mantenimiento Propuesto

### **1. Correctivo**
Para solucionar errores de cálculo en el balance y evitar resultados incorrectos cuando los datos no son válidos.

### **2. Preventivo**
Implementar almacenamiento persistente para evitar pérdida futura de información importante del usuario.

### **3. Adaptativo**
Desarrollar una versión PWA para asegurar compatibilidad en móviles, tablets y navegadores modernos.

---

##  Reflexión sobre el Control de Versiones
El uso de **Git y GitHub** facilita enormemente la gestión del proyecto:
- Permite rastrear cada cambio realizado.
- Favorece el trabajo colaborativo del equipo.
- Garantiza que siempre exista un respaldo del código.
- Reduce riesgos al aplicar mantenimiento, ya que se pueden revertir errores rápidamente.

El control de versiones no solo ordena el desarrollo, sino que **aumenta la calidad del software**, permitiendo aplicar mejoras con seguridad y claridad.

---

##  Conclusión
La aplicación requiere mejoras clave en validación, persistencia y compatibilidad, cada una alineada con diferentes tipos de mantenimiento. Implementar estas mejoras garantiza un software más estable, útil y sostenible en el tiempo.
