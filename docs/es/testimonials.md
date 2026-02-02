# Sección Testimonials

[🇺🇸 Read in English](../en/testimonials.md) | 🇪🇸 Español

Una sección poderosa para mostrar reseñas de clientes y construir prueba social. Muestra testimoniales auténticos con calificaciones de estrellas, fotos de clientes y reseñas detalladas para aumentar confianza y conversiones.

## 📋 Resumen

La sección Testimonials te ayuda a construir credibilidad mostrando experiencias reales de clientes. Presenta un grid responsive de tarjetas de testimoniales, cada una con foto del cliente, nombre, calificación de estrellas y texto de reseña.

## ✨ Características

### Características de Contenido

- **Hasta 12 Testimoniales**: Agrega múltiples reseñas de clientes
- **Calificaciones de Estrellas**: Sistema de calificación de 1-5 estrellas con estrellas visuales
- **Fotos de Clientes**: Sube imágenes de clientes o usa placeholder
- **Muestra Rol/Empresa**: Muestra título del cliente o nombre de empresa
- **Icono de Cita**: Comillas decorativas opcionales
- **Texto Flexible**: Soporte para reseñas cortas o largas

### Características de Diseño

- **Grid Responsive**: 1 columna en móvil, hasta 3 en escritorio
- **Personalización de Tarjeta**: Borde, radio, padding, fondo
- **Efectos Hover**: Animación suave de elevación al pasar el mouse
- **Control de Tipografía**: Tamaños y colores personalizables
- **Opciones de Imagen**: Fotos de clientes cuadradas o circulares
- **Jerarquía Visual**: Separación clara entre calificación, texto e info del cliente

### Características de Rendimiento

- **Lazy Loading**: Las imágenes cargan según se necesitan
- **Markup Optimizado**: HTML limpio y semántico
- **Layout Flexible**: Se auto-ajusta a la longitud del contenido

## 🎨 Opciones de Personalización

### Ajustes de Contenido

| Ajuste     | Tipo     | Por Defecto                        | Descripción              |
| ---------- | -------- | ---------------------------------- | ------------------------ |
| Encabezado | Text     | "What Our Customers Say"           | Título principal sección |
| Subtítulo  | Textarea | "Real reviews from real customers" | Subtítulo de la sección  |

### Ajustes de Layout

| Ajuste                 | Tipo                | Por Defecto | Descripción                        |
| ---------------------- | ------------------- | ----------- | ---------------------------------- |
| Ancho Contenedor       | Range (1000-1600px) | 1200px      | Ancho máximo de la sección         |
| Columnas (Móvil)       | Select              | 1 columna   | Columnas del grid en móvil (1 o 2) |
| Columnas (Escritorio)  | Range (1-3)         | 3           | Columnas del grid en escritorio    |
| Espacio Entre Tarjetas | Range (8-48px)      | 24px        | Espacio entre tarjetas testimonial |

### Estilo de Encabezado

| Ajuste                         | Tipo            | Por Defecto | Descripción                         |
| ------------------------------ | --------------- | ----------- | ----------------------------------- |
| Alineación Encabezado          | Select          | Center      | Izquierda, Centro o Derecha         |
| Tamaño Encabezado (Móvil)      | Range (20-48px) | 28px        | Tamaño fuente encabezado móvil      |
| Tamaño Encabezado (Escritorio) | Range (24-64px) | 36px        | Tamaño fuente encabezado escritorio |
| Espacio Debajo Encabezado      | Range (16-64px) | 40px        | Margen debajo del encabezado        |
| Color Encabezado               | Color           | #000000     | Color texto del encabezado          |
| Color Subtítulo                | Color           | #666666     | Color texto del subtítulo           |

### Estilo de Tarjeta

| Ajuste                | Tipo            | Por Defecto | Descripción               |
| --------------------- | --------------- | ----------- | ------------------------- |
| Fondo Tarjeta         | Color           | #ffffff     | Color de fondo de tarjeta |
| Ancho Borde Tarjeta   | Range (0-4px)   | 1px         | Grosor del borde          |
| Color Borde Tarjeta   | Color           | #e5e5e5     | Color del borde           |
| Border Radius Tarjeta | Range (0-24px)  | 12px        | Redondez de esquinas      |
| Padding Tarjeta       | Range (16-48px) | 24px        | Padding interno           |

### Calificación

| Ajuste                         | Tipo            | Por Defecto | Descripción                      |
| ------------------------------ | --------------- | ----------- | -------------------------------- |
| Mostrar Calificación Estrellas | Checkbox        | On          | Muestra calificaciones estrellas |
| Tamaño Estrella                | Range (14-32px) | 20px        | Tamaño icono estrella            |
| Color Estrella (Llena)         | Color           | #ffc107     | Color para estrellas llenas      |
| Color Estrella (Vacía)         | Color           | #e0e0e0     | Color para estrellas vacías      |

