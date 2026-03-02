# 📱 Manual de Instalación — Mis Finanzas

Guía completa para instalar y usar la app **Mis Finanzas** en tu celular.
Sin tiendas de aplicaciones. Sin registro. Sin servidores.

---

## Requisitos

| Plataforma | Navegador recomendado |
|---|---|
| Android | Chrome (versión 80 o superior) |
| iPhone / iPad | Safari (versión 14 o superior) |

Solo necesitás internet para la primera instalación. Después funciona sin conexión.

---

## Paso 1 — Abrir la app

Desde tu celular, ingresá a:

```
https://richardyag.github.io/app-finanzas-personales/finanzas.html
```

Podés escanear este link o escribirlo directamente en el navegador.

---

## Paso 2 — Instalar en Android (Chrome)

1. Tocá el menú **⋮** (tres puntos) en la esquina superior derecha
2. Seleccioná **"Añadir a pantalla de inicio"**

   ```
   Menú Chrome
   ├── Nueva pestaña
   ├── Nueva pestaña de incógnito
   ├── Historial
   ├── ...
   └── ► Añadir a pantalla de inicio   ← acá
   ```

3. Aparecerá un cuadro con el nombre **"Mis Finanzas"** — tocá **Añadir**
4. El ícono aparece en tu pantalla de inicio como cualquier otra app

> En algunos modelos Android, Chrome muestra primero un banner en la parte inferior de la pantalla que dice **"Agregar Mis Finanzas a la pantalla de inicio"**. Tocalo directamente.

---

## Paso 2 — Instalar en iPhone / iPad (Safari)

> **Importante:** tiene que ser Safari. Chrome en iOS no permite esta instalación.

1. Tocá el botón **Compartir** en la barra inferior de Safari
   (es un cuadrado con una flecha hacia arriba ↑)
2. Deslizá el menú hacia abajo y tocá **"En pantalla de inicio"**

   ```
   Opciones de Safari
   ├── Copiar enlace
   ├── Añadir a marcadores
   ├── Añadir a favoritos
   ├── ...
   └── ► En pantalla de inicio   ← acá
   ```

3. Tocá **Agregar** en la esquina superior derecha
4. La app aparece en tu pantalla de inicio con el nombre **"Mis Finanzas"**

---

## Funcionamiento offline

Una vez instalada, la app funciona **completamente sin internet**.

Tus datos se guardan en dos lugares del dispositivo de forma automática:
- **localStorage**: almacenamiento principal del navegador
- **IndexedDB**: copia de seguridad automática que protege tus datos si el navegador limpia el caché

La única excepción son las fuentes tipográficas (Google Fonts). Si usás la app sin internet, los textos se ven con fuentes del sistema, igual de legibles.

---

## Actualizar la app

Cuando haya una nueva versión:

1. Abrí el link original en el navegador (no el ícono de la pantalla de inicio)
2. Forzá la recarga: en Android presioná el ícono ↺, en iPhone mantenés el botón ↺
3. Cerrá la pestaña y abrí la app desde el ícono — ya estará actualizada

---

## Qué puede hacer la app

### Movimientos
- Registrar **ingresos fijos** (sueldo, jubilación, renta) y **variables** (freelance, inversión, bonus)
- Registrar **gastos fijos** (alquiler, servicios, cuotas) y **variables** (supermercado, comidas, ocio)
- **Cambio de moneda** entre ARS, USD y EUR con tipo de cambio calculado automáticamente
- Filtrar por tipo: Todos / Ingresos / Gastos
- **Editar** cualquier movimiento tocando el botón ✎
- Agregar **notas** opcionales a cada movimiento
- **Exportar** el mes a CSV con el botón ⬇ del encabezado

### 💰 Presupuestos
- Asignar límites mensuales por categoría (Alquiler, Comidas, Ocio, etc.)
- Ver barra de progreso por categoría con colores: verde / amarillo / rojo
- Resumen general de lo presupuestado vs gastado en el mes

