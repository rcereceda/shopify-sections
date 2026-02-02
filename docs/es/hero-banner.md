# Sección Hero Banner - Guía de Uso

[🇺🇸 Read in English](../en/hero-banner.md) | 🇪🇸 Español

## 📋 Resumen

La sección Hero Banner es una sección de ancho completo y alto impacto, perfecta para páginas principales, landing pages y páginas de campaña. Soporta fondos de imagen y video con overlays personalizables y posicionamiento flexible de contenido.

## ✨ Características

- **Medios Flexibles**:

  - Fondo de imagen (recomendado: 1920x800px o mayor)
  - Fondo de video (formato MP4, opcional)
  - Fallback automático a imagen si no se provee video
  - Placeholder si no se selecciona ningún medio

- **Efectos de Imagen**:

  - **Parallax al hacer scroll**: Crea efecto de profundidad al desplazarse
  - **Movimiento ambiente**: Movimiento circular sutil cuando está inactivo
  - Ambos efectos pueden habilitarse/deshabilitarse independientemente
  - Respeta las preferencias de movimiento del usuario (accesibilidad)

- **Diseño Profesional** (Heroicons):

  - Heroicons limpios y modernos para mini badges
  - Consistente con la sección Trust Badges

- **Elementos de Contenido**:

  - Texto eyebrow (texto pequeño arriba del encabezado)
  - Encabezado principal (H1)
  - Subtítulo/descripción (richtext)
  - Hasta 2 botones CTA (primario + secundario)
  - Mini trust badges dinámicos (ilimitados vía bloques)

- **Personalización Completa**:

  - Control de color y opacidad del overlay
  - Personalización de color de texto
  - Posicionamiento vertical (arriba/centro/abajo)
  - Posicionamiento horizontal (izquierda/centro/derecha)
  - Alineación de texto (izquierda/centro/derecha)
  - Control de ancho máximo de contenido
  - Control de altura (móvil + escritorio)

- **Diseño Responsive**:
  - Optimizado para todos los tamaños de pantalla
  - Controles de altura separados para móvil y escritorio
  - Tamaños de texto se adaptan automáticamente
  - Botones amigables al tacto

## 🎨 Opciones de Personalización

### Ajustes de Medios

| Ajuste              | Tipo  | Descripción                                        |
| ------------------- | ----- | -------------------------------------------------- |
| **Imagen de Fondo** | Image | Imagen de fondo principal (1920x800px recomendado) |
| **URL de Video**    | URL   | URL de video MP4 opcional (ver nota abajo)         |

**Nota sobre URL de Video:**

- Sube tu video a **Shopify Files** (Configuración → Archivos), luego copia la URL generada
- O usa una URL de CDN (tu propio hosting, link directo de Vimeo, etc.)
- Shopify no soporta subir videos directamente a assets del tema (son muy grandes)
- Formato MP4 con codec H.264 recomendado, mantén bajo 10MB para rendimiento

### Efectos de Imagen

| Ajuste                            | Tipo     | Por Defecto | Descripción                                                              |
| --------------------------------- | -------- | ----------- | ------------------------------------------------------------------------ |
| **Habilitar Parallax al Scroll**  | Checkbox | Off         | Crea efecto de profundidad al hacer scroll (funciona mejor con imágenes) |
| **Habilitar Movimiento Ambiente** | Checkbox | Off         | Agrega movimiento circular sutil a la imagen cuando está inactiva        |

**Notas de Efectos:**

- **Parallax**: La imagen permanece fija mientras haces scroll, creando una ilusión de profundidad. Mejor para secciones hero en la parte superior de la página.
- **Movimiento Ambiente**: Una animación circular suave de 30 segundos que da vida a imágenes estáticas. Sutil y profesional. **Solo aplica a imágenes, no videos** (los videos ya tienen movimiento).
- Ambos efectos funcionan juntos o independientemente
- Los efectos se deshabilitan automáticamente para usuarios que prefieren movimiento reducido (accesibilidad)

### Ajustes de Overlay

| Ajuste               | Tipo  | Por Defecto | Descripción                  |
| -------------------- | ----- | ----------- | ---------------------------- |
| **Color de Overlay** | Color | #000000     | Color del overlay            |
| **Opacidad Overlay** | Range | 40%         | Opacidad del overlay (0-80%) |

