# 🧩 Proyecto Ecoenergixx – Análisis Funcional y Planificación Ágil SCRUM ☀️

Este repositorio contiene la **documentación estructurada** del sistema de ventas de paneles solares “Ecoenergixx”, aplicando prácticas de análisis funcional ágil y planificación de sprints en Scrum.

---

## 🎯 Objetivo

Aplicar principios ágiles para:
- Analizar y estructurar historias de usuario según funcionalidades reales del sistema.
- Estimar el esfuerzo de desarrollo mediante técnicas colaborativas (Planning Poker, Story Points).
- Planificar un Sprint básico alineado con la capacidad del equipo.

---

## 🧠 ¿Por qué se organizó así?

Durante el análisis del documento original con las historias de usuario, se detectó que varias estaban agrupadas bajo categorías amplias como “Gestión de usuarios” o “Catálogo”. Para mejorar la trazabilidad y claridad del backlog, se realizó una reestructuración con base en buenas prácticas ágiles:

### ✔️ Lo que se hizo:

1. **División de épicas en bloques funcionales más específicos.**
   - “Gestión de usuarios” se dividió en:  
     a) Registro y autenticación  
     b) Administración de usuarios
   - “Catálogo y carrito” se dividió en:  
     a) Visualización del catálogo  
     b) Gestión del carrito

2. **Asignación de nombres breves y significativos** a cada historia de usuario.

3. **Redacción de criterios de aceptación claros y puntuales**, para facilitar el trabajo del equipo de desarrollo y validación.

Esta organización facilita la estimación, planificación, desarrollo, pruebas y seguimiento.

---

## 🔖 Estructura Funcional del Producto

El sistema fue descompuesto en 9 épicas funcionales, cada una con historias de usuario numeradas (HU01–HU25), un nombre representativo y criterios de aceptación específicos.

### 📚 Épicas y sus Historias de Usuario

1. **Registro y Autenticación de Usuarios**
   - HU01 – Registro de cliente  
   - HU02 – Inicio de sesión  
   - HU03 – Recuperación de contraseña

2. **Administración de Usuarios**
   - HU04 – Eliminación de usuario  
   - HU05 – Actualización de usuario

3. **Visualización del Catálogo**
   - HU06 – Visualización de catálogo  
   - HU07 – Filtro de productos

4. **Gestión del Carrito de Compras**
   - HU08 – Agregar al carrito  
   - HU09 – Modificar cantidad del carrito  
   - HU10 – Recomendaciones personalizadas

5. **Proceso de Compra**
   - HU11 – Selección de método de pago  
   - HU12 – Resumen de pedido  
   - HU13 – Confirmación de compra por correo

6. **Envío y Seguimiento de Pedidos**
   - HU14 – Registro de dirección de envío  
   - HU15 – Consulta de estado de pedido  
   - HU16 – Gestión de pedidos por administrador

7. **Gestión del Catálogo de Productos**
   - HU17 – Agregar producto al catálogo  
   - HU18 – Eliminar producto del catálogo  
   - HU19 – Actualizar producto del catálogo  
   - HU20 – Gestión de inventario  
   - HU21 – Subida de imágenes y fichas técnicas

8. **Reportes y Analítica**
   - HU22 – Visualización de estadísticas de ventas  
   - HU23 – Generación de reportes

9. **Seguridad y Control de Acceso**
   - HU24 – Protección de datos del usuario  
   - HU25 – Asignación de roles y permisos

> Cada historia de usuario tiene criterios de aceptación redactados con viñetas, accesibles en el archivo `criterios_aceptacion.txt`.

---

## ✅ Criterios de Aceptación

Se definieron criterios de aceptación para cada historia de usuario.  
Por ejemplo, para la historia **HU01 – Registro de cliente**:

- El sistema permite ingresar nombre, correo y contraseña.  
- Se valida que el correo electrónico no esté registrado previamente.  
- Se envía un mensaje de confirmación tras el registro exitoso.

> Consulta el archivo `criterios_aceptacion.txt` para ver todos los criterios por historia.

---

## 🛠️ Técnicas de Estimación Utilizadas

### 🔢 1. **Planning Poker** 🃏

Técnica grupal basada en cartas numéricas tipo Fibonacci (1, 2, 3, 5, 8, 13, 20...).  
Se usó para estimar historias como “Enviar confirmación por correo” o “Filtrar paneles por tipo”.

**Ventajas:**
- Fomenta el diálogo y consenso.
- Reduce el sesgo de opinión.
- Alinea la percepción del esfuerzo entre todos.

---

### 👕 2. **T-Shirt Sizing**

Clasificación de tamaño relativo con tallas (XS, S, M, L, XL).

**Usos:**
- En fases tempranas.
- Cuando hay muchas historias para estimar rápidamente.

**Ejemplo:**
- “Iniciar sesión” → Talla S  
- “Generar reportes” → Talla L o XL

---

### 📈 3. **Story Points**

Unidad relativa que mide el esfuerzo general, considerando:

- Complejidad técnica
- Incertidumbre
- Volumen de trabajo

**Escala usada:** 1, 2, 3, 5, 8, 13, 20

**Ejemplos:**
- “Registrar cliente” → 3 puntos  
- “Recomendaciones inteligentes” → 8 puntos  
- “Protección de datos” → 13 puntos (alta incertidumbre)

---

## 📊 Simulación de Sprint

- 👥 **Equipo**: 4 personas  
- ⏱️ **Horas efectivas por día**: 3  
- 📆 **Duración**: 10 días hábiles  
- 🔢 **Capacidad total**: 4 × 10 × 3 = **120 horas**  
- 🧮 **Velocidad estimada**: 15 Story Points

Se seleccionaron historias de usuario que sumaban 15 puntos, priorizadas según valor funcional y técnica de estimación, y se asignaron equitativamente a los integrantes.

---

## 📂 Archivos Incluidos

- `README.md`: Este documento explicativo completo.  
- `criterios_aceptacion.txt`: Criterios de aceptación para cada HU.  
- `Historias_de_Usuario.xlsx`: Backlog funcional con épicas, historias, criterios, prioridades, estado y responsables.  
- `SprintBacklog.xlsx`: Planificación del sprint con esfuerzo, puntos e integrantes.  
- `HistoriasClasificadas.xlsx`: Estimaciones por Planning Poker, T-Shirt Sizing y Story Points.

---

## ✍️ Autor

**Johan Castillo** – Estudiante en formación de desarrollo ágil y SCRUM  
👩‍🏫 Instructora guía: Carolina Forero – SENA

---

## 📚 Referencias

- Estimación de Historias de Usuario – Presentación PDF SENA  
- Videos oficiales de formación en SCRUM – SENA  
- [scrumpoker.online](https://scrumpoker.online/) – Herramienta para estimación grupal
