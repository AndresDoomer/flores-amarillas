# 🌻 Flores Amarillas — Una Carta Especial 💛

Un detalle interactivo y animado para regalar flores amarillas virtuales, con música de fondo, animaciones de apertura de sobre, efectos visuales de fuegos artificiales, pétalos dorados y una carta con dedicatoria especial.

✨ **Demo en Vivo:** [https://andresdoomer.github.io/flores-amarillas/](https://andresdoomer.github.io/flores-amarillas/)

---

## 📸 Vista Previa y Experiencia

1. **Sobre Interactivo:** Al entrar, se muestra un elegante sobre sellado con un corazón brillante y un botón pulsante *"Toca para abrir 💌"*.
2. **Apertura y Animación:** Al presionar el sobre:
   - Se reproduce automáticamente la canción **"Cuéntame" de Equilivre** empezando directamente en el coro más emocionante (1:05).
   - Estallan fuegos artificiales y chispas doradas (`canvas-confetti`).
   - Una suave lluvia de pétalos amarillos y destellos cae continuamente de fondo.
3. **Carta y Ramillete:**
   - La carta emerge con un mensaje emotivo lleno de cariño.
   - Fotografía del ramo de flores amarillas con destellos mágicos.
   - Dedicatoria y firma especial: *"Atentamente, Andrés 🌻"*.
4. **Reproductor de Música Integrado:**
   - Control en la esquina inferior derecha para pausar o reanudar la música en cualquier momento.
   - Ecualizador animado mientras la canción se reproduce.
   - Bucle automático para volver a la mejor parte de la canción cuando finalice.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & Vanilla CSS3:** Diseño responsivo (optimizado para celulares, tablets y computadoras), efectos de desenfoque (*glassmorphism*), sombras suaves y animaciones fluidas con `@keyframes`.
- **JavaScript Moderno:** Gestión de estados de apertura, interacción táctil y sincronización de eventos.
- **YouTube IFrame Player API:** Reproducción oculta y optimizada de audio de alta fidelidad con control de tiempo de inicio (segundo 65) y bucle inteligente.
- **Canvas Confetti:** Efecto visual de celebración con partículas personalizadas en tonos amarillos, dorados y blancos.
- **Google Fonts:** Tipografías *Outfit*, *Caveat* y *Dancing Script* para darle calidez y estilo manuscrito a la carta.

---

## 🚀 Despliegue en GitHub Pages

Este proyecto está configurado para desplegarse automáticamente con **GitHub Pages**:

1. Los archivos principales son:
   - `index.html`: Toda la estructura, diseño y lógica interactiva.
   - `flores.jpg`: Fotografía del ramo de flores amarillas.
2. Cada cambio en la rama `master` actualiza automáticamente el sitio web en cuestión de segundos.

---

## 🌐 Cómo usar una URL Personalizada

En GitHub existen dos formas de personalizar tu enlace:

### 1. Cambiar el nombre del repositorio (Gratis e Inmediato)
El enlace actual es:
```
https://andresdoomer.github.io/flores-amarillas/
```
Si renombras el repositorio en GitHub (por ejemplo, a `para-ti`, `flores`, `te-amo`, etc.):
- La nueva URL será: `https://andresdoomer.github.io/tu-nuevo-nombre/`
- O si renombras el repositorio exactamente como `andresdoomer.github.io`, la URL quedará en la raíz: `https://andresdoomer.github.io/`

### 2. Usar un Dominio Propio (ej. `midominio.com` o `florespara.ti`)
Si tienes o compras un dominio personalizado:
1. Ve a tu repositorio en GitHub: **Settings** > **Pages**.
2. En la sección **Custom domain**, escribe tu dominio (por ejemplo: `floresparaella.com`).
3. Haz clic en **Save** y activa la casilla **Enforce HTTPS**.
4. En tu proveedor de dominio (GoDaddy, Namecheap, Cloudflare, etc.), agrega los registros DNS:
   - Tipo `CNAME` apuntando `www` a `andresdoomer.github.io`.
   - O tipo `A` apuntando a las IPs de GitHub Pages:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```

---

Hecho con 💛 por **AndresDoomer**
