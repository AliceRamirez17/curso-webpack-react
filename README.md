# curso-webpack-react

Pasos para configurar Webpack 5 en un proyecto de React

1. Crear el archivo package.json

```
npm init -y
```

2. Instalación de react y react-dom

```
npm install react react-dom
```

3. Armado de Boilerplate básico

```text
.
├── README.md
├── package.json
├── package-lock.json
├── .gitignore
├── .babelrc
├── webpack.config.js
├── src
|  ├── components
|     └── App.jsx
├── styles
|     └── global.scss
|  └── index.html
└── public
   └── index.html

```

4. Instalación de Babel

```
npm install @babel/core @babel/preset-env @babel/preset-react babel-loader -D
```

5. Configuración básica de .babelrc

6. Instalación de webpack, webpack-cli y webpack-dev-server -D

7. Configuración básica de webpack en webpack.config.js

8. Instalación de html-loader y html-webpack-plugin

```
npm install html-loader html-webpack-plugin -D
```

9. Configuración de scripts en package.json

10. Agregar la configuración del plugin html-webpack-plugin en webpack.config.js
11. Instalar sass, compilador de css y loader de css y sass

```
npm install mini-css-extract-plugin css-loader style-loader sass sass-loader -D
```

12. Agregar la configuración del plugin mini-css-extract-plugin en webpack.config.js

13. Instalar plugins para optimar los archivos css, js y generar un código más limpio

```
npm install css-minimizer-webpack-plugin terser-webpack-plugin clean-webpack-plugin -D
```

14. Agregar la configuración de css-minimizer, terser-plugin y clean-plugin
