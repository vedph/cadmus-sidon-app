# Cadmus Sidon App

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.2.

## Docker

1. update version in `src/env.js`.
2. `ng build --configuration production`
3. `docker build . -t vedph2020/cadmus-sidon-app:3.0.0 -t vedph2020/cadmus-sidon-app:latest` (replace with the current version).

Production:

(1) build as above.
(2) change `dist/env.js` so that it looks like this:

```js
// https://www.jvandemo.com/how-to-use-environment-variables-to-configure-your-angular-application-without-a-rebuild/
(function (window) {
  window.__env = window.__env || {};

  // environment-dependent settings
  window.__env.apiUrl = "https://cadmus-sidon.fusi-soft.com/api/";
  window.__env.version = '1.0.4-prod';
})(this);
```

(3) `docker build . -t vedph2020/cadmus-sidon-app:1.0.4-prod`.

## History

- 2023-11-11:
  - ⚠️ upgraded to Angular 17.
  - opted in for flags editor.
  - opted in for thesauri import.
- 2023-07-02:
  - updated Angular and packages.
  - migrated to PostgreSQL.
- 2023-03-16: updated Angular and packages.

### 2.0.2

- 2023-02-05: updated Angular and packages.

### 2.0.1

- 2022-12-19: updated Cadmus packages.

### 2.0.0

- 2022-12-17:
  - upgraded to Angular 15.
  - replaced Akita with ELF.
- 2022-11-10: updated Angular and packages.
- 2022-10-10: more preview styles.
- 2022-10-05:
  - updated packages.
  - added [preview infrastructure](https://github.com/vedph/cadmus_doc/blob/master/guide/adding-preview.md).

### 1.0.4

- 2022-09-28: updated packages.

### 1.0.3

- 2022-09-08: upgraded Angular.

### 1.0.2

- 2022-09-05: added orthography layer.
- 2022-09-04: updated packages.
- 2022-08-18: updated packages.
- 2022-07-15: upgraded to Angular 14.
- upgraded Angular and Cadmus packages.

### 1.0.1

- initial release.
