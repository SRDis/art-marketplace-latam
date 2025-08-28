# Art Marketplace Latam

Marketplace para artistas de América Latina (enfocado en México) que conecta creadores con coleccionistas. Incluye gestión de obras, pagos con Stripe, certificados de autenticidad y guías de envío con Shippo.

## Estructura
- `/client-portal`: Frontend para clientes (browsing, carrito, checkout).
- `/artist-portal`: Frontend para artistas (subida de obras, dashboard).
- `/shared`: Componentes y utilidades compartidas.
- `/docs`: Documentación del proyecto.

## Tecnologías
- Frontend: Next.js 14, Tailwind CSS, Shadcn UI
- Backend: Next.js API Routes, Supabase (Postgres, Auth, Storage)
- Pagos: Stripe Connect
- Envíos: Shippo
- Emails: Resend

## Instalación
1. Clona el repositorio: `git clone <repo-url>`
2. Instala dependencias: `cd client-portal && npm install` (repite para artist-portal)
3. Configura variables de entorno en `.env.local` (ver `.env.example`)

## Desarrollo
- Configura Supabase, Stripe, Shippo y Resend en modo sandbox.
- Usa Vercel para despliegue continuo.

## Contribuir
- Usa ramas para features: `git checkout -b feature/nueva-funcionalidad`
- Haz pull requests a la rama `main`.