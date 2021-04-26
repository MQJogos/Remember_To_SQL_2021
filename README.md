# Remember_To_SQL_2021
Apenas estude

Questão 1
O comando sql ALTER pode ser usado para


Alterar a estrutura da tabela


Alterar os dados da tabela


Adicionar colunas a tabela


Deletar colunas da tabela


Deletar linhas da tabela

Questão 2
O banco de dados da sua empresa contém uma tabela denominada OrderShip que é definida da seguinte maneira:



- Um valor NULL representa uma ordem interna.

- Noventa por cento dos valores no CountryCode são NULL.

 

Os clientes exigem um procedimento que retornará pedidos para todos os clientes de um país especificado.

Foi criado um novo procedimento para atender esta demanda:

 



 

 O desempenho neste procedimento é lento e você precisa otimizar essa consulta. Qual instrução Transact-SQL você deve usar?


CREATE NONCLUSTERED INDEX IX_CountryCode ON Ordership (CountryCode) WHERE CountryCode IS NOT NULL


CREATE STATISTICS ST_CountryCode ON OrderShip (CountryCode) WHERE CountryCodeIS NOT NULL


CREATE CLUSTERED INDEX IX_CountryCode ON OrderShip (CountryCode)


CREATE INDEX IX_CountryCode ON OrderShip (CustomerID) WHERE CountryCode IS NOT NULL

Questão 3
Quais dos metódos abaixo é o mais indicado para reforçar a integridade das informações em um banco de dados?


Constraints.



Stored Procedure.



Triggers.



Cursors.



Functions.

Questão 4
Qual o tipo de JOIN deve ser utilizado quando você deseja retornar as linhas que não possuem os valores correspondentes ao predicado?

 


Equi-join.



Natural-join.



Outer-join.



Todos os mencionados.

Questão 5
Identifique entre os fatores de qualidade abaixo o que está com a definição INCORRETA:


Testabilidade - É o processo de documentação dos cenários de testes durante o levantamento de requisitos


Manutenibilidade - É uma característica inerente a um projeto de sistema ou produto, e se refere à facilidade, precisão, segurança e economia na execução de ações de manutenção no sistema


Interoperabilidade - Capacidade de um sistema (informatizado ou não) de se comunicar de forma transparente (ou o mais próximo disso) com outro sistema (semelhante ou não)


Reusabilidade - Quando um programa (ou partes de um programa) pode ser reutilizado em outras aplicações


Confiabilidade - Quanto que se pode esperar que um programa execute a função pretendida com a precisão exigida

Questão 6
Das opções seguintes, assinale aquela que NÃO é uma característica referente aos bancos de dados SQL Server até a versão 2014.


ser um banco de dados relacional.


possuir integração com ferramentas e linguagens como o framework.NET.


ser multiplataforma


rodar em plataforma Microsoft.


possuir entre suas ferramentas o Query Analyser e o Profile.

Questão 7
Algoritmo:

var RESPOSTA, CONTADOR, X, N:INTEIRO

INICIO

CONTADOR ? 0

RESPOSTA ? 0

X ? 4

N ? 8

ENQUANTO(CONTADOR >= N) FAÇA

RESPOSTA ?  RESPOSTA * X

CONTADOR ? CONTADOR + 1

ESCREVA(RESPOSTA)

FIM_ENQUANTO

ESCREVA(RESPOSTA)

FIM

A saída na tela será:


0,0,0,0 e 0


4,8,16,32 e 64


1


2,4,8 e 8


0

Questão 8
Você administra uma instância do Microsoft SQL Server 2017 que contém um banco de dados financeiro hospedado em uma rede de área de armazenamento (SAN).

O banco de dados financeiro tem as seguintes características:

- O banco de dados é modificado continuamente pelos usuários durante o horário comercial de segunda a sexta - feira, entre as 9:00 e as 17:00 horas;

- Cinco por cento dos dados existentes são modificados a cada dia.;

- O departamento financeiro carrega arquivos CSV grandes em várias tabelas a cada dia útil às 11:15 horas e às 15:15 horas usando os comandos BCP ou BULK INSERT. Cada carga de dados adiciona 3 GB de dados ao banco de dados.

- Um backup completo do banco de dados é realizado todos os domingos às 10:00 horas.

- As operações de backup serão realizadas a cada duas horas (11:00, 13:00, 15:00 e 17:00) durante o horário comercial.

