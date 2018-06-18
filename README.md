## A Name Builder Helper for Projects

### Install and Run
```
npm install
```
```
npm start
```

### Distributing
When you're ready to distribute the goods, run the below command. This will compile/transpile/minimize everything and place all in the ```dist/``` folder.
```
gulp build-dist
```

### Gulp Tasks
Gulp tasks will run automatically but to manually run them:

Building Javascript: This will concat the js files together in order by name:
```
gulp build-js
```

Building SASS
```
gulp build-sass
```

Compressing Images
```
gulp build-images
```

Using Node Modules on the client
```
gulp build-node-modules
```

### Testing
Create your ```*.spec.js``` files as needed inside ```src/js/*```
```
npm run test
```
