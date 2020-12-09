# Laravel Deploy

Laravel deploy thingy

## Steps

- [ ] User runs  ``` laravel-deploy new {application name}```

Downloads a fresh laravel latest project and extract the zip file and name the file with the application name

- [ ] Runs the composer install && npm install && npm run dev
- [ ] Update the .env with the database credentials
- [ ] Creates apache2 config named with the application name and point the directory to the application directory and domain as {application}.test
- [ ] Update windows hosts file with the application.test


And now you should be able to access the application by visiting {application}.test and should see the newly created laravel app
