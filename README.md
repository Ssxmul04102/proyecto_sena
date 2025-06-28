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

## ✅ Objetivos Centrales por Grupo de Historias

### 📦 1. **Flujo Básico de Compra (Cliente)**
**Historias incluidas:**
- HU02 – Inicio de sesión  
- HU08 – Agregar productos al carrito  
- HU09 – Modificar cantidad  
- HU14 – Registro de dirección de envío  

**🎯 Objetivo:**  
**Permitir al cliente gestionar su proceso de compra de forma personalizada y eficiente, desde el acceso a su cuenta hasta la preparación del pedido para su envío.**

**🧠 ¿Por qué?**  
Estas historias representan el flujo inicial de compra. Desde ingresar al sistema, seleccionar productos, ajustarlos y preparar el checkout.

---

### 📦 2. **Ciclo Completo de Compra y Administración (Cliente/Admin)**
**Historias incluidas:**
- HU01 – Registro de cliente  
- HU03 – Recuperación de contraseña  
- HU06 – Ver catálogo  
- HU11 – Selección de método de pago  
- HU12 – Resumen de pedido  
- HU13 – Confirmación por correo  
- HU15 – Consulta de estado del pedido  
- HU18 – Eliminar producto (admin)  
- HU16 – Gestión de pedidos (admin)

**🎯 Objetivo:**  
**Facilitar y administrar una experiencia de compra completa, segura y eficiente de paneles solares, permitiendo a los clientes registrarse, gestionar sus pedidos y pagos, y a los administradores mantener actualizado el catálogo y supervisar las ventas.**

**🧠 ¿Por qué?**  
Este grupo extiende el flujo hasta la posventa y asegura que los administradores puedan sostener el funcionamiento del sistema.

---

### 📦 3. **Gestión Avanzada y Personalización (Cliente/Admin)**
**Historias incluidas:**
- HU04 – Eliminar usuario  
- HU05 – Actualizar usuario  
- HU07 – Filtro de productos  
- HU10 – Recomendaciones  
- HU17 – Agregar producto  
- HU19 – Actualizar producto  
- HU20 – Gestionar inventario  
- HU21 – Subida de fichas técnicas  
- HU22 – Panel de estadísticas  
- HU23 – Reportes  
- HU24 – Protección de datos  
- HU25 – Asignación de roles

**🎯 Objetivo:**  
**Garantizar una gestión eficiente, segura y personalizada del sistema y del catálogo de productos, permitiendo a los administradores controlar usuarios, inventario y datos, y a los clientes encontrar fácilmente los paneles más adecuados a sus necesidades.**

**🧠 ¿Por qué?**  
Este conjunto potencia la personalización del catálogo para el cliente y fortalece la administración del sistema en un entorno seguro y escalable.

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
- `SprintBacklog.xlsx`:
