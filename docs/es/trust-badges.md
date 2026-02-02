# Sección Trust Badges - Guía de Uso

[🇺🇸 Read in English](../en/trust-badges.md) | 🇪🇸 Español

## 📋 Resumen

La sección Trust Badges muestra múltiples indicadores de confianza en un grid responsive para generar confianza en el cliente y aumentar conversiones.

## ✨ Características

- **Múltiples Badges**: Agrega badges de confianza ilimitados usando bloques
- **6 Iconos Integrados** (Heroicons):
  - 🚚 Envío Gratis (icono de camión)
  - ✅ Garantía de Devolución (icono de escudo con check)
  - 💬 Soporte 24/7 (icono de burbujas de chat)
  - ⭐ Calidad Premium (icono de estrella)
  - 🔄 Devoluciones Fáciles (icono de flecha circular)
  - 🌱 Eco-Friendly (icono de hoja)
- **Diseño Profesional**: Heroicons modernos para un look limpio y consistente
- **Grid Responsive**: 1-4 columnas en escritorio, 1-2 en móvil
- **Totalmente Personalizable**: Colores, espaciado, border radius
- **Efectos Hover**: Animaciones suaves al pasar el mouse
- **Sin Dependencias**: Liquid y CSS puros

## 🎨 Opciones de Personalización

### Ajustes de Sección

| Ajuste                    | Tipo    | Por Defecto        | Descripción                            |
| ------------------------- | ------- | ------------------ | -------------------------------------- |
| **Encabezado**            | Texto   | "Why Shop With Us" | Encabezado opcional de la sección      |
| **Columnas (Móvil)**      | Select  | 1                  | Número de columnas en móvil (1 o 2)    |
| **Columnas (Escritorio)** | Range   | 4                  | Número de columnas en escritorio (1-4) |
| **Gap**                   | 8-48px  | 24px               | Espacio entre badges                   |
| **Color de Fondo**        | Color   | #f9f9f9            | Color de fondo del badge               |
| **Color de Texto**        | Color   | #000000            | Color del texto del badge              |
| **Color de Icono**        | Color   | #000000            | Color del icono del badge              |
| **Border Radius**         | 0-24px  | 8px                | Redondez de las esquinas del badge     |
| **Padding Superior**      | 0-100px | 40px               | Espaciado superior de la sección       |
| **Padding Inferior**      | 0-100px | 40px               | Espaciado inferior de la sección       |

### Ajustes de Bloque (Por Badge)

| Ajuste          | Tipo   | Por Defecto          | Descripción                    |
| --------------- | ------ | -------------------- | ------------------------------ |
| **Icono**       | Select | Shipping             | Elige entre 6 iconos o ninguno |
| **Título**      | Texto  | "Free Shipping"      | Título del badge               |
| **Descripción** | Texto  | "On orders over $50" | Descripción del badge          |

## 📖 Instalación

### Crear el Archivo de Sección

1. Copia el código de `trust-badges.liquid`
2. Ve a **Admin de Shopify** → **Tienda Online** → **Temas**
3. Haz clic en **Acciones** → **Editar código**
4. En la carpeta **Sections**, haz clic en el ícono **"+"** (o clic derecho → **Nuevo archivo**)
5. Nómbralo `trust-badges.liquid`
6. Pega el código y haz clic en **Guardar**

### Agregar a tu Página

1. Regresa a **Tienda Online** → **Temas**
2. Haz clic en **Personalizar** (no "Editar código")
3. Navega a la página deseada
4. Haz clic en **Agregar sección** (bajo Header, Template o Footer)
5. Busca **"Trust Badges"**
6. Haz clic para agregarlo y personaliza los ajustes
7. Haz clic en **Guardar**

## 💡 Ejemplos de Uso

### Ejemplo 1: Página Principal de E-commerce

```
Encabezado: "Por Qué Comprar con Nosotros"
Columnas (Escritorio): 4
Columnas (Móvil): 2

Badges:
1. Envío Gratis | En pedidos mayores a $50
2. Devoluciones Fáciles | Política de devolución de 30 días
3. Soporte 24/7 | Servicio al cliente dedicado
4. Calidad Premium | Productos mejor calificados
```

### Ejemplo 2: Página de Producto

