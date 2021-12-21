# CMS with Graphql

Simple GraphQL server built with [Strapi@v3](https://docs-v3.strapi.io).

## Development setup

1. Install dependencies `npm install`
2. Run development server `npm run develop`
3. Open [Admin panel](http://localhost:1337/admin) and register admin account
4. Go to [User role settings](http://localhost:1337/admin/settings/users-permissions/roles) and set permissions to "select all" for collections:
  - Employee
  - Project
5. Go to [Content Manager](http://localhost:1337/admin/content-manager) and create new entries
6. PROFIT!

## Links

- Admin panel http://localhost:1337/admin
- GraphQL playground http://localhost:1337/graphql
