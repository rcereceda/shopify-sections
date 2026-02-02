# Sección Featured Products

[🇺🇸 Read in English](../en/featured-products.md) | 🇪🇸 Español

Una sección flexible y altamente personalizable para mostrar tus mejores productos. Perfecta para destacar bestsellers, nuevos productos, artículos de temporada o cualquier colección curada de productos.

## 📋 Resumen

La sección Featured Products muestra productos de cualquier colección de Shopify en un grid hermoso y responsive. Incluye imágenes de productos, títulos, precios, badges de descuento y botones de llamado a la acción personalizables.

## ✨ Características

### Características de Contenido

- **Integración con Colecciones**: Obtiene productos de cualquier colección de Shopify
- **Límite Flexible de Productos**: Muestra 2-12 productos
- **Encabezado y Subtítulo**: Títulos de sección personalizables
- **Información de Producto**: Imagen, título, vendor, descripción, precio
- **Badges de Descuento**: Muestra automática de porcentaje de descuento
- **Precios Comparativos**: Muestra precio original cuando está en oferta
- **Botón Ver Todo**: Enlace a la colección completa
- **Efecto Hover de Imagen**: Muestra segunda imagen del producto al pasar el mouse (si está disponible)

### Características de Diseño

- **Grid Responsive**: 1 columna en móvil (por defecto), 2-4 en escritorio
- **Personalización de Tarjeta**: Borde, radio, padding, fondo
- **Control de Imagen**: Aspect ratio (cuadrado, vertical, horizontal) y opciones de ajuste
- **Control de Tipografía**: Tamaños y colores para todos los elementos de texto
- **Estilo de Botón**: Botones CTA completamente personalizables
- **Efectos Hover**: Animación suave de sombra + revelación de botón

### Características de Rendimiento

- **Lazy Loading**: Las imágenes cargan según se necesitan
- **Imágenes Responsive**: Srcset para tamaños óptimos de imagen
- **Markup Optimizado**: HTML limpio y semántico

## 🎨 Opciones de Personalización

### Ajustes de Contenido

| Ajuste              | Tipo              | Por Defecto                       | Descripción                     |
| ------------------- | ----------------- | --------------------------------- | ------------------------------- |
| Encabezado          | Text              | "Featured Products"               | Título principal de la sección  |
| Subtítulo           | Text              | "Discover our most popular items" | Subtítulo de la sección         |
| Colección           | Collection Picker | -                                 | Colección fuente para productos |
| Máximo de Productos | Range (2-12)      | 4                                 | Número de productos a mostrar   |

### Ajustes de Layout

| Ajuste                  | Tipo                | Por Defecto | Descripción                        |
| ----------------------- | ------------------- | ----------- | ---------------------------------- |
| Columnas (móvil)        | Select              | 1 columna   | Columnas del grid en móvil (1 o 2) |
| Columnas (escritorio)   | Range (2-4)         | 4           | Columnas del grid en escritorio    |
| Espacio Entre Productos | Range (8-48px)      | 24px        | Espacio entre tarjetas de producto |
| Ancho del Contenedor    | Range (1000-1600px) | 1200px      | Ancho máximo de la sección         |

### Estilo de Encabezado

| Ajuste                         | Tipo            | Por Defecto | Descripción                         |
| ------------------------------ | --------------- | ----------- | ----------------------------------- |
| Alineación Encabezado          | Select          | Center      | Izquierda, Centro o Derecha         |
| Tamaño Encabezado (móvil)      | Range (20-48px) | 28px        | Tamaño fuente encabezado móvil      |
| Tamaño Encabezado (escritorio) | Range (24-64px) | 36px        | Tamaño fuente encabezado escritorio |
| Espacio Debajo Encabezado      | Range (16-64px) | 32px        | Margen debajo del encabezado        |
| Color Encabezado               | Color           | #000000     | Color texto del encabezado          |
| Color Subtítulo                | Color           | #666666     | Color texto del subtítulo           |

### Estilo de Tarjeta de Producto

| Ajuste                | Tipo           | Por Defecto | Descripción               |
| --------------------- | -------------- | ----------- | ------------------------- |
| Fondo de Tarjeta      | Color          | #ffffff     | Color de fondo de tarjeta |
| Ancho Borde Tarjeta   | Range (0-4px)  | 1px         | Grosor del borde          |
| Color Borde Tarjeta   | Color          | #e5e5e5     | Color del borde           |
| Border Radius Tarjeta | Range (0-24px) | 8px         | Redondez de esquinas      |
| Padding Tarjeta       | Range (8-32px) | 16px        | Padding interno           |

### Imagen de Producto

