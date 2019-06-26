#Angular-electron

Base d'un projet pour une application bureau avec Electron et Angular

C'est plus facile que vous ne le pensez

Si vous savez développer un site, alors vous savez développer une application desktop. Electron est un framework pour créer des applications natives avec les technologies web comme JavaScript, HTML et CSS. Electron s'occupe de la partie technique pour que vous puissiez vous concentrer sur le cœur de votre application. https://electronjs.org/

##Lancer l'application

Pour lancer l'application, exécuter "npm run electron-build". /!\ Il n'a pas de rafraichissement automatique, il faut développer avec angular et la commande "ng serve".

##Construire un package pour une application bureau

npm install electron-packager -g npm install electron-packager --save-dev

##Construire un installateur avec Windows electron-packager . --platform=win32

ça va générer le dossier /angular-electron-win32-x64/

##Construire un installateur avec MAC OS electron-packager . --platform=darwin

ça va générer le dossier /angular-electron-darwin-x64/
