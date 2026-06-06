# Documento de Requisitos de Producto Mínimo Viable (MVP)

## 1. Resumen del Producto

**Nombre provisional:** GymPay

**Problema**

Los usuarios del gimnasio deben acudir presencialmente para realizar o renovar sus pagos mensuales, lo que genera molestias, pérdida de tiempo y retrasos en las renovaciones.

**Solución MVP**

Una aplicación móvil y web sencilla que permita a los usuarios registrar un método de pago, contratar una suscripción mensual y renovar automáticamente su membresía sin necesidad de acudir al gimnasio.

---

## 2. Objetivo del MVP

Permitir que los miembros del gimnasio gestionen y paguen su suscripción mensual de forma digital, segura y automática.

---

## 3. Usuarios Objetivo

### Cliente del gimnasio

Persona que desea:

* Pagar su membresía sin desplazarse.
* Mantener su suscripción activa automáticamente.
* Consultar el estado de sus pagos.

### Administrador del gimnasio

Persona responsable de:

* Ver usuarios activos.
* Ver pagos realizados.
* Gestionar membresías.

---

## 4. Funcionalidades Principales (MVP)

### 1. Registro e inicio de sesión

El usuario puede:

* Crear una cuenta.
* Iniciar sesión.
* Recuperar contraseña.

**Prioridad:** Crítica

---

### 2. Gestión de suscripción

El usuario puede:

* Ver el plan disponible.
* Activar una suscripción mensual.
* Consultar estado de su membresía.

**Prioridad:** Crítica

---

### 3. Registro de método de pago

El usuario puede:

* Registrar tarjeta de crédito o débito mediante una pasarela de pago segura.
* Actualizar o eliminar el método de pago.

**Prioridad:** Crítica

---

### 4. Cobro recurrente mensual

El sistema puede:

* Realizar el cobro automático mensual.
* Renovar la membresía tras un pago exitoso.
* Marcar la membresía como pendiente si el cobro falla.

**Prioridad:** Crítica

---

### 5. Historial de pagos

El usuario puede:

* Consultar pagos realizados.
* Ver fechas y montos cobrados.

**Prioridad:** Alta

---

### 6. Panel administrativo básico

El administrador puede:

* Ver miembros activos.
* Ver miembros con pagos pendientes.
* Consultar historial de pagos.

**Prioridad:** Alta

---

## 5. Funcionalidades Fuera del Alcance del MVP

Para evitar complejidad innecesaria, NO se incluirán inicialmente:

* Reserva de clases.
* Rutinas de entrenamiento.
* Seguimiento de ejercicios.
* Chat con entrenadores.
* Integración con wearables.
* Programa de recompensas.
* Múltiples planes complejos.
* Facturación avanzada.
* Aplicación para múltiples gimnasios.

---

## 6. Flujo Principal de Usuario

### Alta de suscripción

1. Usuario crea una cuenta.
2. Inicia sesión.
3. Visualiza el plan mensual disponible.
4. Registra un método de pago.
5. Confirma la suscripción.
6. El sistema activa la membresía.
7. Cada mes se ejecuta el cobro automático.
8. El usuario puede consultar el estado de su membresía y pagos.

---

## 7. Requisitos No Funcionales

### Seguridad

* Comunicación cifrada mediante HTTPS.
* Gestión segura de autenticación.
* Los datos de tarjetas no se almacenan directamente en la aplicación.

### Disponibilidad

* Aplicación accesible 24/7.

### Usabilidad

* Proceso de suscripción completado en menos de 3 minutos.

---

## 8. Tecnologías Sugeridas

Manteniendo simplicidad y flexibilidad:

### Frontend

* React

### Backend

* Node.js o Flask

### Base de Datos

* PostgreSQL

### Pagos Recurrentes

* Stripe (suscripciones automáticas)

### Despliegue

* Vercel (frontend)
* Render o Railway (backend)

---

## 9. Métrica de Éxito del MVP

### Métrica Principal

Al menos el 60% de los miembros activos del gimnasio realizan sus pagos mediante la aplicación durante los primeros 3 meses.

### Métricas Secundarias

* Reducción del 80% de pagos presenciales.
* Tasa de éxito de cobros superior al 95%.
* Tiempo promedio de activación de suscripción menor a 3 minutos.
* Menos del 5% de incidencias relacionadas con pagos.

---

## 10. Definición de MVP Exitoso

El MVP será considerado exitoso si los usuarios pueden:

1. Registrarse.
2. Añadir un método de pago.
3. Activar una suscripción mensual.
4. Renovarla automáticamente.
5. Consultar el estado de su membresía y pagos.

Sin necesidad de acudir físicamente al gimnasio para realizar pagos.
