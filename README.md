# cf-minimal-digital-archive
Minimal Example of Digital Archive on Cloudflare using Workers, R2, D1

## Frontend
- Workers

- Landing Page
- Search
- Item Details
- Management Dashboard
  - Authorised Login: Better Auth

### Framework
- React Router
- Astro
- Nuxt
- SvelteKit
- Hono

## Backend
- Workers

- Web API
  - Serving IIIF Image API (Level 0; Pre-tiled images +`info.json` )
  - Serving IIIF Presentation API (`manifest.json`)
  - Metadata Search
  - CRUD + Images Management called by Dashboard
 
### Language/Framework
- Hono
- Elysia
- Rust

## Object Storage
- R2: Pre-tiled IIIF Level 0 Images

## Database
- D1 (SQLite + FTS5)
  - Search
  - Metadata
    - Title
    - Author
    - Category
    - size
    - published_at (item itself)
    - created_at (data)
    - updated_at
  - DrizzleORM