Você precisa garantir que o tamanho do backup seja o menor possível. Qual backup você deve executar a cada duas horas?


FULL;


CHECKSUM;


Diferencial;


Transaction Log

Questão 9
Qual o resultado obtido ao compilar e executar a classe abaixo?

------------------------------------------------------------------------------------

public class CarNamePrinter {

          public static void main(String[] args) {

            int index = 0;

            final String[] cars = {"Sandero", "Gol", "Onix"};

            for (;;) {

                System.out.print(cars[++index]);

                if (index == 2) {

                    return;

                }

                System.out.print(", ");

            }

        }

    }

Sandero, Gol, Onix


Gol, Onix


Sandero, Gol


Não compila


Ocorre um erro de execução

Questão 10
Para acessar os elementos de um vetor ou matriz usa-se índices. O índice define a posição da variável dentro do vetor ou da matriz.

Observe as afirmativas abaixo acerca deste assunto:

I. int Vetor[5]; // declara um vetor de 5 posições;

II. int Matriz[6][5]; // declara uma matriz de 6 linhas e 5 colunas;

III. Vetor[0] = 9; // coloca 9 na primeira posição do vetor;

IV. Matriz[0][1] = 15; // coloca 15 na primeira linha e na segunda coluna da matriz;

V. Vetor[4] = 8; // Coloca 8 na quarta posição do Vetor;

É correto apenas:


I, II e III


I e III


I, II, III e IV


I, II e IV


Todas

Questão 11
Retorne o nome das cidades junto a temperatura e condição, onde condição é ensolarada ou nublada, mas a temperatura deve ser superior a 70.


SELECT cidade, temperatura, condicao FROM tempo WHERE condicao = 'ensolarada' AND condicao = nublada OR temperatura > 70;



SELECT cidade, temperatura, condicao FROM tempo WHERE condicao = 'ensolarada' OR condicao = nublada OR temperatura > 70;



SELECT cidade, temperatura, condicao FROM tempo WHERE condicao = 'ensolarada' OR condicao = nublada AND temperatura > 70;



SELECT cidade, temperatura, condicao FROM tempo WHERE condicao = 'ensolarada' AND condicao = nublada AND temperatura > 70;

Questão 12
Qual é a menor estrutura de dados em um banco de dados Oracle?

 


Data Block.



Segment.



Extent.



Data File.



Tablespace.

Questão 13
Qual a maneira correta de guardar dados no localStorage do browser?


document.localStorage = { token: "tokenSecreto" };


window.localStorage = JSON.stringify({ token: "tokenSecreto" });


browser.localStorage.set({ token: "tokenSecreto" });


window.localStorage.setItem("token", "tokenSecreto");


browser.localStorage.setItem({ token: "tokenSecreto" });

Questão 14
Qual o resultado ao executar a classe abaixo? public class A { private void sum(int value1, long value2) { System.out.println(value1 + value2); } private void sum(long value1, int value2) { System.out.println(value1 + value2 + 5); } public static void main(String[] args) { A a = new A(); a.sum(5, 5); } }


Não compila pois o compilador não consegue identificar qual método utilizar na chamada implementada no main: a.sum(5,5)


É exibido o número 10.


Ocorre um erro de execução.


É exibido o número 15.


Não compila porque não é possível existir dois métodos sum, na mesma classe, com essas assinaturas.

Questão 15
Sobre FULL JOIN:


Retorna todos os registros mesmo quando não há um resultado em uma das tabelas


Retorna todas os registros quando há um resultado em uma das tabelas


Retorna todas os registros quando há pelo menos um resultado em ambas das tabelas


Retorna apenas os registros presentes na tabela à esquerda


Nenhuma das alternativas acima

Questão 16
Analise o comando SQL abaixo:

UPDATE usuarios SET status = 'ativo';

Com base no comando descrito acima, assinale qual é a alternativa correta


O comando irá alterar o campo usuarios para 'ativo' na tabela status


O comando irá inserir o campo status na tabela usuarios


O comando irá alterar o campo status para 'ativo' de todas as linhas da tabela usuarios


O comando não irá ser executado porque está faltando o comando 'WHERE'


O comando irá inserir um novo registro com status 'ativo' na tabela usuários

Questão 17
Sabendo que a tabela INCUBADOS possui apenas 2 campos (ID e INCUBADINHO), qual delas irá apresentar pior performance no banco de dados?


