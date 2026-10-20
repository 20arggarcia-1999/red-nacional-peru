# Red Nacional del Perú

Mapa interactivo del diseño de la Red Nacional del Perú (RNP), trabajo final del curso Conectividad de Redes 02.

**Página:** https://20arggarcia-1999.github.io/red-nacional-peru/

La página muestra el diseño en ocho vistas:

- **Anillos:** los 9 anillos de fibra.
- **Core:** los 11 nodos core en los cruces de anillos.
- **Lógica:** las 27 conexiones de 100 Gbit/s.
- **Agregación:** los 22 nodos con doble subida.
- **Distribución:** las 180 capitales de provincia.
- **Direcciones:** el plan de direccionamiento.
- **Fallas:** simulación de caídas.
- **Simulación:** la maqueta en GNS3, con 30 routers configurados y 14 encendidos por escenario.

Para abrir una vista directamente, agrega su nombre al enlace, por ejemplo `#simulacion` o `#logica`.

Es un archivo HTML único, sin dependencias aparte de las fuentes de Google Fonts.

## Fuentes y notas

- Límites departamentales y capitales: INEI e IDEP, a través del repositorio [juaneladio/peru-geojson](https://github.com/juaneladio/peru-geojson).
- Requisitos técnicos: Anexo N.° 1 del trabajo final.
- Los prefijos públicos y los números de AS son rangos reservados para documentación (RFC 5737 y RFC 5398).
- Elaborado con asistencia de inteligencia artificial generativa. El contenido técnico debe validarse con el docente del curso.
