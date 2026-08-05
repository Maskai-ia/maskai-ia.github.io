# Nykoll Ortiz · Carta de presentación

Sitio personal de **Nykoll Ortiz** — CRM Specialist · Automation · Data Operations.
Publicado con **GitHub Pages** en **https://maskai-ia.github.io**

> Esta es mi página web. El código vive en este mismo repositorio (`index.html`).
> Cuando alguien entra a la web, GitHub sirve este archivo tal cual.

---

## Qué es

Una carta de presentación de una sola página, bilingüe (español / inglés), pensada
para posicionarme ante empresas y clientes freelance que buscan especialistas en
HubSpot, CRM, automatización, operaciones comerciales y análisis de datos.

**Estilo:** "Dossier editorial". Fondo papel cálido, tinta negra, guinda sangre
(#B81C2A) como acento, tipografías Playfair Display (títulos) + DM Sans (cuerpo) +
Space Mono (etiquetas y datos). Índice lateral que te sigue al hacer scroll, reglas
finas y secciones numeradas. Logo: fueguito estilo Calcifer en pixel.

Todo el contenido está anclado a mi CV y a mis repositorios reales. Los casos de
estudio están anonimizados por rubro (sin nombres de clientes).

---

## Estructura del sitio

| Sección | Contenido |
|---|---|
| Masthead | Nombre, rol, propuesta de valor, panel CRM ilustrativo animado |
| Elevator pitch | Resumen de 30s + indicadores (años, marcas, clientes, UPC, inglés) |
| N°01 Perfil | Quién soy + tarjeta de identidad + stack técnico |
| N°02 Especialidades | CRM, Automatización, Data/BI, Growth |
| N°03 Casos | 4 casos anonimizados (problema, proceso, stack, resultado) |
| N°04 Trayectoria | Experiencia profesional |
| N°05 Proyectos & publicaciones | Repos de GitHub + carruseles de LinkedIn |
| N°06 Contacto | LinkedIn, GitHub, email |

---

## Cómo se hizo (sin frameworks)

- Un solo archivo `index.html` con HTML, CSS y JavaScript en línea.
- Sin librerías externas, sin dependencias, sin build. Carga rápido.
- Bilingüe con un toggle ES/EN (guarda la preferencia en `localStorage`).
- Accesible: `skip link`, foco visible, un solo `<h1>`, textos alternativos.
- Respeta `prefers-reduced-motion` (desactiva animaciones si el sistema lo pide).
- Responsive: en móvil el índice lateral se vuelve un menú.

## Cómo editar

1. Abre `index.html`.
2. El contenido en español está en `<span class="l-es">` y el inglés en
   `<span class="l-en">`. Edita ambos.
3. Los colores y tipografías están en las variables CSS `:root` (arriba del archivo).
4. Guarda y súbelo a GitHub (ver abajo). La web se actualiza sola en ~1 minuto.

## Cómo desplegar

GitHub Pages ya está activo en la rama `main`. Para publicar un cambio:

```bash
git add index.html
git commit -m "actualizo la web"
git push
```

En ~1 minuto queda en https://maskai-ia.github.io

---

## Historial de versiones

Guardo copias de cada rediseño en la carpeta local `~/Downloads/maskai-site/versions/`
y en el historial de git:

- **v1** — hero oscuro (descartado, muy oscuro).
- **v2** — claro + tarjeta de presentación.
- **v3** — claro + dashboard animado + elevator pitch.
- **v4** — Dossier editorial (versión actual). Sin "slop" de IA: fuera gradientes,
  blobs y botones píldora; entra tipografía mono, índice tipo ledger y reglas finas.

---

© 2026 Nykoll Ortiz · Lima, Perú