### Texto de Reseña

| Ajuste             | Tipo            | Por Defecto | Descripción                |
| ------------------ | --------------- | ----------- | -------------------------- |
| Mostrar Icono Cita | Checkbox        | On          | Muestra comillas           |
| Tamaño Texto       | Range (14-20px) | 16px        | Tamaño fuente texto reseña |
| Color Texto        | Color           | #333333     | Color texto de reseña      |

### Info del Cliente

| Ajuste                      | Tipo            | Por Defecto | Descripción                     |
| --------------------------- | --------------- | ----------- | ------------------------------- |
| Tamaño Imagen               | Range (40-80px) | 56px        | Tamaño foto del cliente         |
| Border Radius Imagen        | Range (0-50%)   | 50%         | Redondez imagen (50% = círculo) |
| Fondo Placeholder           | Color           | #f0f0f0     | Fondo para fotos faltantes      |
| Color Icono Placeholder     | Color           | #cccccc     | Color icono para placeholders   |
| Tamaño Nombre               | Range (14-20px) | 16px        | Tamaño fuente nombre cliente    |
| Color Nombre                | Color           | #000000     | Color nombre del cliente        |
| Mostrar Rol/Empresa Cliente | Checkbox        | On          | Muestra rol o empresa           |
| Tamaño Rol                  | Range (12-16px) | 14px        | Tamaño fuente texto rol         |
| Color Rol                   | Color           | #666666     | Color texto rol                 |

### Espaciado

| Ajuste                        | Tipo             | Por Defecto | Descripción                   |
| ----------------------------- | ---------------- | ----------- | ----------------------------- |
| Padding Superior (Móvil)      | Range (20-100px) | 40px        | Espaciado superior en móvil   |
| Padding Inferior (Móvil)      | Range (20-100px) | 40px        | Espaciado inferior en móvil   |
| Padding Superior (Escritorio) | Range (40-160px) | 80px        | Espaciado superior escritorio |
| Padding Inferior (Escritorio) | Range (40-160px) | 80px        | Espaciado inferior escritorio |

### Colores

| Ajuste         | Tipo  | Por Defecto | Descripción         |
| -------------- | ----- | ----------- | ------------------- |
| Color de Fondo | Color | #f9f9f9     | Fondo de la sección |

## 📦 Instalación

### Paso 1: Copiar el Código de la Sección

1. Navega a `sections/testimonials.liquid`
2. Copia todo el contenido del archivo

### Paso 2: Crear el Archivo de Sección

1. Ve a **Admin de Shopify** → **Tienda Online** → **Temas**
2. Haz clic en **Acciones** → **Editar código**
3. En la carpeta **Sections**, haz clic en el ícono **"+"**
4. Nómbralo `testimonials.liquid`
5. Pega el código y haz clic en **Guardar**

### Paso 3: Agregar a tu Página

1. Ve a **Tienda Online** → **Temas** → **Personalizar**
2. Navega a la página deseada
3. Haz clic en **Agregar sección**
4. Busca **"Testimonials"**
5. Haz clic para agregarlo
6. **Agrega bloques de testimoniales**:
   - Haz clic en "Agregar bloque"
   - Selecciona "Testimonial"
   - Completa calificación, reseña, foto y nombre del cliente
   - Repite para agregar más testimoniales (hasta 12)
7. Personaliza los ajustes de estilo
8. Haz clic en **Guardar**

## 💡 Ejemplos de Uso

### Ejemplo 1: Página Principal - Prueba Social

```
Contenido:
- Encabezado: "Lo Que Dicen Nuestros Clientes"
- Subtítulo: "Reseñas reales de clientes reales"

Layout:
- Columnas (Móvil): 1
- Columnas (Escritorio): 3
- Gap: 24px

Testimoniales (3):
1. ⭐⭐⭐⭐⭐ | "Producto increíble, superó mis expectativas" | María G.
2. ⭐⭐⭐⭐⭐ | "Servicio al cliente excepcional" | Juan P.
3. ⭐⭐⭐⭐⭐ | "Mejor compra que he hecho" | Ana L.

Estilo:
- Imagen: Circular (50%)
- Card Radius: 12px
- Mostrar Icono Cita: ✓
```

### Ejemplo 2: Página de Producto

```
Contenido:
- Encabezado: "Clientes Satisfechos"
- Subtítulo: "Más de 500 reseñas de 5 estrellas"

Layout:
- Columnas (Móvil): 1
- Columnas (Escritorio): 2
- Container Width: 1000px

Testimoniales (4):
- Reseñas específicas del producto
- Fotos reales de clientes
- Calificaciones de 4-5 estrellas

Estilo:
- Background: #ffffff
- Card Border: 2px
- Mostrar Rol: ✓ (ej: "Comprador Verificado")
```

### Ejemplo 3: Página About