### Ajustes de Contenido

| Ajuste          | Tipo     | Por Defecto              | Descripción                           |
| --------------- | -------- | ------------------------ | ------------------------------------- |
| **Eyebrow**     | Text     | "New Collection"         | Texto pequeño arriba del encabezado   |
| **Encabezado**  | Text     | "Welcome to Our Store"   | Encabezado principal (H1)             |
| **Subtítulo**   | Richtext | "Discover our latest..." | Texto de descripción                  |
| **Color Texto** | Color    | #ffffff                  | Color de todos los elementos de texto |

### Ajustes de Botones

| Ajuste               | Tipo | Por Defecto  | Descripción            |
| -------------------- | ---- | ------------ | ---------------------- |
| **Etiqueta Botón 1** | Text | "Shop Now"   | Texto botón primario   |
| **Link Botón 1**     | URL  | -            | URL botón primario     |
| **Etiqueta Botón 2** | Text | "Learn More" | Texto botón secundario |
| **Link Botón 2**     | URL  | -            | URL botón secundario   |

### Bloques de Prueba Social

El Hero Banner soporta **dos tipos de bloques** para prueba social:

#### 1. Trust Badges (Ilimitados)

Mini indicadores de confianza mostrados horizontalmente.

**Para agregar un badge:**

1. En el personalizador de temas, haz clic en "Agregar bloque"
2. Selecciona "Trust Badge"
3. Configura icono y texto
4. Arrastra para reordenar

**Ajustes de Bloque:**

| Ajuste    | Tipo   | Por Defecto     | Descripción |
| --------- | ------ | --------------- | ----------- |
| **Icono** | Select | Shipping        | Icono badge |
| **Texto** | Text   | "Free Shipping" | Texto badge |

**Iconos Disponibles**: Ninguno, Envío Gratis, Garantía de Devolución, Soporte 24/7, Calidad Premium, Devoluciones Fáciles

#### 2. Testimonial Destacado (Límite: 1)

Una reseña de cliente destacada con estrellas, cita, foto y nombre.

**Para agregar un testimonial:**

1. En el personalizador de temas, haz clic en "Agregar bloque"
2. Selecciona "Featured Testimonial"
3. Configura calificación, cita, foto e info del cliente

**Ajustes de Bloque:**

| Ajuste                     | Tipo         | Por Defecto      | Descripción                          |
| -------------------------- | ------------ | ---------------- | ------------------------------------ |
| **Calificación Estrellas** | Range (0-5)  | 5                | Número de estrellas (0 para ocultar) |
| **Cita Testimonial**       | Textarea     | (texto ejemplo)  | Texto de reseña del cliente          |
| **Foto Cliente**           | Image Picker | -                | Imagen perfil del cliente            |
| **Nombre Cliente**         | Text         | "Sarah Johnson"  | Nombre del cliente                   |
| **Título Cliente**         | Text         | "Verified Buyer" | Título o empresa                     |

**Beneficios de bloques:**

- ✅ Elige entre badges, testimonial o ambos
- ✅ Agrega badges ilimitados + 1 testimonial destacado
- ✅ Reordena con drag & drop
- ✅ Remueve bloques fácilmente
- ✅ No se necesitan cambios de código

### Ajustes de Layout

| Ajuste                  | Tipo   | Por Defecto | Descripción                                 |
| ----------------------- | ------ | ----------- | ------------------------------------------- |
| **Posición Vertical**   | Select | Center      | Arriba, Centro o Abajo                      |
| **Posición Horizontal** | Select | Center      | Izquierda, Centro o Derecha                 |
| **Alineación Texto**    | Select | Center      | Izquierda, Centro o Derecha                 |
| **Ancho Máx Contenido** | Range  | 700px       | Ancho máximo del contenido (400-1000px)     |
| **Altura (Móvil)**      | Range  | 500px       | Altura de sección en móvil (400-700px)      |
| **Altura (Escritorio)** | Range  | 650px       | Altura de sección en escritorio (400-900px) |

## 📖 Instalación

### Crear el Archivo de Sección

