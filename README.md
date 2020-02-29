
<div align="center">

  <h1>Шаблон сборки проекта на webpack 4</h1>

  <a href="https://github.com/webpack/webpack">
    <img width="200" height="200" src="https://webpack.js.org/assets/icon-square-big.svg">
  </a>
  <br>
  <br>
</div>  

---

<h2 align="center">Подготовка проекта</h2>

#### Для работы проекта требуется установленные глобально:

#### * [Node.js](https://nodejs.org/ru/) - среда выполнения JavaScript
#### * [npm](https://www.npmjs.com/) - менеджер пакетов

##### Для начала работы требуется инициализировать проект и установить модули сбоки и сам webpack:

>npm init
>npm install --save-dev

---

<h2 align="center">Описание модулей</h2>

#### В данной сборке используются модули:

        "@babel/core"
        "@babel/preset-env"
        "autoprefixer"
        "babel-loader"
        "copy-webpack-plugin"
        "css-loader"
        "css-mqpacker"
        "cssnano"
        "file-loader"
        "html-webpack-plugin"
        "mini-css-extract-plugin"
        "mqpacker"
        "node-sass"
        "path"
        "postcss-loader"
        "sass-loader"
        "style-loader"
        "webpack"
        "webpack-cli"
        "webpack-dev-server"
        "webpack-merge"
        "vue"

Описание конфигурации плагинов находится в файле package.json находящемся в корне данного проекта.

---

<h2 align="center">Настройка конфигурации проекта</h2>

#### Конфигурационные файлы сборки находятся в директории build в корне проекта.

---

<h2 align="center">Запуск проекта</h2>

#### Запуск разработки:

>npm run dev

#### Запуск сборки:

>npm run build

---

### Подробнее о webpack читать <a href="https://github.com/webpack/webpack">тут</a>
