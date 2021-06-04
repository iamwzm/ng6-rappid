# JointJS + Rappid + angular6 (Demo)

使用的 angular-cil: 6.0.8

## node_modules:
`npm install lodash@3.10.1 --save`

`npm install @types/lodash@3.10.1 --save-dev`

`npm install backbone --save`

`npm install @types/backbone@1.3.3 --save-dev`

`npm i jquery@3.3.1 --save`

`npm install @types/jquery@3.3.1 --save-dev`

##### 上面的版本不一定正确，慎用

Include in angular.json:

    <!-- Rappid/JointJS dependencies: -->
                "assets": [
                  "src/favicon.ico",
                  "src/assets"
                ],
                "styles": [
                  "src/styles.css",
                  "src/vendor/css/rappid.css"
                ],
                "scripts": [
                  "node_modules/jquery/dist/jquery.js",
                  "node_modules/lodash/index.js",
                  "node_modules/backbone/backbone.js",
                  "src/vendor/js/rappid.min.js"
                ]



## 温馨提示:

如果高于angular-cil(6.0.8)慎用(因为这个版本还是累死累活从 angular.js 迁移过来的，其中借鉴了不少)
