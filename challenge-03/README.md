# Desafio da semana #3

```js
// Declarar uma variável qualquer, que receba um objeto vazio.
 var objeto = { }

/*
Declarar uma variável `pessoa`, que receba suas informações pessoais.
As propriedades e tipos de valores para cada propriedade desse objeto devem ser:
- `nome` - String
- `sobrenome` - String
- `sexo` - String
- `idade` - Number
- `altura` - Number
- `peso` - Number
- `andando` - Boolean - recebe "falso" por padrão
- `caminhouQuantosMetros` - Number - recebe "zero" por padrão
*/
> var pessoa ={nome: 'Paulo' , sobernome: 'victor', sexo: ' masculino', idade: 29, altura:1.71, peso:95 ,andando:false, caminhou: 0 }
undefined
> pessoa
{
  nome: 'Paulo',
  sobernome: 'victor',
  sexo: ' masculino',
  idade: 29,
  altura: 1.71,
  peso: 95
  andando: false
  caminhou:0
}

/*
Adicione um método ao objeto `pessoa` chamado `fazerAniversario`. O método deve
alterar o valor da propriedade `idade` dessa pessoa, somando `1` a cada vez que
for chamado.
*/
pessoa.fazeraniversario = function ( ){
.... pessoa.idade++
.... }
pessoa.fazeraniversario++()
/*


Adicione um método ao objeto `pessoa` chamado `andar`, que terá as seguintes
características:
- Esse método deve receber por parâmetro um valor que representará a quantidade
de metros caminhados;
- Ele deve alterar o valor da propriedade `caminhouQuantosMetros`, somando ao
valor dessa propriedade a quantidade passada por parâmetro;
- Ele deverá modificar o valor da propriedade `andando` para o valor
booleano que representa "verdadeiro";
*/
 pessoa.andar = function(metros) {
... pessoa.caminhou =+metros;
... pessoa.andando = true;
... }

/*
Adicione um método ao objeto `pessoa` chamado `parar`, que irá modificar o valor
da propriedade `andando` para o valor booleano que representa "falso".
*/
? pessoa.parar = function (){
... pessoa.andando = false:
pessoa.andando = false;
}
                      ^

/*
Crie um método chamado `nomeCompleto`, que retorne a frase:
- "Olá! Meu nome é [NOME] [SOBRENOME]!"
*/pessoa.nomeCompleto = function(){
return 'ola ! Meu nome é ' + pessoa.nome+' ' + pessoa.sobrenome + '!' ;}
?

/*
Crie um método chamado `mostrarIdade`, que retorne a frase:
- "Olá, eu tenho [IDADE] anos!"
*/
 pessoa.mostraridade = function(){
... return 'ola eu tenho' + pessoa.idade + ' anos!;
return 'ola eu tenho' + pessoa.idade + ' anos!}

/*
Crie um método chamado `mostrarPeso`, que retorne a frase:
- "Eu peso [PESO]Kg."
*/ pessoa.mestrorpeso = function(){
... return 'ola meu peso e' + pessoa.peso + KG.}
?

/*
Crie um método chamado `mostrarAltura` que retorne a frase:
- "Minha altura é [ALTURA]m."
*/pessoa.mostraraltura = function(){
return 'ola minha altura é ' + pessoa.altura + m}
?

/*
Agora vamos brincar um pouco com o objeto criado:
Qual o nome completo da pessoa? (Use a instrução para responder e comentários
inline ao lado da instrução para mostrar qual foi a resposta retornada)
*/
 ola meu nome e Paulo Victor !

/*
Qual a idade da pessoa? (Use a instrução para responder e comentários
inline ao lado da instrução para mostrar qual foi a resposta retornada)
*/
ola eu tenho 29 anos

/*
Qual o peso da pessoa? (Use a instrução para responder e comentários
inline ao lado da instrução para mostrar qual foi a resposta retornada)
*/
 eu tenho 95kg.

/*
Qual a altura da pessoa? (Use a instrução para responder e comentários
inline ao lado da instrução para mostrar qual foi a resposta retornada)
*/
 minha altura é 1.71

/*
Faça a `pessoa` fazer 3 aniversários.
*/
pessoa.fazeraniversario()
29
pessoa.fazeraniversario()
30
pessoa.fazeraniversario()
31
/*
Quantos anos a `pessoa` tem agora? (Use a instrução para responder e
comentários inline ao lado da instrução para mostrar qual foi a resposta
retornada)
*/
ola eu tenho 31 anos

/*
Agora, faça a `pessoa` caminhar alguns metros, invocando o método `andar` 3x,
com metragens diferentes passadas por parâmetro.
*/
?>  pessoa.andar(100)
undefined
> pessoa.andar(200)
undefined
> pessoa.andar(300)
undefined
> pessoa.andando
true
>

/*
A pessoa ainda está andando? (Use a instrução para responder e comentários
inline ao lado da instrução para mostrar qual foi a resposta retornada)
*/
?

/*
Se a pessoa ainda está andando, faça-a parar.
*/
pessoa.andando; false

/*
E agora: a pessoa ainda está andando? (Use uma instrução para responder e
comentários inline ao lado da instrução para mostrar a resposta retornada)
*/
nao

/*
Quantos metros a pessoa andou? (Use uma instrução para responder e comentários
inline ao lado da instrução para mostrar a resposta retornada)
*/
600 mts

/*
Agora vamos deixar a brincadeira um pouco mais divertida! :D
Crie um método para o objeto `pessoa` chamado `apresentacao`. Esse método deve
retornar a string:
********
- pessoa.apresentacao = function(){
return "Olá, eu sou o [NOME COMPLETO], tenho [IDADE] anos, [ALTURA], meu peso é [PESO] e, só hoje, eu já caminhei [CAMINHOU QUANTOS METROS] metros!"
}


Só que, antes de retornar a string, você vai fazer algumas validações:
- Se o `sexo` de `pessoa` for "Feminino", a frase acima, no início da
apresentação, onde diz "eu sou o", deve mostrar "a" no lugar do "o";
- Se a idade for `1`, a frase acima, na parte que fala da idade, vai mostrar a
palavra "ano" ao invés de "anos", pois é singular;
- Se a quantidade de metros caminhados for igual a `1`, então a palavra que
deve conter no retorno da frase acima é "metro" no lugar de "metros".
- Para cada validação, você irá declarar uma variável localmente (dentro do
método), que será concatenada com a frase de retorno, mostrando a resposta
correta, de acordo com os dados inseridos no objeto.
*/
- pessoa.apresentacao = function(){
var sexo = 'o';
if ( pessoa.sexp === 'feminino' ) {
sexo = 'a'
}
if (pessoa.idade ===1 ){
idadeanos = 'ano';
^}
if(pessoa.caminhar === 1 ){
metroscaminhar = 'metros ';
}
return "Olá, eu sou o'+ sexo +', '+pessoa.nome + 'tenho ' +pessoa.idade+ anos, '+ pessoa.altura'+, meu peso é '+pessoa.peso'+ e, só hoje, eu já caminhei '+pessoa.caminhou'+ metros!"

// Agora, apresente-se ;)
?
```