```
Encabezado: "" (sin encabezado)
Columnas (Escritorio): 3
Columnas (Móvil): 1

Badges:
1. Calidad Premium | Hecho a mano con cuidado
2. Devoluciones Fáciles | Devoluciones sin complicaciones de 60 días
3. Eco-Friendly | Materiales de origen sostenible
```

### Ejemplo 3: Página de Checkout

```
Encabezado: "Compra Segura y Protegida"
Columnas (Escritorio): 2
Columnas (Móvil): 1

Badges:
1. Pago Seguro | Checkout encriptado con SSL
2. Garantía de Devolución | 100% satisfacción garantizada
```

## 🎯 Mejores Prácticas

### Ubicación

- **Página Principal**: Debajo de la sección hero o arriba del footer
- **Páginas de Producto**: Debajo del botón "Agregar al Carrito"
- **Páginas de Colección**: En la parte superior o inferior
- **Carrito/Checkout**: Cerca de los botones de pago

### Consejos de Contenido

1. **Sé Específico**: "Envío gratis en pedidos mayores a $50" es mejor que solo "Envío gratis"
2. **Usa Números**: "Política de devolución de 30 días" es más concreto que "Devoluciones fáciles"
3. **Genera Confianza**: Enfócate en lo que más les importa a los clientes
4. **Mantenlo Corto**: Los títulos deben ser de 2-4 palabras, las descripciones de 3-6 palabras

### Consejos de Diseño

1. **Coincide con tu Marca**: Personaliza los colores para que coincidan con tu tienda
2. **No Exageres**: 3-4 badges suelen ser suficientes
3. **Usa Contraste**: Asegúrate de que el texto sea legible sobre el fondo
4. **Prueba en Móvil**: Siempre revisa cómo se ve en dispositivos móviles

## 🔧 Ejemplos de Personalización

### Estilo Minimalista

```
Color de Fondo: #ffffff
Border Radius: 0px
Gap: 16px
```

### Estilo de Tarjeta

```
Color de Fondo: #f5f5f5
Border Radius: 12px
Gap: 24px
```

### Estilo Audaz

```
Color de Fondo: #000000
Color de Texto: #ffffff
Color de Icono: #ffffff
Border Radius: 8px
```

## 🐛 Solución de Problemas

**Problema**: Los badges no se muestran

- **Solución**: Asegúrate de haber agregado al menos un bloque de badge

**Problema**: El layout se ve roto en móvil

- **Solución**: Intenta reducir las columnas en móvil a 1

**Problema**: Los iconos no se muestran

- **Solución**: Asegúrate de haber seleccionado un icono (no "ninguno")

**Problema**: Los colores no cambian

- **Solución**: Limpia el caché de tu navegador y recarga

## 📱 Comportamiento Responsive

- **Móvil (< 768px)**: Usa el ajuste `columns_mobile`
- **Escritorio (≥ 768px)**: Usa el ajuste `columns_desktop`
- Los iconos escalan de 48px a 56px
- Los tamaños de texto se ajustan automáticamente

## ⚡ Rendimiento

- **Sin Dependencias Externas**: Todos los iconos son SVG inline (Heroicons)
- **CSS Mínimo**: ~2KB de estilos
- **Carga Rápida**: No requiere JavaScript
- **Amigable con SEO**: Estructura HTML semántica
- **Iconos Modernos**: Heroicons profesionales para un look pulido

## 🎨 Esquemas de Color

### Modo Claro (Por Defecto)

```
Fondo: #f9f9f9
Texto: #000000
Icono: #000000
```

### Modo Oscuro

```
Fondo: #1a1a1a
Texto: #ffffff
Icono: #ffffff
```

### Colores de Marca (Ejemplo)

```
Fondo: #f0f7ff
Texto: #003d82
Icono: #0066cc
```

## 📊 Consejos para Conversión

1. **Above the Fold**: Coloca los trust badges donde los clientes puedan verlos inmediatamente
2. **Cerca de CTAs**: Posiciona cerca de los botones "Agregar al Carrito" o "Comprar Ahora"
3. **Mensajería Consistente**: Haz que los badges coincidan con tus políticas reales
4. **Prueba Variaciones**: Prueba diferentes combinaciones para ver qué convierte mejor
5. **Actualiza Regularmente**: Mantén la información actualizada (ej., umbrales de envío)

---

**¿Necesitas ayuda?** Revisa el [README](../../README.es.md) principal o abre un issue en GitHub.
