# Change Log

## [1.0.17] 2022-08-17
### Fixes & Improvements

- Update API (minor)
- List TOKEN_API in user profile page
- Patch Twitter OAuth Blueprint

## [1.0.16] 2022-08-17
### Fixes

- Patch Twitter OAuth Flow
  - SIGN-IN page was always hidden 

## [1.0.15] 2022-07-28
### Fixes

- `Users List` (Admin only view)
  - Fix Users Deletion 
- JS (Minor) Fixes
  - Patch all JS Browser Warnings 

## [1.0.14] 2022-07-28
### Improvements & Fixes

- Update password Improvements
- Change Password Improvements
- Fix JS Errors (Browser Console)

## [1.0.13] 2022-07-20
### Fixes

- Patch Docker (now includes latest evolutions)
  - Starts with `SQLite` 

## [1.0.12] 2022-07-20
### Improvements

- Auth Features
  - Change password
  - Self Account Deletion
- API via Flask-RestX
  - Path: `/api/` 
  - Products, Sales models 

## [1.0.11] 2022-07-19
### Improvements

- Added Social Login 
  - Github & Twitter
- Persistent Dark Mode  

## [1.0.10] 2022-06-22
### Improvements

- Improve error checking on FTP IMG Upload
  - Added test CMD: `flask test_ftp`
  - UI is showing the status
- Added Unitary tests
  - `python.exe run.py tests`  

## [1.0.9] 2022-06-15
### Improvements

- Improved Authentication
  - Force strong passwords during registration
  - Suspend user after 3 failed login attempts
- New Feature: `User Profiles`
  - Extended User profile
  - Added Superusers
  - Image upload via `FTP`

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
