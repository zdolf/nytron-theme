# After theme installation

1. In console navigate to the theme directory and install all needed packages via `npm` command.

`npm install`

2. Run laravel mix command to compile all assets.

`npx mix`

3. Seed all blueprints, languages and data

`php artisan theme:seed <author-themename>`

## Watching SASS and JS file changes

You can run watch command while styling the theme to automatically compile you assets.

`npm mix watch`