```
Contenido:
- Encabezado: "Historias de Nuestros Clientes"
- Subtítulo: "Cómo hemos impactado sus vidas"

Layout:
- Columnas (Móvil): 1
- Columnas (Escritorio): 3
- Gap: 32px

Testimoniales (6):
- Reseñas más largas y detalladas
- Fotos profesionales de clientes
- Incluye empresa/rol del cliente

Estilo:
- Imagen: Cuadrada (0%)
- Card Padding: 32px
- Text Size: 16px
```

## 🎯 Mejores Prácticas

### Contenido de Testimoniales

1. **Autenticidad**: Usa reseñas reales de clientes reales
2. **Especificidad**: Testimoniales específicos son más creíbles que genéricos
3. **Variedad**: Mezcla diferentes tipos de clientes y experiencias
4. **Longitud**: 2-4 oraciones es ideal (50-100 palabras)
5. **Fotos Reales**: Fotos auténticas de clientes generan más confianza

### Diseño

1. **Número de Testimoniales**: 3-6 testimoniales funciona mejor
2. **Columnas**: 3 columnas en escritorio, 1 en móvil
3. **Calificaciones**: Muestra mayormente 4-5 estrellas (pero incluye algún 3-4 para credibilidad)
4. **Imágenes Circulares**: Más moderno y amigable
5. **Espaciado**: Suficiente padding para que las tarjetas respiren

### Ubicación

1. **Homepage**: Después de productos destacados o antes del footer
2. **Páginas de Producto**: Cerca del botón "Agregar al Carrito"
3. **Página About**: Para construir credibilidad de marca
4. **Landing Pages**: Para reducir objeciones y aumentar conversiones

### Conversión

1. **Nombres Completos**: Usa nombres reales (con permiso)
2. **Roles/Empresas**: Agrega credibilidad ("CEO de...", "Comprador Verificado")
3. **Fotos**: Siempre incluye fotos cuando sea posible
4. **Calificaciones Visibles**: Las estrellas llaman la atención inmediatamente
5. **Variedad de Beneficios**: Diferentes testimoniales destacando diferentes aspectos

## 🐛 Solución de Problemas

**Problema**: Testimoniales no se muestran

- **Solución**: Asegúrate de haber agregado al menos un bloque "Testimonial"

**Problema**: Layout se ve roto en móvil

- **Solución**: Reduce columnas móvil a 1, reduce padding de tarjeta

**Problema**: Fotos se ven estiradas

- **Solución**: Usa imágenes cuadradas (1:1) o ajusta el border radius

**Problema**: Texto muy largo rompe el diseño

- **Solución**: Mantén testimoniales entre 50-100 palabras, usa texto más conciso

**Problema**: Estrellas no se muestran

- **Solución**: Verifica que "Mostrar Calificación Estrellas" esté habilitado

**Problema**: Placeholder de imagen no se ve bien

- **Solución**: Ajusta colores de placeholder background e icon color para mejor contraste

## 📱 Comportamiento Responsive

### Móvil (< 768px)

- Usa `columns_mobile` (1 o 2 columnas)
- Padding reducido en tarjetas
- Tamaños de fuente reducidos
- Imágenes de cliente más pequeñas
- Grid gap reducido

### Escritorio (≥ 768px)

- Usa `columns_desktop` (1-3 columnas)
- Padding completo en tarjetas
- Tamaños de fuente completos
- Hover effect con elevación de tarjeta
- Grid gap completo

## ⚡ Rendimiento

- **Lazy Loading**: Fotos de clientes cargan solo cuando son visibles
- **CSS Optimizado**: ~2KB de estilos
- **Sin JavaScript**: Efectos hover con CSS puro
- **Markup Semántico**: HTML limpio y accesible
- **Flexible Grid**: CSS Grid moderno para layout responsive

## 🎨 Esquemas de Color

### Estilo Claro (Por Defecto)

```
Background: #f9f9f9
Card Background: #ffffff
Card Border: #e5e5e5
Text: #333333
Stars: #ffc107
```

### Estilo Oscuro

```
Background: #1a1a1a
Card Background: #2a2a2a
Card Border: #404040
Text: #ffffff
Stars: #ffc107
```

### Estilo Minimalista

```
Background: #ffffff
Card Background: #ffffff
Card Border: #000000 (2px)
Text: #000000
Stars: #000000
```

## 📊 Consejos para Conversión

1. **Ubicación Estratégica**: Coloca testimoniales donde los clientes toman decisiones
2. **Prueba Social**: Más testimoniales = más confianza (pero no sobrecargues)
3. **Especificidad**: "Envío en 2 días" es mejor que "Envío rápido"
4. **Fotos Reales**: Aumentan credibilidad en 35%
5. **Calificaciones Altas**: Muestra mayormente 4-5 estrellas
6. **Actualiza Regularmente**: Testimoniales recientes son más relevantes

---

**¿Necesitas ayuda?** Revisa el [README](../../README.es.md) principal o abre un issue en GitHub.
