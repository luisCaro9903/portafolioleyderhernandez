# Portafolio Leyder Hernández · v5

Sitio estático. Abrir `index.html` en el navegador. No necesita build ni servidor.

## Estructura

- `index.html`: todo el sitio (HTML, CSS y JS en un solo archivo, sin librerías).
- `assets/img/`: 102 imágenes optimizadas. Nombre: `{proyecto}-{nn}-1200.jpg`. Las de gran formato también tienen `-2000.jpg` y se sirven con `srcset`.
- Fuente de las imágenes: https://leyderh3.myportfolio.com (descargadas el 2026-11-06).
- Retrato: `assets/img/leyder-retrato-900.jpg` (foto entregada por Leyder, recortada al círculo).
- Trayectoria, formación, herramientas y uso de IA por proyecto: CV de Leyder (noviembre 2026).
- Respaldo de la versión anterior: `../2026-11-06-portfolio-leyder-hernandez-v2-respaldo.html`.

## Curaduría

Casos destacados (4), elegidos por versatilidad y no solo por impacto visual:

1. **Carnaval de Polonuevo 2026**: dirección de arte, concepto y consistencia en serie (6 eventos, una estructura).
2. **La Barca del Arte**: rediseño de identidad con antes/después y evidencia en sitio.
3. **Informe de reacreditación (Universidad del Atlántico)**: editorial, arquitectura de información e IA en el proceso.
4. **Feria Agroindustrial**: sistema modular que llega al espacio físico (foto del arco de entrada).

**Pitalito 81 años** queda como "También destacado". Tiene la mejor documentación del sistema (concepto, paleta, elementos, afiche), pero se superpone con el Carnaval: mismo cliente, mismo tipo de encargo. Se presenta como secuencia de construcción en 4 láminas.

Los 12 proyectos siguen en el Archivo (vista lista o mosaico). Ningún proyecto se eliminó.

## Reglas de veracidad

- Los textos de contexto, reto y concepto salen de las descripciones originales de Leyder o de lo visible en las piezas. No hay métricas, testimonios, bocetos ni resultados inventados.
- **Fotografía en sitio**: solo dos imágenes muestran implementación real. Son el afiche de La Barca durante una actividad y el arco de entrada de la Feria.
- **Mockup**: se marca así toda pieza presentada en render (merch, credenciales, teléfonos, boletas). No implica que se haya producido.
- "Identidad anterior" en La Barca: es la única pieza del proyecto que no usa el logotipo nuevo, y la descripción original dice que la página muestra la identidad anterior.
- Las paletas se tomaron a ojo de las piezas, no de los archivos fuente.

## Interacción

- **Visor de imágenes**: toda imagen de un caso se abre a pantalla completa (versión 2000 px cuando existe). Flechas, teclado y deslizar en celular; tocar para acercar y recorrer el detalle.
- **Anatomía del informe**: los números de la lámina son botones; cada uno abre su descripción. En escritorio la leyenda lateral está sincronizada.
- **Menú en celular**: botón "Menú" bajo 980 px, navegación a pantalla completa.
- **Capacidades**: sección genérica (sirve para cualquier empresa o cliente), cada capacidad enlaza al proyecto que la prueba.

## Sistema de movimiento

Un solo lenguaje: el monograma.

- El anillo se dibuja y la H se arma al cargar.
- El hueco del monograma es una ventana que se abre con el scroll hacia el caso 01.
- El cursor es el anillo del logo.
- El número de cada sección va dentro del anillo con sus dos cortes.
- Los proyectos del archivo se abren como un círculo que crece desde el clic.

Todo respeta `prefers-reduced-motion`. Las animaciones de entrada solo mueven el contenido. Nada queda invisible esperando el scroll.

## Perfil

Retrato dentro del anillo del monograma (blanco y negro, pasa a color con el cursor; a color en pantallas táctiles). Debajo: trayectoria, formación y herramientas tomadas del CV, en el mismo formato de tabla editorial de los casos. La cifra "7 organizaciones" cuenta: Alcaldía de Polonuevo, Universidad del Norte, Corporación Universitaria Americana, Institución Universitaria de Barranquilla, Universidad del Atlántico, Casa de Teatro Ay Macondo y Petromil.

## Pendiente

- El brief llegó cortado en la sección 7 (microinteracciones). Si había requisitos después de ese punto, faltan por revisar.
- Confirmar con Leyder la autorización para publicar sus datos de contacto antes de subir el sitio.
- `og:image` usa una ruta relativa. Al publicar en un dominio, cambiarla a URL absoluta.
