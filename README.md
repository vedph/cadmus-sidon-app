# Cadmus Sidon App

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.1.3.

## Docker

1. update version in `src/env.js`.
2. `ng build --configuration production`.
3. `docker build . -t vedph2020/cadmus-sidon-app:4.0.0 -t vedph2020/cadmus-sidon-app:latest` (replace with the current version).

## Setup

```sh
ng new cadmus-sidon-app
cd cadmus-sidon-app
ng add @angular/material
ng add @angular/localize

npm i @auth0/angular-jwt @myrmidon/auth-jwt-admin @myrmidon/auth-jwt-login @myrmidon/cadmus-api @myrmidon/cadmus-core @myrmidon/cadmus-graph-ui @myrmidon/cadmus-graph-pg @myrmidon/cadmus-item-editor @myrmidon/cadmus-item-list @myrmidon/cadmus-item-search @myrmidon/cadmus-part-general-pg @myrmidon/cadmus-part-general-ui @myrmidon/cadmus-part-philology-pg @myrmidon/cadmus-part-philology-ui @myrmidon/cadmus-preview-pg @myrmidon/cadmus-preview-ui @myrmidon/cadmus-profile-core @myrmidon/cadmus-refs-asserted-chronotope @myrmidon/cadmus-flags-pg @myrmidon/cadmus-flags-ui @myrmidon/cadmus-refs-asserted-ids @myrmidon/cadmus-refs-assertion @myrmidon/cadmus-refs-decorated-ids @myrmidon/cadmus-refs-doc-references @myrmidon/cadmus-refs-external-ids @myrmidon/cadmus-refs-historical-date @myrmidon/cadmus-mat-physical-size @myrmidon/cadmus-refs-lookup @myrmidon/cadmus-refs-proper-name @myrmidon/cadmus-state @myrmidon/cadmus-text-block-view @myrmidon/cadmus-thesaurus-editor @myrmidon/cadmus-thesaurus-list @myrmidon/cadmus-thesaurus-ui @myrmidon/cadmus-ui @myrmidon/cadmus-ui-pg @myrmidon/ngx-mat-tools @myrmidon/ngx-tools @myrmidon/paged-data-browsers ts-md5 @myrmidon/cadmus-text-ed @myrmidon/cadmus-text-ed-md @myrmidon/cadmus-text-ed-txt --force
```

## History

### 4.0.0

- 2025-02-05: updated packages.
- 2025-01-31:
  - ⚠️ upgraded to Angular 19.
  - ⚠️ migrated to standalone and signals.

### 3.0.0

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
