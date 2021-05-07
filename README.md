# Primeiro projeto

## Babel
* Babel é o compilador de JS
  * Babel CLI e Core são essenciais pro babel rodar
  * Babel preset-env identifica qual ambiente será rodado para entender quais conversões fazer
  * yarn babel src/index.js -o dist/bundle.js (-o é out-file, qual o arquivo de saída (bundle.js))

## Webpack é o "compilador" de conteudos estáticos (sass, less, jpg, png...)

* Uma boa convenção é usar o path por causa de problemas de compatibilidade de diretorios (windows usa \\ por ex.)

* function render ('elemento a ser renderizado', 'local onde será renderizado')
