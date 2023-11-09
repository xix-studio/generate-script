# Nx Generate scripts

## Setup a intergrated Node-Angular applications

```bash
npx create-nx-workspace@latest org_name
# application name: frontend
npx nx g @nx/angular:setup-tailwind frontend
npx nx g @nx/express:app backend --directory=apps/backend --e2eTestRunner=none
```