1. Copia el código de `hero-banner.liquid`
2. Ve a **Admin de Shopify** → **Tienda Online** → **Temas**
3. Haz clic en **Acciones** → **Editar código**
4. En la carpeta **Sections**, haz clic en el ícono **"+"**
5. Nómbralo `hero-banner.liquid`
6. Pega el código y haz clic en **Guardar**

### Agregar a tu Página

1. Ve a **Tienda Online** → **Temas** → **Personalizar**
2. Navega a la página deseada (usualmente Página Principal)
3. Haz clic en **Agregar sección**
4. Busca **"Hero Banner"**
5. Haz clic para agregarlo
6. Personaliza los ajustes
7. Sube tu imagen/video
8. **Agrega bloques de trust badge** (opcional):
   - Haz clic en "Agregar bloque" dentro de la sección Hero Banner
   - Selecciona "Trust Badge"
   - Elige un icono e ingresa texto
   - Repite para agregar más badges
   - Arrastra bloques para reordenarlos
9. Haz clic en **Guardar**

## 💡 Ejemplos de Uso

### Ejemplo 1: Tienda E-commerce

```
Medios:
- Imagen de Fondo: Foto lifestyle del producto
- Video: (Opcional) Producto en uso
- Overlay: #000000, 50% opacidad

Efectos:
- Parallax al Scroll: ✓ Habilitado
- Movimiento Ambiente: ✗ Deshabilitado

Contenido:
- Eyebrow: "NUEVA LLEGADA"
- Encabezado: "Productos de Calidad Premium"
- Subtítulo: "Descubre nuestra colección curada de artículos excepcionales"
- Color Texto: #ffffff

Botones:
- Botón 1: "Comprar Ahora" → /collections/all
- Botón 2: "Conocer Más" → /pages/about

Badges (agregar como bloques):
1. ✓ Envío Gratis (icono: shipping)
2. ✓ Devoluciones Fáciles (icono: returns)
3. ✓ Soporte 24/7 (icono: support)

Layout:
- Vertical: Centro
- Horizontal: Centro
- Alineación Texto: Centro
- Altura Escritorio: 700px
```

## 🎯 Mejores Prácticas

### Guías de Medios

1. **Dimensiones de Imagen**: Usa 1920x800px o mayor para mejor calidad
2. **Formato de Imagen**: JPG para fotos, PNG para gráficos con transparencia
3. **Subida de Video**:
   - Ve a Admin de Shopify → Configuración → Archivos
   - Sube tu video (MP4, codec H.264)
   - Copia la URL CDN generada
   - Pégala en el campo "URL de Video"
4. **Formato de Video**: MP4, codec H.264, máx 10MB para carga rápida
5. **Duración de Video**: Loop de 10-30 segundos funciona mejor
6. **Compresión**: Optimiza imágenes/videos antes de subir

### Guías de Efectos

1. **Parallax al Scroll**:

   - ✅ Mejor para: Secciones hero en la parte superior de la página
   - ✅ Funciona genial con: Imágenes lifestyle de alta calidad
   - ⚠️ Evitar con: Videos (puede causar problemas de rendimiento)
   - 💡 Tip: Combina con un overlay más oscuro para mejor contraste de texto

2. **Movimiento Ambiente**:

   - ✅ Mejor para: Imágenes estáticas que necesitan vida sutil
   - ✅ Funciona genial con: Fotos de productos, fotos lifestyle
   - ⚠️ **No aplica a videos**: Los videos ya tienen movimiento, por lo que el movimiento ambiente se deshabilita automáticamente cuando se usan fondos de video
   - 💡 Tip: El efecto es muy sutil - eso es intencional para profesionalismo

3. **Combinando Ambos Efectos**:
   - Crea una sensación premium y moderna
   - Mejor para marcas de moda, lifestyle y lujo
   - Prueba en móvil para asegurar rendimiento suave

### Consejos de Contenido

1. **Texto Eyebrow**: Mantenlo corto (1-3 palabras), usa para categorías o anuncios
2. **Encabezado**: Claro, audaz, enfocado en beneficios (3-6 palabras ideal)
3. **Subtítulo**: Expande el encabezado, agrega contexto (10-15 palabras)
4. **Botones**: Usa verbos de acción ("Comprar Ahora", "Comenzar", "Conocer Más")
5. **Badges**: Destaca beneficios clave (envío gratis, garantías, etc.)

