# Flowjuyu Backend

Backend principal de Flowjuyu, un marketplace enfocado en textiles guatemaltecos, vendedores artesanales y comercios que necesitan publicar, administrar y promocionar sus productos en línea.

Este backend se encarga de manejar la lógica de negocio, autenticación, roles, productos, perfiles de vendedores, analítica, flujos internos y la comunicación con la base de datos.

## Tech Stack

- Node.js
- Express
- TypeScript
- PostgreSQL
- Sequelize
- Firebase Auth
- JWT
- Supabase
- Railway

## Main Features

### Authentication and Sessions

- Firebase Auth integration for user authentication.
- JWT-based backend session validation.
- Role-based access control for `buyer` and `seller`.
- Protected routes for authenticated users.
- Session validation between frontend and backend.

### Seller Management

- Seller profile creation and update.
- Business information management.
- Seller onboarding support.
- Public seller profile data for marketplace pages.
- Seller-specific product ownership validation.

### Product Management

- Product creation, edition, listing and deletion.
- Product ownership validation by seller.
- Product image handling support.
- Product status management.
- Product metadata for marketplace discovery.
- Support for seller SKU and internal product codes.

### Marketplace Taxonomy

- Category, region and fabric selection support.
- Custom values for categories, regions and fabrics.
- Storage of custom taxonomy inputs for future analysis.
- Fields such as:

```txt
categoria_custom
region_custom
tela_custom