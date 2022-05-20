# Desafio da semana #4

```js
/*
Declare uma variável chamada `isTruthy`, e atribua a ela uma função que recebe
um único parâmetro como argumento. Essa função deve retornar `true` se o
equivalente booleano para o valor passado no argumento for `true`, ou `false`
para o contrário.
*/
>var istruthy = function () {
return a ? true : false ;
}
istruthy ()
false

// Invoque a função criada acima, passando todos os tipos de valores `falsy`.

istruthy( undefind );
istruthy( null );
istruthy( NaN );
istruthy( 0 );
istruthy( -0 );
istruthy( ' ' );
istruthy( false );


Invoque a função criada acima passando como parâmetro 10 valores `truthy`.
*/
istruthy( 1 );
istruthy(  2);
istruthy( 3 );
istruthy( 4 );
istruthy( 5 );
istruthy( 6 );
istruthy( 7 );
istruthy( 8 );
istruthy( 9 );
istruthy( 10 );


/*
Declare uma variável chamada `carro`, atribuindo à ela um objeto com as
seguintes propriedades (os valores devem ser do tipo mostrado abaixo):
- `marca` - String
- `modelo` - String
- `placa` - String
- `ano` - Number
- `cor` - String
- `quantasPortas` - Number
- `assentos` - Number - cinco por padrão
- `quantidadePessoas` - Number - zero por padrão
*/
> var carro = { marca: ' GM',
... cor:'branca',
... ano:' 2015',
... modelo: 'cobalt',
... placa:'a a a ',
... quantidadeDePessoas: 0,
... quantidadeDeAssentos: 5,
... }


/*
Crie um método chamado `mudarCor` que mude a cor do carro conforme a cor
passado por parâmetro.
*/
> carro.mudarcor = function ( cor ){
... carro.cor = cor;

/*
Crie um método chamado `obterCor`, que retorne a cor do carro.
*/
carro.obtercor = funtion( obter){
 return carro.cor;
}

/*
Crie um método chamado `obterModelo` que retorne o modelo do carro.
*/
> carro.obtermodelo = function(){

retturn carro.modelo;
}

/*
Crie um método chamado `obterMarca` que retorne a marca do carro.
*/
carro.obtermarca = function (){
return carro.marca
}

/*
Crie um método chamado `obterMarcaModelo`, que retorne:
"Esse carro é um [MARCA] [MODELO]"
Para retornar os valores de marca e modelo, utilize os métodos criados.
*/
 carro.obtermarcaModelo = function (){
 return 'esse carro é um '+carro.obtermarca()+ '+ carro.obtermodelo+';
 }
 
 
 
Crie um método que irá adicionar pessoas no carro. Esse método terá as
seguintes características:
- Ele deverá receber por parâmetro o número de pessoas entrarão no carro. Esse
número não precisa encher o carro, você poderá acrescentar as pessoas aos
poucos.
- O método deve retornar a frase: "Já temos [X] pessoas no carro!"
- Se o carro já estiver cheio, com todos os assentos já preenchidos, o método
deve retornar a frase: "O carro já está lotado!"
- Se ainda houverem lugares no carro, mas a quantidade de pessoas passadas por
parâmetro for ultrapassar o limite de assentos do carro, então você deve
mostrar quantos assentos ainda podem ser ocupados, com a frase:
"Só cabem mais [QUANTIDADE_DE_PESSOAS_QUE_CABEM] pessoas!"
- Se couber somente mais uma pessoa, mostrar a palavra "pessoa" no retorno
citado acima, no lugar de "pessoas".
*/
?

/*
Agora vamos verificar algumas informações do carro. Para as respostas abaixo,
utilize sempre o formato de invocação do método (ou chamada da propriedade),
adicionando comentários _inline_ ao lado com o valor retornado, se o método
retornar algum valor.

Qual a cor atual do carro?
*/
carro.obtercor();//azul

// Mude a cor do carro para vermelho.
?
carro.mudarcor (' vermelho');

// E agora, qual a cor do carro?
 carro.obtercor(); //'vermelho'

// Mude a cor do carro para verde musgo.
?carro.mudarcor(' verde musgo');

// E agora, qual a cor do carro?
?
carro.obtercor(); // 'verde musgo'

// Qual a marca e modelo do carro?
carro.obtermarcaModelo(); // 'GM cobalt'
'
// Adicione 2 pessoas no carro.
?

// Adicione mais 4 pessoas no carro.
?

// Faça o carro encher.
?

// Tire 4 pessoas do carro.
?

// Adicione 10 pessoas no carro.
?

// Quantas pessoas temos no carro?
?
```