SELECT * FROM [itbox.dba].[dbo].[INCUBADOS] WHERE INCUBADINHO='FELICIO';


SELECT INCUBADINHO FROM [itbox.dba].[dbo].[INCUBADOS] WHERE INCUBADINHO='FELICIO';


SELECT INCUBADINHO FROM [itbox.dba].[dbo].[INCUBADOS] WHERE INCUBADINHO LIKE 'FELICIO%';


SELECT * FROM [itbox.dba].[dbo].[INCUBADOS] WHERE INCUBADINHO LIKE '%FELICIO%';

Questão 18
Sobre Orientação a objetos, analise:

I - O encapsulamento garante que apenas as interfaces necessárias para interação com o objeto estejam visíveis, e atributos internos não sejam acessíveis.

II - O polimorfismo garante que objetos possam herdar métodos e atributos de uma superclasse para a geração de uma nova classe.

III - A herança possibilita que distintas operações na mesma classe tenham o mesmo nome, desde que alterada a assinatura.


III, apenas


II, apenas


I, apenas


II e III, apenas


I, II e III

Questão 19
Suponha que solicitaram a você ordenar 6 objetos em ordens diferentes por dia.
E assim por diante, de modo que nunca será repetido as ordens anteriores. Durante quanto tempo será possível fazer isso?

Por exemplo:
Dia 1: A B C D E F
Dia 2: A B C D F E
Dia 3: A B C F D E


6 meses


36 dias


Entre 1 ano e meio e 2 anos


Entre 2 anos e 2 anos e 6 meses


Mais de 2 anos

Questão 20
Qual a saída correta para o algoritmo abaixo

algoritmo

   var

      posicao: inteiro

      valor: inteiro

      total: inteiro

   inicio

      valor <- 1

      total <- 0

      para posicao de 1 ate 5 faca

         valor <- valor + valor

         total <- valor

      fim-para

      escreva(total)

fim


30


16


12


32


26

Questão 21
O departamento vendas da empresa que você trabalha solicitou que fosse desenvolvido um relatório que apresentasse a rentabilidade das vendas por cliente, baseado no salário de cada vendedor e na margem de lucro de cada produto. O sistema foi desenvolvido levando em consideração critérios rigorosos de segurança, ou seja, cada departamento tem acesso apenas os procedimentos relacionadas ao departamento. Desta forma, a arquitetura do banco de dados recebeu as mesmas tratativas, principalmente no controle de usuários.

Considerando o cenário descrito e as boas práticas de administração de banco de dados, qual das opções abaixo seria o método mais prático para desenvolver o relatório solicitado?


Desenvolver a instrução SQL e destinar-a para a equipe de desenvolvimento para que vinculem com a regra de negócio da aplicação.

 


Criar de uma PROCEDURE que colete as informaçõesdas tabelas dos demais departamentos envolvidos e consolide em uma tabela criada para o departamento de vendas, assim realizando a consulta a partir dessa tabela.


Criar uma VIEW com a instrução SQL necessária e posteriormente conceder permissão de leitura na VIEW para os colaboradores do departamento de vendas.


Considerando a segurança necessária, desenvolver um script externo, por exemplo shell ou bat, que coletaria essas informações do banco de dados e gravaria em um arquivo .txt que seria disponibilizado posteriormente para o departamento de vendas.

Questão 22
Ao executar o código abaixo, quando chegar na linha 7 (comentada no código), quantos objetos do tipo Customer estarão elegíveis para o Garbage Collector?

public class Foo {
    public static void main(String[] args) {
        Customer c1 = new Customer();
        c1 = null;
        for (int x = 0; x < 8; x++) {
            Customer c2 = new Customer();
        } //linha 7
    }
}

Nenhum


9


7


8


1

Questão 23
As Collections são um conjunto de classes e interfaces em JAVA que representam estruturas de dados avançadas. Sobre elas, é correto o que se afirma em:


A interface LIST é uma coleção que não permite a adição de valores duplicados e mantém uma ordenação específica entre os elementos


A interface MAP é uma das interfaces que estende de Collections


A interface SET é uma coleção que não permite elementos duplicados e a ordem em que os elementos são armazenados pode não ser a ordem na qual eles foram inseridos.


Algumas das implementações possíveis da interface SET são ArrayList e LinkedList


Algumas das implementações possíveis da interface LIST são HashSet, TreeSet e LinkedHashSet

