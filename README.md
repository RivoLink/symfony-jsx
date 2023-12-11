## Symfony JSX

### Config env.
```sh
cp .env .env.local
nano .env.local
```

### Install dependencies
```sh
symfony composer install

yarn install
yarn encore dev
```

### Start server
```sh
symfony serve --port=8787
symfony open:local
```

### Access to user datatable
```sh
https://127.0.0.1:8787/command
```
