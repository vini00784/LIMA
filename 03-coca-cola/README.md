# Projeto Coca-Cola

## Tags semânticas
* HEADER (cabeçalho)
* MAIN (parte principal)
* FOOTER (rodapé)

## Tags genéricas ("sem" significado)
* DIV (se comporta como um cômodo de uma casa, pode contar até outras DIV's)
* SPAN (pequenos textos ou ícones)

## Seletores
* https://flukeout.github.io/

* "*"   --> universal, ou seja, seleciona tudo
* Seletor por Tag --> nome da tag (body, main, header e etc)
* Seletor por classe --> nome da classe (.menu / .icone_menu e etc)
* Seletor por ID --> nome do ID (#titulo), somente um item pode conter um ID, pois ele é único, como um CPF

* A,B --> seleciona todos os elementos do A e do B, exemplo: (bento, plate) --> seleciona tudo dentro de "bento' e tudo dentro de "plate"
* A * --> combinação com o seletor universal, exemplo: (plate *), seleciona tudo dentro de plate
* A + B --> seleciona *APENAS* o elemento B que segue diretamente A, exemplo: (plate + apple), seleciona o próximo "apple" que possui o mesmo nível de plate.
* A ~ B --> seleciona *TODOS* os "irmãos" de um elemento. Isso é como o Seletor Adjacente (A + B), exceto que obtém todos os seguintes elementos em vez de um, exemplo: (bento ~ pickle), seleciona todo pickle que segue o bento.
* A > B --> seleciona os elementos que são filhos diretos de outros elementos, exemplo: (plate > apple), seleciona toda "apple" que está *DENTRO* de plate.

## Display: flex (flex-box)
* https://flexboxfroggy.com/
* A propriedade CSS display especifica o tipo de caixa de renderização usada por um elemento.
* Com o valor flex: o elemento se comporta como um elemento de bloco e apresenta seu conteúdo de acordo com o modelo flexbox.

* flex-direction: column - coluna
* flex-direction: row - linha

* Os itens abaixo dependem de como o flex-direction está, ou seja, se estiver column, o eixo principal é vertical, se estiver row, o eixo principal é horizontal
* justify-content: eixo principal
* align-items: eixo secundário