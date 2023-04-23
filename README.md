# typescript-rest-with-token-authorisation

## Installing

### .env

```bash
cp .env.example .env
```

Change values.

### Packages

```bash
npm clean-install
```

### db

```bash
npx prisma generate
npx prisma migrate dev --name "init"
```

## Running

```bash
npm run dev
```
