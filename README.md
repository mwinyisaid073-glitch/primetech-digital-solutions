# Primetech Digital Solutions

Complete starter project containing:

- `frontend/` - HTML/CSS/JavaScript website suitable for GitHub Pages.
- `backend/` - PHP API starter for PHP/MySQL hosting.
- `database/schema.sql` - MySQL database structure.

## GitHub Pages

Upload the **contents of `frontend/`** to the root of your GitHub repository so that `index.html` is in the repository root. Then enable:

Settings -> Pages -> Deploy from a branch -> main -> /root.

The backend cannot run on GitHub Pages because GitHub Pages is static hosting.

## MySQL/PHP

Import `database/schema.sql` into MySQL on your PHP hosting, then edit:

`backend/api/config.php`

with your database username and password.

## Important security note

The frontend demo login (`admin` / `admin123`) is only for demonstrating the interface. Do not use that password in a real deployment. The PHP backend uses password hashes and should be connected to a proper session/authentication system before production use.
