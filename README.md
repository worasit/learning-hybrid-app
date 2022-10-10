# Learning Hybrid Application Development

- https://ionicframework.com/docs/react
- https://capacitorjs.com/docs/getting-started
- https://ionicframework.com/docs/react/your-first-app

## Set up

- https://ionicframework.com/start
- https://dashboard.ionicframework.com/app/b7f472e5/getting-started
    ```shell
    sudo chown -R $(whoami) /usr/local/{lib/node_modules,bin,share}
    sudo chown -R $(whoami) ~/.npm ~/.npmrc
    npm install -g @ionic/cli native-run cordova-res
    ionic start photo-gallery tabs --type=react --capacitor
    ```

Your Ionic app is ready! Follow these next steps:

- Go to your new project: cd ./photo-gallery
- Run ionic serve within the app directory to see your app in the browser
- Run ionic capacitor add to add a native iOS or Android project using Capacitor
- Generate your app icon and splash screens using cordova-res --skip-config --copy
- Explore the Ionic docs for components, tutorials, and more: https://ion.link/docs
- Building an enterprise app? Ionic has Enterprise Support and Features: https://ion.link/enterprise-edition

## Deploying to iOS and Android

```shell
ionic build
```