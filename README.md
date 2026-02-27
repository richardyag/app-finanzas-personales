# 💰 Mis Finanzas — App de Control Personal

Una aplicación web progresiva (PWA) para gestionar tus finanzas personales desde el celular. Sin servidores, sin registros, sin internet requerido: todo se guarda localmente en tu dispositivo.

---

## Características

### Movimientos
- Registrá **ingresos fijos** (sueldo, renta, jubilación)
- Registrá **ingresos variables** (freelance, inversiones, bonus)
- Registrá **gastos fijos** (alquiler, servicios, cuotas, suscripciones)
- Registrá **gastos variables** (supermercado, comidas, ocio, ropa, salud, transporte)
- Filtrá por tipo: Todos / Ingresos / Gastos
- Eliminá movimientos con un toque

### Balance mensual
- Balance neto del mes en tiempo real
- Desglose de ingresos vs gastos
- **Barra de progreso** con código de color: verde / amarillo / rojo según cuánto gastaste respecto a lo que ingresó

### Cuentas recurrentes (🔔)
- Configurá tus cuentas periódicas: luz, gas, agua, internet, alquiler, tarjeta, etc.
- Definí el **día de vencimiento** y la **frecuencia** (mensual, bimestral, trimestral, semestral, anual)
- **Alertas automáticas**: se notifica N días antes del vencimiento
- Las cuentas se ordenan por urgencia: vencidas → próximas → al día → pagadas
- Al marcar como pagada, se registra automáticamente como gasto fijo del mes

### Navegación por mes
- Navegá hacia adelante y atrás entre meses
- Cada mes tiene sus propios movimientos almacenados

### Alertas
- Banner rojo si hay cuentas **vencidas**
- Banner amarillo si hay cuentas **próximas a vencer**

---

## Tecnología

| Elemento | Detalle |
|----------|---------|
| Lenguaje | HTML5 + CSS3 + JavaScript vanilla |
| Almacenamiento | `localStorage` (datos en el dispositivo) |
| Fuentes | Google Fonts: Fraunces + DM Sans |
| Sin dependencias | No requiere Node, npm ni frameworks |
| PWA-ready | Se puede instalar como app en el celular |

---

## Instalación en el celular

La app puede instalarse directamente desde el navegador, sin tiendas de aplicaciones.

### Android (Chrome)
1. Abrí el enlace de la app en Chrome
2. Tocá el menú ⋮ (tres puntos)
3. Seleccioná **"Añadir a pantalla de inicio"**
4. Tocá **Añadir** — aparecerá como app en tu pantalla

### iOS (Safari)
1. Abrí el enlace en Safari
2. Tocá el botón **Compartir** (cuadro con flecha hacia arriba)
3. Seleccioná **"En pantalla de inicio"**
4. Tocá **Agregar** — la app queda instalada

> Ver [INSTALL.md](INSTALL.md) para el manual completo con imágenes descriptivas.

---

## Uso rápido

1. **Abrir la app** desde el enlace de GitHub Pages o pantalla de inicio
2. **Agregar movimientos** con el botón `＋` al pie de la pantalla
3. **Configurar cuentas** yendo a la pestaña 🔔 Cuentas y tocando `＋`
4. **Navegar meses** con las flechas `‹` y `›` del encabezado

---

## Privacidad

- Todos los datos se almacenan **únicamente en tu dispositivo** usando `localStorage`
- No se envía ningún dato a servidores externos
- No requiere cuenta, login ni internet (excepto para cargar las fuentes de Google Fonts)

---

## Licencia

MIT — Libre para usar, modificar y compartir.
