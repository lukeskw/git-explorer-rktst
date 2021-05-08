# Primeiro projeto

## Babel
* Babel é o compilador de JS
  * Babel CLI e Core são essenciais pro babel rodar
  * Babel preset-env identifica qual ambiente será rodado para entender quais conversões fazer
  * yarn babel src/index.js -o dist/bundle.js (-o é out-file, qual o arquivo de saída (bundle.js))

## Webpack é o "compilador" de conteudos estáticos (sass, less, jpg, png...)

* Uma boa convenção é usar o path por causa de problemas de compatibilidade de diretorios (windows usa \\ por ex.)

* function render ('elemento a ser renderizado', 'local onde será renderizado')


## Conceito de imutabilidade
  Diz que uma variável nunca poderá ter seu valor alterado, ela sempre irá receber outro valor!

## UseEffect
  Toda vez que precise tomar alguma ação após a mudança de algo(ex: variavel), usar o useEffect( "qual função executar", "quando executar(array de dependencias)" ) //  useEffect( ()=> {}, [] )
  * array de dependencias
    * vazio = a função dentro do useEffect será executada 1 unica vez assim que o componente for exibido em tela
    * com variáveis = quais informações que quando mudarem, o useEffect vai executar de novo;
