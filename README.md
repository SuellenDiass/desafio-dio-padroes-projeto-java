<p align="center">
 <img src="https://octodex.github.com/images/megacat-2.png" width="300" height="300">
</p>




# desafio-dio-padroes-projeto-java



### _Padrões de Projetos_	
São soluções consolidadas para problemas recorrentes no desenvolvimento e manutenção de software orientado a objetos.

São classificados nas seguintes categorias:
 
* Padrões Criacionais: Abstracty Factory, Builder, Factory Method,Prototype, Singleton. 
* Padrões Comportamentais: Chain of Responsibility, Iterator, Observer, Strategy, Template Method.
* Padrões Estruturais: Adapter, Bridge, Composite, Decorator, Facade, Flyweight, Proxy .

No projeto desse curso foi utilizado os seguintes padrões:

* Um padrão Criacional Singleton: que provê uma instancia única de uma determinada classe ou abstração e fornecer um modo para recupera-la.
* Um padrão comportamental Strategy : é uma interface que define um contrato que vai ser seguido por múltiplas implementações determinado algoritmo ou problema que será resolvido. Simplifica a variação de algoritmos para a resolução de um mesmo problema.
* E um padrão estrutural Facade: é uma interface que abstrai a complexidade de integrações com múltiplos subsistemas, ou, sistema interno que requerem um integração mais complexa, sejam interno ou externo.

Onde cada uma delas engloba uma séries de implementações e referencias que são importantes e resolve diferentes problemas.
	
### _Praticando com Java puro: Singleton,Strategy,Facade_

Nesse projeto com o uso da IDE Eclipse, foi criado um projeto java limpo somente com a JRE e foi criado um pacote para organização dos arquivos. Logo em seguida foi criada três classes Singleton para mostrar como é sua implementação em um projeto.

* Na classe SingletonLazy:  não disponibiliza uma estancia para o usuário Singleton ele tem uma instancia dele mesmo. O construtor do Singleton tem que ser privado, para que não seja instanciado externamente. Ela controla sua própria instancia e tem um método que expõe de maneira pública.
* Na classe SingletonLazyHolder: ela vai encapsular essa instancia em uma classe estática interna que ele vai chamar de holder. 
* Na classe SingletonEager:  assim que a variável estática é definida ele já atribui a estancia, quando for chamada vai estar pronta para ser retornar.
* Na classe Test com o método main para validar se o Singleton está funcionando

Nesse projeto foi mostrado as principais variações de projeto Singleton que é o dos mais utilizados.

Foram criados dois pacotes:

* Subsistema.crm , para buscar as informações dos clientes.
* Subsistema.cep, será uma API de cep.
* A facade abstraiu a complexidade de integração com esse subsistemas e proveu uma interface mais simples para uso e execução da funcionalidade que se propôs a fazer.

Foram criadas classes com interfaces diferentes. 

Foram criadas implementações diferentes, uma com o uso do singleton e a outra não, para mostrar que são sistemas com implementações distintas de integração.


### _Meu projeto_

Por está iniciando no mundo da programação, optei em entregar o meu projeto usando apenas o java na IDE Eclipse. 

Para o projeto usei o assunto abordado acima, referente aos Padrões de Projetos :

* Padrões Criacionais: Singleton retorna uma única instancia de uma determinada classe todas as vezes que forem requisitadas. 
Pega o objeto que foi criado e sempre vai ficar retornando aquele objeto criado

* Padrões Comportamentais: Strategy, uma interface que define um contrato que vai ser seguido por múltiplas implementações determinado algoritmo ou problema que será resolvido.
Simplifica a variação de algoritmos para a resolução de um mesmo problema.

Como exemplo tentei reproduzir um jogo de contra-ataque, a tropa de Elite tentará defender e impedir que os bandidos assaltem um banco.
Os bandidos sempre tentarão atacar, para conseguir levar o dinheiro, a tropa de Elite tentará atacar e desarmar os bandidos, onde os bandidos optaram por uma estratégia diferente sem sucesso levando a se entregarem

Segue abaixo o vídeo onde tirei a base dos estudos

https://www.youtube.com/watch?v=11yEH9RAI28&list=PLd0lZIptCEwOplc9fZ8rv5yj-Vo7C6q7k&index=20

* Padrão estrutural Facade: mascarar, ou, ocultar a implementação complexa de qualquer objeto da classe cliente. 

Um exemplo que será utilizado é de  um restaurante onde um cliente quer comer pizza e o outro massa, o cliente não deve se preocupar se há os ingredientes que o chef vai utilizar, ele simplesmente solicita ao garçom é de responsabilidade do chef preparar.
Podemos considerar como facade o garçom, o chef e os ingredientes.

Segue abaixo o vídeo onde tirei a base dos estudos

https://www.youtube.com/watch?v=I0xWD1hQlW8

### Curso feito na Dio.me com o professor Venilton Falvo Jr- Tech Lead na Dio 

## links úteis

[sintaxe basica markdown](https://www.dio.me/)