### 🔮 Proyección de cierre de mes
- El balance muestra automáticamente cuánto quedará a fin de mes según tu ritmo de gasto actual
- También muestra tu tasa de ahorro del mes en tiempo real

### 📊 Estadísticas
- Gráfico de barras **mes a mes** (12 meses del año seleccionado)
- Gráfico de barras **año a año** (tendencia histórica)
- Gráfico de **dona por categoría** para ver en qué gastás más, mes a mes

### 🏦 Patrimonio
- **Cuentas líquidas**: banco, efectivo, billetera digital, bróker, cripto — con saldo actualizado automáticamente cada vez que registrás un ingreso o gasto
- **Activos**: auto, casa, lote, departamento, tecnología, inversión, cripto
- **Pasivos**: préstamos, hipoteca, tarjeta, cuotas
- **Fondos de ahorro**: metas con barra de progreso; celebración al llegar al 100%

### 🔔 Cuentas programadas
- Configurar **cobros** (sueldo, alquiler cobrado) y **pagos** (luz, gas, internet) con día de vencimiento
- Alertas automáticas días antes del vencimiento
- Al registrar el pago real, se actualiza el monto esperado para el mes siguiente
- Vista de **previsiones** en meses futuros

---

## Copia de seguridad de tus datos

La app guarda tus datos automáticamente en el dispositivo. Para mayor seguridad:

**Opción 1 — Exportar CSV**
Tocá el botón ⬇ junto al nombre del mes para descargar todos los movimientos como archivo `.csv`. Guardalo en la nube (Drive, iCloud, etc.).

**Opción 2 — No limpiar datos del navegador**
Evitá usar "Limpiar caché" o "Borrar datos del sitio" en la configuración del navegador. La app tiene una copia de seguridad automática en IndexedDB, pero si limpiás completamente el almacenamiento del navegador ambas copias se borran.

---

## Desinstalar

### Android
- Mantenés presionado el ícono → "Desinstalar" o arrastrarlo a la papelera

### iPhone
- Mantenés presionado el ícono → "Eliminar app" → "Eliminar de pantalla de inicio"

> Desinstalar la app **no borra los datos** guardados en el navegador. Si reinstalás la app y usás el mismo navegador, tus datos siguen ahí.

---

## Preguntas frecuentes

**¿Mis datos se sincronizan entre dispositivos?**
No. Cada dispositivo guarda sus datos localmente. Para pasar datos a otro celular, exportá el CSV desde el dispositivo original e ingresá los datos manualmente en el nuevo.

**¿Puedo perder mis datos?**
Solo si limpiás manualmente los datos del navegador o restablecés el celular de fábrica. La app usa dos capas de almacenamiento local (localStorage + IndexedDB) para mayor resiliencia.

**¿Funciona en modo avión?**
Sí, completamente. Una vez abierta por primera vez, no necesita internet para nada.

**¿Es segura? ¿Quién ve mis datos?**
Nadie. Los datos nunca salen del dispositivo. No hay servidor, no hay cuenta, no hay telemetría.

**¿Por qué no está en Google Play o App Store?**
Las PWA (Progressive Web Apps) se instalan directamente desde el navegador, sin pasar por tiendas. Es más simple, más privado y sin actualizaciones forzadas.

**¿Puedo usarla en la computadora?**
Sí. Abrí el link en Chrome de escritorio. También se puede instalar como app de escritorio desde el ícono que aparece en la barra de direcciones de Chrome (⊕).

---

## Información técnica

| Elemento | Detalle |
|---|---|
| Tipo | Progressive Web App (PWA) |
| Tecnología | HTML5 + CSS3 + JavaScript puro |
| Almacenamiento | localStorage + IndexedDB (automático) |
| Gráficos | Chart.js 4 (CDN) |
| Fuentes | Google Fonts: Fraunces + DM Sans |
| Dependencias externas | Ninguna (solo fuentes y gráficos vía CDN) |
| Código fuente | https://github.com/richardyag/app-finanzas-personales |
| Licencia | MIT |
