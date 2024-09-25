
# Billion-updates-in-your-database


## Installation

```bash
$ npm install
```

Create `.env`
```bash
cp .env.example .env
```

Correct values in `.env` for your system. <br>

## Prepare database

```bash
# migrations
npm run migration:run

# fill database with mock users
npm run seed:run
```

## Running the app

```bash
# development
npm run start

# watch mode
npm run start:dev

# production mode
npm run start:prod
```
