# Laravel Deploy

Laravel deploy thingy

## Steps

- [x] User runs  ``` laravel-deploy new {application name}```

Downloads a fresh laravel latest project and extract the zip file and name the file with the application name

- [x] Runs the composer install && npm install && npm run dev
- [x] Update the .env with the database credentials
- [x] Creates apache2 config named with the application name and point the directory to the application directory and domain as {application}.test
- [x] Update windows hosts file with the application.test


And now you should be able to access the application by visiting {application}.test and should see the newly created laravel app

```
composer global require jinas/laravel-deploy
```
