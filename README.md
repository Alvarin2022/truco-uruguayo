# 🃏 Truco Uruguayo — Anotador Oficial

> Anotador digital para el Truco Uruguayo. Palitos, historial, ranking y reglamento completo. Gratis, sin publicidad, hecho con orgullo oriental.

**🌐 Jugá ahora:** [trucouruguayo.netlify.app](https://trucouruguayo.netlify.app)

---

## ✨ Funcionalidades

- **Anotador** con palitos en forma de cuadrado (grupos de 5)
- **Malas y buenas** bien diferenciadas (15+15 o 20+20)
- **Reloj de partida** con pausa y reset
- **Partido a 30 o 40 puntos** a elección
- **Nombres de equipos** editables antes de cada partida
- **Abandono por Falta Envido o Contraflor** con registro del motivo
- **Historial** de partidas con duración y resultado
- **Ranking** de equipos por porcentaje de victorias
- **Reglamento completo** con buscador integrado
- **Funciona sin internet** una vez instalada
- **Instalable** en Android e iOS como app nativa (PWA)

---

## 📱 Cómo instalar la app

### Android (Chrome)

1. Abrí [trucouruguayo.netlify.app](https://trucouruguayo.netlify.app) desde **Google Chrome**
2. Tocá los **tres puntitos** (⋮) arriba a la derecha
3. Seleccioná **"Agregar a pantalla de inicio"**
4. Confirmá tocando **"Agregar"**

La app aparece en tu pantalla de inicio con el ícono del escudo uruguayo. Se abre sin barras del navegador, como una app nativa.

> **Alternativa:** Chrome puede mostrar automáticamente un banner en la parte inferior de la pantalla con la opción de instalar. Si aparece, tocá **"Instalar"** directamente.

---

### iPhone / iPad (Safari)

> ⚠️ En iOS la instalación funciona **únicamente desde Safari**. Chrome y otros navegadores en iOS no permiten instalar PWAs.

1. Abrí [trucouruguayo.netlify.app](https://trucouruguayo.netlify.app) desde **Safari**
2. Tocá el botón de **compartir** — el ícono de cuadrado con flecha hacia arriba (↑) en la barra inferior
3. Deslizá hacia abajo en el menú y tocá **"Agregar a pantalla de inicio"**
4. Editá el nombre si querés (por defecto aparece "Truco Uruguayo") y tocá **"Agregar"**

La app queda en tu pantalla de inicio y se abre en pantalla completa sin la interfaz de Safari.

> **Nota iOS:** Algunas funciones offline pueden ser más limitadas que en Android, pero el anotador funciona correctamente en ambas plataformas.

---

## 🎮 Cómo usar el anotador

1. Tocá **"+ Nueva"** para iniciar una partida
2. Escribí los nombres de ambos equipos
3. Elegí si jugás a **30 o 40 puntos**
4. Tocá **"Jugar"** — el reloj arranca automáticamente
5. Usá **"+ Punto"** para sumar y **"−"** para corregir
6. Si un equipo abandona por Falta Envido o Contraflor, tocá el botón correspondiente en su tablero
7. Al llegar al puntaje máximo, la partida se guarda automáticamente en el historial

---

## 📋 Reglamento

La app incluye un reglamento completo del Truco Uruguayo con buscador. Accedé desde la pestaña **"Reglamento"** para consultar cualquier regla durante la partida:

- La muestra y las piezas
- Jerarquía de cartas
- El truco y sus apuestas (Truco / Retruco / Vale 4)
- El envido, Real Envido y Falta Envido
- La Flor y la Contraflor
- Las señas entre compañeros
- Historia del Truco Uruguayo
- Y más...

---

## 🛠️ Tecnologías

- **HTML5 / CSS3 / JavaScript** — sin frameworks, sin dependencias
- **PWA** (Progressive Web App) — instalable y funciona offline
- **localStorage** — historial y ranking guardados en el dispositivo
- **Service Worker** — caché para uso sin conexión
- **GitHub** — control de versiones
- **Netlify** — hosting gratuito con deploy automático

---

## 🚀 Deploy automático

Este proyecto usa **Netlify** conectado a GitHub. Cada vez que se hace un `push` a la rama `main`, el sitio se actualiza automáticamente en [trucouruguayo.netlify.app](https://trucouruguayo.netlify.app) en menos de un minuto.

---

## 📁 Estructura del proyecto

```
truco-uruguayo/
├── index.html       # App completa (anotador, historial, ranking, reglamento)
├── manifest.json    # Configuración PWA (nombre, íconos, colores)
├── sw.js            # Service Worker para funcionamiento offline
├── icon-192.png     # Ícono de la app (pantalla de inicio)
├── icon-512.png     # Ícono de la app (alta resolución)
└── README.md        # Este archivo
```

---

## 🗺️ Roadmap

- [x] Anotador con palitos en cuadrado
- [x] Malas y buenas diferenciadas
- [x] Reloj de partida
- [x] Partido a 30 o 40 puntos
- [x] Nombres editables por partida
- [x] Abandono por Falta Envido / Contraflor
- [x] Historial local de partidas
- [x] Ranking por porcentaje de victorias
- [x] Reglamento con buscador
- [x] PWA instalable en Android e iOS
- [ ] Login con usuario y contraseña
- [ ] Historial sincronizado entre dispositivos
- [ ] Estadísticas individuales por usuario
- [ ] Formato de torneo

---

## 🤝 Contribuciones

¿Encontraste un bug o tenés una sugerencia? Abrí un **Issue** en GitHub o contactanos directamente. La app está en desarrollo activo y el feedback de los usuarios es bienvenido.

---

*Hecho con orgullo oriental 🇺🇾 — Uruguay*