| Ajuste                          | Tipo     | Por Defecto    | Descripción                                  |
| ------------------------------- | -------- | -------------- | -------------------------------------------- |
| Mostrar Segunda Imagen en Hover | Checkbox | On             | Muestra segunda imagen del producto en hover |
| Aspect Ratio de Imagen          | Select   | Cuadrado (1:1) | Proporciones de imagen                       |
| Ajuste de Imagen                | Select   | Cover          | Cómo la imagen llena el contenedor           |
| Color de Fondo de Imagen        | Color    | #f5f5f5        | Fondo para imágenes transparentes            |

**Opciones de Ratio de Imagen:**

- Cuadrado (1:1) - 100%
- Vertical (4:5) - 125%
- Vertical (3:4) - 133%
- Horizontal (4:3) - 75%

### Info de Producto

| Ajuste                | Tipo            | Por Defecto | Descripción                       |
| --------------------- | --------------- | ----------- | --------------------------------- |
| Mostrar Vendor        | Checkbox        | Off         | Muestra vendor/marca del producto |
| Color Vendor          | Color           | #999999     | Color texto del vendor            |
| Color Título          | Color           | #000000     | Color del título del producto     |
| Tamaño Título         | Range (14-24px) | 16px        | Tamaño fuente del título          |
| Mostrar Descripción   | Checkbox        | Off         | Muestra descripción del producto  |
| Color Descripción     | Color           | #666666     | Color texto de descripción        |
| Color Precio          | Color           | #000000     | Color texto del precio            |
| Tamaño Precio         | Range (14-24px) | 18px        | Tamaño fuente del precio          |
| Color Precio Comparar | Color           | #999999     | Color del precio original         |

### Badge de Descuento

| Ajuste               | Tipo     | Por Defecto | Descripción                     |
| -------------------- | -------- | ----------- | ------------------------------- |
| Mostrar Badge Oferta | Checkbox | On          | Muestra porcentaje de descuento |
| Fondo Badge          | Color    | #ff0000     | Color de fondo del badge        |
| Color Texto Badge    | Color    | #ffffff     | Color del texto del badge       |

### Botón

| Ajuste              | Tipo           | Por Defecto | Descripción                                            |
| ------------------- | -------------- | ----------- | ------------------------------------------------------ |
| Mostrar Botón       | Checkbox       | On          | Muestra botón CTA debajo de tarjeta (aparece en hover) |
| Texto Botón         | Text           | "Buy Now"   | Etiqueta del botón                                     |
| Fondo Botón         | Color          | #000000     | Color de fondo del botón                               |
| Color Texto Botón   | Color          | #ffffff     | Color del texto del botón                              |
| Border Radius Botón | Range (0-24px) | 4px         | Redondez de esquinas del botón                         |

### Botón Ver Todo

| Ajuste                   | Tipo            | Por Defecto | Descripción              |
| ------------------------ | --------------- | ----------- | ------------------------ |
| Mostrar Botón 'Ver Todo' | Checkbox        | On          | Muestra enlace colección |
| Texto Botón              | Text            | "Shop Now"  | Etiqueta del botón       |
| Espacio Arriba del Botón | Range (24-80px) | 48px        | Margen superior          |
| Fondo                    | Color           | #ffffff     | Fondo del botón          |
| Color Texto              | Color           | #000000     | Color texto del botón    |
| Color Borde              | Color           | #000000     | Color borde del botón    |

### Espaciado de Sección

| Ajuste           | Tipo            | Por Defecto | Descripción         |
| ---------------- | --------------- | ----------- | ------------------- |
| Padding Superior | Range (0-120px) | 60px        | Espaciado superior  |
| Padding Inferior | Range (0-120px) | 60px        | Espaciado inferior  |
| Color de Fondo   | Color           | #f5f5f5     | Fondo de la sección |

## 📦 Instalación

### Paso 1: Copiar el Código de la Sección

1. Navega a `sections/featured-products.liquid`
2. Copia todo el contenido del archivo

### Paso 2: Crear el Archivo de Sección

1. Ve a **Admin de Shopify** → **Tienda Online** → **Temas**
2. Haz clic en **Acciones** → **Editar código**
3. En la carpeta **Sections**, haz clic en el ícono **"+"**
4. Nómbralo `featured-products.liquid`
5. Pega el código y haz clic en **Guardar**

### Paso 3: Agregar a tu Página

1. Ve a **Tienda Online** → **Temas** → **Personalizar**
2. Navega a la página deseada
3. Haz clic en **Agregar sección**
4. Busca **"Featured Products"**
5. Haz clic para agregarlo
6. **Selecciona una colección** en los ajustes
7. Personaliza los ajustes según tus necesidades
8. Haz clic en **Guardar**

## 💡 Ejemplos de Uso

### Ejemplo 1: Bestsellers de Página Principal

