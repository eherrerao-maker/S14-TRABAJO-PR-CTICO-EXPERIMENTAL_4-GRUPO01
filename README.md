# S14-TRABAJO-PR-CTICO-EXPERIMENTAL_4-GRUPO01
Caso de Estudio: Simulador de Cajero Bancario con Vectores
# Simulador de Cajero Bancario (ATM) — README

## Descripción General
Este proyecto corresponde al caso de estudio **"Simulador de Cajero Bancario con Vectores"**, desarrollado en JavaScript utilizando **estructuras `for`**.

El simulador permite registrar clientes, iniciar sesión, realizar retiros, depósitos, pagos de servicios y consultar saldo, integrando todas las operaciones con el diseño HTML proporcionado.

---

## 🧩 Funcionalidades del Sistema

### ✔ Registro de Clientes
- Almacena datos en un vector de clientes.
- Valida DNI (6 a 10 dígitos numéricos).
- Verifica DNI duplicado.
- Contraseña/PIN de 4 dígitos.

### ✔ Inicio de Sesión
- Validación de credenciales.
- Carga del cliente a la sesión activa.
- Muestra el nombre del usuario en la interfaz.

### ✔ Operaciones Bancarias
#### Retiros
- Montos predefinidos y personalizados.
- Validación de múltiplos de $10.
- Verificación de saldo suficiente.
- Registro del movimiento.

#### Depósitos
- Montos predefinidos y personalizados.
- Actualización de saldo en tiempo real.
- Registro del movimiento.

#### Pagos de Servicios
- Ingreso de servicio y monto.
- Validación de saldo.
- Registro del pago.

### ✔ Consulta de Saldo y Movimientos
- Muestra saldo actualizado.
- Despliega los últimos 5 movimientos del cliente.

---

## Estructura de Datos

###  Vector de Clientes
Cada cliente se almacena así:

```js
[dni, nombreCompleto, saldo, password]
```

---

### Trabajo experimental desarrollado por el **Grupo 1**  
- Angie Isabel Irrazaba Calero
- Elian Oswaldo Herrera Olmedo
- Sabino Andrés Naranjo Naranjo
- María Méndez 
- Angelica Suarez
- Jordy Moran

Carrera: Ingeniería en Software — Segundo Semestre C1

Asignatura: Técnicas de Programación  
Fecha: 16/11/2025  
Año lectivo: 2025