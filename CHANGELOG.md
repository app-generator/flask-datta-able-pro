# Change Log

## [1.0.15] 2024-11-30
### Changes

- Update Routes
- Update Dependencies

## [1.0.14] 2024-05-14
### Changes

- Update Links 
- Minor Improvements

## [1.0.13] 2024-05-14
### Changes

- Update Dependencies
- Added Apps
  - DataTables
  - API
  - Charts
  - Celery
  - Media Files Manager

## [1.0.12] 2023-10-08
### Changes

- Update Dependencies

## [1.0.11] 2023-06-09
### Changes

- Bump Codebase Version
- `LIVE Reload` in Docker
- CI/CD via Render
  - `render.yaml`
- DBMS silent fallback to SQLite:
  - `.env` DBMS settings not good or not present
- `CDN` support

## [1.0.10] 2022-06-13
### Fixes

- Docker Scripts
- `elements-ac_tour.html` - fix broken template

## [1.0.9] 2022-06-13
### Improvements

- Built with [Datta Able PRO Generator](https://appseed.us/generator/datta-able-pro/)
  - Timestamp: `2022-06-13 10:57`
- Improved `Auth UX`

## [1.0.8] 2022-05-30
### Fixes

- Fix broken links 
- Fix Assets path (Chart.js was Uppercased)

## [1.0.7] 2022-05-30
### Improvements

- Bump UI to `Datta Able PRO v1.0.0`
- Improved `Docker`
- Improved Codebase
- Page Compression via `Flask-Minify`

## [1.0.6] 2022-04-01
### Fixes

- **Patch ImportError**: [cannot import name 'safe_str_cmp' from 'werkzeug.security'](https://docs.appseed.us/content/how-to-fix/importerror-cannot-import-name-safe_str_cmp-from-werkzeug.security)
  - `Werkzeug` deprecation of `safe_str_cmp` starting with version `2.1.0`
    - https://github.com/pallets/werkzeug/issues/2359

- 2021-11-08 - `v1.0.6-rc1`
  - ImportError: cannot import name 'TextField' from 'wtforms'
    - Problem caused by `WTForms-3.0.0`
    - Fix: use **WTForms==2.3.3**

## [1.0.5] 2021-11-06
### Improvements

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v2.0.0
  - Dependencies update (all packages) 
    - Flask==2.0.1 (latest stable version)
- Better Code formatting
- Improved Files organization
- Optimize imports
- Docker Scripts Update
- Gulp Tooling  (SASS Compilation)

## [1.0.4] 2021-05-16
### Dependencies Update

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.6
- Freeze used versions in `requirements.txt`
    - jinja2 = 2.11.3
    
## [1.0.3] 2020-03-22
### Fixes 

- Bump Codebase: [Flask Dashboard](https://github.com/app-generator/boilerplate-code-flask-dashboard) v1.0.5
- Bump UI: [Jinja Datta PRO](https://github.com/app-generator/jinja-datta-able-pro) v1.0.2

## [1.0.2] 2021-03-18
### Improvements

- Freeze used versions in `requirements.txt`
    - flask_sqlalchemy = 2.4.4
    - sqlalchemy = 1.3.23

## [1.0.1] 2020-12-29
### Improvements & Bug Fixes

- Bump Flask codebase - v1.0.2
- Bump UI - v1.0.0

## [1.0.0] 2020-04-26
### Initial Release