### Consejos de Diseño

1. **Opacidad de Overlay**:

   - Imágenes claras: 20-40% opacidad
   - Imágenes oscuras: 40-60% opacidad
   - Imágenes ocupadas: 50-70% opacidad

2. **Color de Texto**:

   - Overlay oscuro → Texto blanco (#ffffff)
   - Overlay claro → Texto oscuro (#000000)
   - Asegura contraste para legibilidad

3. **Posicionamiento de Contenido**:

   - **Centro/Centro**: Más versátil, funciona para cualquier contenido
   - **Izquierda/Centro**: Genial para storytelling, más dinámico
   - **Abajo/Izquierda**: Moderno, estilo editorial

4. **Altura**:
   - Hero de página principal: 650-800px escritorio
   - Landing page: 500-650px escritorio
   - Página de campaña: 400-550px escritorio

### Consejos para Conversión

1. **Above the Fold**: Asegura que encabezado y CTA sean visibles sin hacer scroll
2. **CTAs Claros**: Botón primario debe destacar, secundario es opcional
3. **Señales de Confianza**: Usa badges para reducir fricción (envío gratis, devoluciones, etc.)
4. **Móvil Primero**: Prueba en móvil - la mayoría del tráfico viene de teléfonos
5. **Carga Rápida**: Optimiza archivos de medios para tiempos de carga rápidos

## 🐛 Solución de Problemas

**Problema**: Video no reproduce

- **Solución**: Asegúrate que el video sea formato MP4 y la URL sea correcta. Revisa la consola del navegador para errores.

**Problema**: Texto es difícil de leer

- **Solución**: Aumenta la opacidad del overlay o cambia el color del texto para mejor contraste.

**Problema**: Contenido se corta en móvil

- **Solución**: Reduce la altura móvil o ajusta el posicionamiento vertical.

**Problema**: Badges no se muestran

- **Solución**: Asegúrate de haber agregado al menos un bloque "Trust Badge" usando el botón "Agregar bloque".

**Problema**: Efecto parallax no funciona

- **Solución**:
  - Asegúrate que "Habilitar parallax al scroll" esté marcado
  - Parallax funciona mejor con imágenes, no videos
  - Intenta hacer scroll en la página para ver el efecto
  - Verifica que la sección hero esté en la parte superior de la página

**Problema**: Movimiento ambiente es muy sutil / no visible

- **Solución**:
  - El efecto es intencionalmente sutil (loop de 30 segundos)
  - Espera unos segundos para ver el movimiento circular suave
  - El efecto escala la imagen a 1.2x, así que asegura que tu imagen tenga suficiente espacio
  - El efecto se deshabilita para usuarios con preferencias de sensibilidad al movimiento

## 📱 Comportamiento Responsive

### Móvil (< 768px)

- Altura: Usa ajuste `height_mobile`
- Tamaños de fuente: Reducidos para legibilidad
- Botones: Se apilan si es necesario
- Badges: Se envuelven a múltiples líneas
- Padding: 40px vertical, 20px horizontal

### Escritorio (≥ 768px)

- Altura: Usa ajuste `height_desktop`
- Tamaños de fuente: Tamaño completo
- Botones: Lado a lado
- Badges: Línea única
- Padding: 60px vertical, 40px horizontal

## ⚡ Rendimiento

- **Sin Dependencias Externas**: Todos los iconos son SVG inline (Heroicons)
- **Medios Optimizados**: Usa CDN de imágenes de Shopify con srcset responsive
- **CSS Mínimo**: ~4KB de estilos (incluyendo efectos parallax)
- **Sin JavaScript**: Animaciones CSS puras para todos los efectos
- **Carga Rápida**: Lazy loading para imágenes, entrega optimizada de video
- **Accesibilidad**: Respeta `prefers-reduced-motion` para usuarios con sensibilidad al movimiento
- **Acelerado por GPU**: Efectos parallax y ambiente usan transforms CSS para rendimiento suave

---

**¿Necesitas ayuda?** Revisa el [README](../../README.es.md) principal o abre un issue en GitHub.
