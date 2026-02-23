# 🏥 Sistema de Órdenes Médicas

Proyecto desarrollado para la materia Construcción de Software.

Este sistema permite crear órdenes médicas validando reglas de negocio clínicas, aplicando arquitectura limpia sin el uso de frameworks como Spring.

---

## 📌 Funcionalidades

- Crear órdenes médicas
- Agregar múltiples ítems a la orden
- Validaciones de negocio completas
- Menú interactivo por consola
- Manejo de excepciones personalizadas

---

## 🧱 Arquitectura

El proyecto está organizado por capas:

- **models** → Entidades del dominio
- **services** → Reglas de negocio
- **ports** → Interfaces
- **adapters** → Implementaciones
- **exceptions** → Manejo de errores

---

## 📋 Reglas de negocio implementadas

✔ Número de orden obligatorio  
✔ Número máximo de 6 caracteres  
✔ Número de orden único  
✔ La orden debe tener al menos un ítem  
✔ No se pueden mezclar ayudas diagnósticas con medicamentos o procedimientos  
✔ No se permiten ítems repetidos  
✔ El nombre del ítem es obligatorio  
✔ El nombre no puede ser solo números  
✔ El nombre debe tener mínimo 3 caracteres  
✔ El costo debe ser mayor a cero  
✔ La cantidad debe ser mayor a cero  
✔ Si el ítem requiere especialista, debe tener ID de especialista  

---

## ▶ Cómo ejecutar

1. Clonar el repositorio
2. Abrir en Visual Studio Code
3. Ejecutar la clase `Main`
4. Seguir el menú interactivo por consola

---

## 🛠 Tecnologías usadas

- Java
- Programación orientada a objetos
- Arquitectura por capas
- Git & GitHub

---

## 👨‍💻 Autor

Jhon Edwar Cardona Londoño 