Questão 24
Dado o código abaixo, qual os textos exibidos no console? (considere que todas as classes estão no mesmo pacote) public class A { public void print() { System.out.println("Print A"); } } public class B extends A { public void print() { System.out.println("Print B"); } } public class C extends B { public void print() { System.out.println("Print C"); } } public class MainClass { public static void main(String[] args) { A a1 = new B(); a1.print(); A a2 = new C(); a2.print(); B b = new C(); b.print(); } }


Print A; Print A; Print B.

Print B; Print C; Print C.


Print A; Print A; Print A.


Ocorre erro de compilação


Ocorre erro de execução

Questão 25
Referente a estruturas de dados, é INCORRETO afirmar:


Uma lista encadeada é uma coleção linear de objetos de uma classe autoreferenciada, chamados de nós.


Uma String forma uma estrutura de dados que corresponde a um array de caracteres.


O tamanho (quantidade de elementos) de uma lista encadeada deve ser definido na hora da criação.


De acordo com a teoria dos grafos, quando dois nós estão ligados por um arco, eles podem ser chamados de adjacentes.


A estrutura de dados Pilha apresenta uma estrutura no qual o primeiro elemento a ser inserido será o último a ser removido.

Questão 26
Em banco de dados, como pode ser descrito o objeto do tipo VIEW?

 


Uma view é uma stored procedure especial que é executa assim que determinado evento ocorre.



Uma view é uma tabela virtual a qual retorna os resultados de um SQL pré-compilado.



Uma view é um diagrama de banco de dados.



Uma view é uma tabela sem constrainsts.



Nenhuma das anteriores.

Questão 27
Dada uma matriz A=(ij) 2x2, qual seria a matriz resultante B caso o código a seguir fosse executado?

A = [9  -9]

[-4  3]

PARA I <- 1 ATÉ 2

PARA J <- 1 ATÉ 2

B(j, i) = A(i, j)

FIM_PARA

FIM_PARA


B = [3  -4]

[-9  9]


B = [3  -9]

[-4  9]


B = [9  -4]

[-9  3]


B = [-4   9]

[-9  3]


B = [9  -4]

[3  -9]

Questão 28
Considerando o pseudocódigo abaixo e, assumindo que IntegerQueue é uma pilha de inteiros, o que faz a função function?


void function(int n)
{
   IntegerQueue queue = new IntegerQueue();
   queue.enqueue(0);
   queue.enqueue(1);
   for (int j = 0; j < n; j++)
   {
       int x = queue.dequeue();
       int y = queue.dequeue();
       queue.enqueue(y);
       queue.enqueue(x + y);
       print(x);
   }
}


Imprimir números de 0 até n-1


Imprimir números de n-1 até 0


Imprimir os primeiros n números da sequência de Fibonacci


Imprimir os primeiros n números da sequência de Fibonacci em ordem contrária


Nenhuma das alternativas acima.

Questão 29
Um banco de dados relacional é um banco de dados que modela os dados de uma forma que eles sejam percebidos pelo usuário como tabelas, ou mais formalmente relações.
Sobre o modelo relacional, é INCORRETO afirmar que:


Um banco de dados relacional consiste em uma coleção de tabelas, cada uma com um nome único atribuído.


Na álgebra relacional, as operações de seleção, localização e união são chamadas de operações unárias por operarem em uma relação.


A linguagem SQL é uma linguagem de consulta amigável que possui como base formal a álgebra relacional.


A instância de um banco de dados corresponde ao instantâneo dos dados no banco de dados em um determinado instante de tempo.


Nenhuma das afirmações acima.

Questão 30
Quais dos componentes a seguir fazem parte da arquitetura de um banco de dados ORACLE?

 


Processos de background.



Tablespaces.



Datafiles.



Tempfiles.



Todos os mencionados.

QUESTÃO BÔNUS
Uma equipe da Fórmula 1 deseja calcular o número mínimo de litros que deverá colocar no tanque de um de seus carros para que ele possa percorrer um determinado número de voltas até o primeiro reabastecimento. Escreva um programa (EM QUALQUER LINGUAGEM) que leia o comprimento da pista (em metros), o número total de voltas a serem percorridas no grande prêmio, o número de reabastecimentos desejados e o consumo de combustível do carro (em Km/L). Calcular e escrever o número mínimo de litros necessários para percorrer até o primeiro reabastecimento. Considere que o número de voltas entre os reabastecimentos é o mesmo.