```
Contenido:
- Encabezado: "Nuestros Bestsellers"
- Subtítulo: "Los productos más amados por nuestros clientes"
- Colección: "Bestsellers"
- Productos: 4

Layout:
- Columnas (móvil): 1
- Columnas (escritorio): 4
- Gap: 24px

Estilo:
- Card Background: #ffffff
- Border Radius: 12px
- Mostrar Segunda Imagen: ✓
- Mostrar Badge Oferta: ✓
```

### Ejemplo 2: Nuevos Productos

```
Contenido:
- Encabezado: "Recién Llegados"
- Subtítulo: "Descubre nuestras últimas incorporaciones"
- Colección: "New Arrivals"
- Productos: 6

Layout:
- Columnas (móvil): 2
- Columnas (escritorio): 3
- Gap: 32px

Estilo:
- Aspect Ratio: Vertical (4:5)
- Mostrar Vendor: ✓
- Mostrar Descripción: ✓
```

### Ejemplo 3: Colección de Temporada

```
Contenido:
- Encabezado: "Colección de Verano"
- Subtítulo: "Productos frescos para la temporada"
- Colección: "Summer Collection"
- Productos: 8

Layout:
- Columnas (móvil): 1
- Columnas (escritorio): 4
- Container Width: 1400px

Estilo:
- Background Color: #f0f9ff
- Card Border: 0px
- Border Radius: 16px
- Button Text: "Ver Producto"
```

## 🎯 Mejores Prácticas

### Selección de Productos

1. **Curación**: Elige productos que representen bien tu marca
2. **Variedad**: Mezcla diferentes tipos de productos si es posible
3. **Calidad de Imagen**: Usa imágenes profesionales de alta resolución
4. **Precios**: Considera mostrar un rango de precios para diferentes presupuestos

### Diseño

1. **Número de Productos**: 4-8 productos funciona mejor para la mayoría de casos
2. **Columnas Móvil**: Usa 1 columna para mejor experiencia en móvil
3. **Aspect Ratio**: Cuadrado (1:1) es más versátil, vertical (4:5) mejor para moda
4. **Espaciado**: Mantén gap consistente con otras secciones de tu tienda

### Contenido

1. **Encabezado**: Claro y descriptivo (ej: "Bestsellers", "Nuevos Productos")
2. **Subtítulo**: Agrega contexto o beneficio
3. **Botón CTA**: "Comprar Ahora" convierte mejor que "Ver Producto"
4. **Botón Ver Todo**: Enlaza a la colección completa para más opciones

### Conversión

1. **Badges de Descuento**: Siempre muestra descuentos para crear urgencia
2. **Segunda Imagen**: Habilita hover de imagen para mostrar más del producto
3. **Descripción**: Muestra solo si agrega valor (evita texto genérico)
4. **Posición**: Coloca en homepage arriba del fold o después del hero

## 🐛 Solución de Problemas

**Problema**: No se muestran productos

- **Solución**: Asegúrate de haber seleccionado una colección con productos publicados

**Problema**: Imágenes se ven estiradas

- **Solución**: Ajusta el aspect ratio o usa "Contain" en vez de "Cover" para image fit

**Problema**: Layout se rompe en móvil

- **Solución**: Reduce columnas móvil a 1, reduce padding de tarjeta

**Problema**: Botón no aparece en hover

- **Solución**: En móvil, el botón está oculto por defecto (no hay hover). Solo aparece en escritorio.

**Problema**: Segunda imagen no se muestra en hover

- **Solución**: Asegúrate que el producto tenga al menos 2 imágenes y que la opción esté habilitada

**Problema**: Badge de descuento no aparece

- **Solución**: Verifica que el producto tenga un "compare at price" configurado en Shopify

## 📱 Comportamiento Responsive

### Móvil (< 768px)

- Usa `columns_mobile` (1 o 2 columnas)
- Botón "Buy Now" oculto (no hay hover en móvil)
- Tamaño de fuente reducido
- Padding reducido en tarjetas
- Grid gap reducido

### Escritorio (≥ 768px)

- Usa `columns_desktop` (2-4 columnas)
- Botón "Buy Now" aparece en hover
- Tamaño de fuente completo
- Padding completo en tarjetas
- Segunda imagen aparece en hover (si está habilitada)

## ⚡ Rendimiento

- **Lazy Loading**: Imágenes cargan solo cuando son visibles
- **Responsive Images**: Usa srcset para servir tamaño óptimo
- **CSS Optimizado**: ~3KB de estilos
- **Sin JavaScript**: Efectos hover con CSS puro
- **Shopify CDN**: Imágenes servidas desde CDN global de Shopify

---

**¿Necesitas ayuda?** Revisa el [README](../../README.es.md) principal o abre un issue en GitHub.
