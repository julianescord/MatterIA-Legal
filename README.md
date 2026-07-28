# MatterIA — Legal

Sitio web oficial de documentación legal de MatterIA.

Este repositorio contiene las páginas públicas de:

* Política de Privacidad: `/policy`
* Términos y Condiciones: `/terms`

## URLs

* https://matter-ia.dev/policy
* https://matter-ia.dev/terms

## Arquitectura

El sitio está diseñado para ser desplegado mediante Cloudflare Pages.

```text
GitHub
   │
   ▼
matter-ia-legal
   │
   ▼
Cloudflare Pages
   │
   ▼
matter-ia.dev
   │
   ├── /policy
   └── /terms
```

Los servicios operativos de MatterIA se encuentran en subdominios independientes:

* `crm.matter-ia.dev`
* `n8n.matter-ia.dev`

Este repositorio no contiene credenciales, claves API ni información privada de usuarios.

## Estructura

```text
.
├── README.md
├── index.html
├── policy/
│   └── index.html
└── terms/
    └── index.html
```

## Despliegue

El proyecto puede desplegarse directamente desde GitHub mediante Cloudflare Pages.

No requiere un proceso de compilación.

### Build command

```text
Ninguno
```

### Build output directory

```text
/
```

El sitio utiliza HTML y CSS estándar y no requiere Node.js, npm ni ningún framework.

## Mantenimiento

Las páginas legales deben mantenerse actualizadas cuando cambien:

* Los servicios ofrecidos por MatterIA.
* Los proveedores tecnológicos utilizados.
* Las prácticas de tratamiento de datos.
* Los canales de comunicación.
* Los mecanismos de acceso a servicios Premium.
* Las condiciones comerciales.

Las modificaciones relevantes deben reflejarse tanto en la Política de Privacidad como en los Términos y Condiciones cuando corresponda.
