# Proyecto Ecoenergixx – Estimación y Planificación Ágil en SCRUM ☀️

Este repositorio contiene los artefactos creados como parte de la simulación de planificación de sprints SCRUM basada en historias de usuario relacionadas con un sistema de ventas de paneles solares.

---

## 📌 Objetivo

Aplicar técnicas ágiles para:
- Estimar historias de usuario usando métodos colaborativos.
- Evaluar el esfuerzo de cada historia en función de criterios objetivos.
- Planificar un sprint básico adaptado a la capacidad real del equipo.

---

## 🛠️ Técnicas de Estimación Utilizadas

### 🔢 1. **Planning Poker** 🃏

Técnica de estimación grupal basada en el consenso.  
Se usa una baraja con la secuencia de Fibonacci (1, 2, 3, 5, 8, 13, 20...) para asignar puntos de historia.

**¿Cómo funciona?**
1. Se presenta una historia de usuario.
2. Cada miembro del equipo elige en secreto una carta con su estimación.
3. Todos revelan sus cartas al mismo tiempo.
4. Si hay diferencias significativas, se discuten hasta llegar a consenso.

**Ventajas:**
- Fomenta el diálogo.
- Reduce el sesgo de opinión.
- Alinea la percepción del esfuerzo entre todos.

**Aplicación en Ecoenergixx:**  
Se usó para estimar historias como “Enviar confirmación por correo” o “Filtrar paneles por tipo”, donde fue necesario discutir incertidumbre o dependencias técnicas.

---

### 👕 2. **T-Shirt Sizing**

Método visual y rápido que clasifica historias según su tamaño relativo usando tallas: XS, S, M, L, XL.

**¿Cuándo usarla?**
- En fases tempranas del proyecto.
- Cuando hay muchas historias que necesitan ser priorizadas rápidamente.
- Para una visión general antes de afinar con Planning Poker.

**Ventajas:**
- Fácil de aplicar.
- No requiere cálculos.
- Útil para comparar muchas historias al mismo tiempo.

**Aplicación en Ecoenergixx:**  
Historias como “Iniciar sesión” o “Agregar productos al carrito” fueron clasificadas como **talla S**, mientras que “Gestionar inventario” o “Generar reportes” fueron **talla L o XL**.

---

### 📈 3. **Story Points**

Es una unidad relativa de medida que representa el esfuerzo total necesario para completar una historia. No equivale a horas, sino que se basa en:

- **Complejidad** técnica.
- **Incertidumbre** en los requisitos o en la implementación.
- **Volumen de trabajo** o cantidad de tareas involucradas.

**Escala usada:** Fibonacci (1, 2, 3, 5, 8, 13, 20...)

**Aplicación en Ecoenergixx:**  
Cada historia fue evaluada con estos 3 criterios, y se asignaron puntos basados en una historia de referencia. Por ejemplo:
- “Registrar cliente” = 3 puntos.
- “Recomendaciones inteligentes” = 8 puntos.
- “Seguridad de datos” = 13 puntos (alta incertidumbre).

---

## 📊 Simulación de Sprint

- 👥 **Equipo**: 4 personas
- ⏱️ **Horas efectivas diarias**: 3
- 📆 **Duración del sprint**: 10 días hábiles
- 🔢 **Capacidad total**: 4 × 10 × 3 = **120 horas**
- 🧮 **Velocidad estimada**: 15 Story Points

Se seleccionaron historias de usuario con un total de 15 puntos y se distribuyeron entre los participantes de forma balanceada.

---

## 📂 Archivos incluidos

- `SprintBacklog.xlsx`: Sprint planificado con responsables, puntos y estados.
- `HistoriasClasificadas.xlsx`: Historias con sus respectivas técnicas, puntos y justificación.
- `README.md`: Este documento explicativo.

---


---

## ✍️ Autor

**Johan Castillo** – Estudiante en formación de desarrollo ágil y SCRUM  
👩‍🏫 Instructora guía: Carolina Forero – SENA

---

## 📚 Referencias

- Estimación de Historias de Usuario – Presentación PDF SENA
- Videos oficiales de formación en SCRUM – SENA
- [scrumpoker.online](https://scrumpoker.online/)
