# Boilerplate to start generic projects with React-Mative

## Install & run
```
# Terminal
0. Clone the repository (set project name)
1. navigate to PATH
2. Change 'name' in package.json and 'name'/'displayName in app.json
3. remove ios and android folder (/path_to_your_old_project/ios)
4. init a new project react-native init project_name
5. copy ios and android folder
6. navigate to ios folder
7. run pod install
8. return to root path project
9. run yarn
10. run react-native run-ios

or
3. run react-native run-android


## if you need to start your project and clear cache
react-native start --reset-cache
```


# Steps to create this same boilerplate

## 1. Start a new project
```
# Terminal
npx react-native init <project-name>

```

## 2. add eslint and prettier to project and create estlint file
```
# Terminal

## YARN
yarn add eslint -D

yarn estlint --init
(javascript modules->react->airbnb styleguide)

exclude package.lock
run yarn


## PRETTIER
yarn add prettier eslint-config-prettier eslint-plugin-prettier babel-eslint -D

```

## 3. root import (to use ~ to define root path)
```
# Terminal

yarn add babel-plugin-root-import eslint-import-resolver-babel-plugin-root-import -D

Configure eslint, babel.config.js and creaet jsconfig.json
```

## 4. Add React navigation
https://reactnavigation.org/docs/getting-started
```
yarn add @react-navigation/native

yarn add react-native-reanimated react-native-gesture-handler react-native-screens react-native-safe-area-context @react-native-community/masked-view

npx pod-install ios

import in index.js
import 'react-native-gesture-handler';

run react-native start-ios
(to install dependences)
```
