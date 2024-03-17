FIP Sign
===

_Une aide pour emmarger en FIP + TAF._

## Commencer à développer
L'appli se base sur le framework [Vue.js](https://fr.vuejs.org) et [Node](https://nodejs.org/) pour le développement et le build.

### Tester l'application 

```bash
$ npm install
$ npm run dev
```

### Déployer et vérifier l'application

```bash
$ npm run build
$ npm run preview
```

## Déployer l'application avec Docker

```bash
$ docker build -t fip_sign -f docker/Dockerfile .
$ docker run -p 8080:80 fip_sign
```

# Copyrights
Some assets used in this repository might be copiryghted. There is no intention to use them without permission. If you are the owner of these assets and whant them removed, plese contact me.