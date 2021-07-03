-> Verificar se o NodeJS está intaldado
        |-> node -v
        |-> node -version
-> Para instalar o SASS
        |-> npm install -g sass
-> Para verificar a verão
        |-> sass --version

*Como instalar o Sass no seu projeto;
        Para instalar o Sass é necessário possuir o node na sua máquina, e também um editor de código. Depois, basta digitar o comando "npm install -g sass”.
*Como criar e usar variáveis no Sass;
        Para criarmos variáveis usamos o símbolo $, junto dele o nome da variável, e depois dos dois pontos o valor que queremos. E para usá-las simplesmente chamamos o seu nome. Por exemplo: $branco: #fff; para criar e, para usá-la, chamaremos ela dentro da propriedade css, como por exemplo: color: $branco;
*Como comentar o código no Sass;
        Como em outras linguagens de programação, também é possível fazer comentários no Sass. Existem dois tipos: com duas barras (//) ou entre barras e asteriscos (/**/), a diferença entre eles é que no primeiro caso o comentário é por linha, ou seja, caso o enter seja pressionado, o comentário não será continuado, já o segundo permite comentário em múltiplas linhas.


        At Rules


Grande parte das funções extras do Sass vem no formato de At rules, e nesta aula vimos alguns exemplos como mixins, function, import, extend e include, mas existem diversas At Rules:

@use: carrega mixins, functions e variáveis de outras folhas de estilos Sass e combina o CSS de diversas folhas de estilo juntos.

@forward: carrega uma folha de estilo Sass e torna os mixins, functions e variáveis disponíveis quando a folha de estilo é carregada pela regra do @use.

@import: estende as regras de CSS para carregar styles, mixins, functions e variáveis de outras folhas de estilo.

@mixins e @include: facilitam a reutilização de trechos de código.

@function: define funções customizadas que podem ser utilizadas em expressões.

@extend: permite que os seletores herdem estilos uns dos outros.

@at-root: coloca estilos dentro dele na raiz do documento CSS.

@error: faz com que a compilação falhe com uma mensagem de erro.

@warn: imprime um aviso sem parar totalmente a compilação.

@debug: imprime uma mensagem para fins de debugging.

E também fluxos de controle, como: @if, @each, @for e @while.