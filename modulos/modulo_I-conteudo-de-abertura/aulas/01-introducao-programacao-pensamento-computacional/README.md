# Pensamento Computacional

O pensamento computacional é um modo de pensar, com o objetivo de resolver problemas que não possuem uma solução imediata, fazendo necessário dividi-lo em problemas menores para identificar possíveis soluções . 

#### Os 4 pilares do Pensamento Computacional:

- **Decomposição:** processo que irá dividir o problema em partes menores e gerenciáveis. É necessário analisar o problema para identificar as partes que podem ser separadas, além de pensar na melhor forma de retornar para o problema principal.
- **Reconhecimento de padrões:** os padrões são características que alguns problemas compartilham. Quanto mais padrões reconhecidos em um determinado problema, mais fácil e rápido será a resolução desse problema. 

- **Abstração:** esse é o pilar de maior importância para o pensamento computacional, ele faz a filtragem e classificação dos dados, separando apenas os elementos essenciais em um determinado problema, ignorando detalhes irrelevantes.  

- **Algoritmos:** é uma sequência finita de passos para solucionar um determinado problema ou executar uma tarefa. Pode ser executável por um agente computacional natural (humano) ou sintético (computador). 

  Algoritmos podem ser escritos em forma de diagrama, pseudocódigo (linguagem humana) ou em uma linguagem de programação (códigos).

  Sua formulação passa pelo processo de decomposição, reconhecimento de padrões e abstração.

#### Habilidades Complementares:

- **Raciocínio Lógico:** é a forma de pensamento estruturado, ou raciocínio, que permite encontrar a conclusão ou determinar a resolução de um problema.
- **Aperfeiçoamento:** a partir de uma solução, determinar pontos de melhora e refinamento, sejam eles pontuais ou gerais. 

<br>

# Introdução à Logica de Programação

Lógica de Programação é o modo como se escrevem programas de computador através de uma sequência de passos para executar uma ou várias funções, esta sequência é o algoritmo.

#### O que é lógica?

Parte da filosofia que trata das formas do pensamento em geral (dedução, indução, hipótese, inferência) e das operações intelectuais que visam à determinação do que é verdadeiro ou não. 

Organização e planejamento das instruções, assertivas em um algoritmo, a fim de viabilizar a implantação de um programa.

#### Técnicas de lógica de programação

- **Técnica Linear:** é a execução sequenciada de uma série de operações, onde tem recursos limitados.
- **Técnica Estruturada:** é uma forma de programação de computadores que preconiza que todos os programas possíveis podem ser reduzidos a apenas três estruturas: sequência, decisão e iteração.
- **Técnica Modular:** é um paradigma de programação no qual o desenvolvimento das rotinas de programação é feito através de módulos, que são interligados entre si através de uma interface comum

<br>

# Fundamentos de Algoritmos

### Tipos de dados

Todos os algoritmos, depois de transcritos para linguagens de programação, ou já criados nelas, têm a função de manipular informações retornadas das bases de dados.

Os dados, geralmente, são armazenados em variáveis auxiliares que são utilizadas para manipular as informações. O tipo de dado é utilizado para mostrar ao compilador do programa quais conversões serão necessárias para carregar em memória os valores utilizados na execução dos programas.

Os tipos de dados podem ser compreendidos e classificados em três grupos distintos, que veremos na sequência.

##### 1 - Tipo de dado estático e dinâmico

A verificação do tipo de dado de uma informação é feita de forma estática, quando o código está sendo compilado. Em C, C++ e Java, por exemplo, os tipos de dados são estáticos. A verificação na forma dinâmica ocorre em tempo de execução. Em Lisp, PHP e Python os dados são dinâmicos.

##### 2 - Tipo de dado forte e fraco

Nas linguagens de programação categorizadas como fortes (Java, Pascal, SQL), o tipo de dado de um valor deve, obrigatoriamente, ter o mesmo tipo de dado da variável. Do contrário, será gerado erro na hora da compilação.

##### 3 - Tipo de dado primitivo e composto

Os tipos primitivos (nativos ou básicos) são fornecidos pelas linguagens de programação. Por este motivo, dependendo da linguagem de implementação utilizada na codificação, os tipos primitivos podem ou não possuírem os mesmos tipos de dados das informações guardadas na memória.

Em computação existem apenas quatro tipos de dados primitivos, que são:

- **INTEIRO**: Representa valores numéricos negativo ou positivo sem casa decimal, ou seja, valores inteiros.
- **REAL**: Representa valores numéricos negativo ou positivo com casa decimal, ou seja, valores reais. Também são chamados de ponto flutuante.
- **LÓGICO**: Representa valores booleanos, assumindo apenas dois estados, VERDADEIRO ou FALSO. Pode ser representado apenas um bit (que aceita apenas 1 ou 0).

- **TEXTO**: Representa uma sequência de um ou mais caracteres. Colocamos os valores do tipo TEXTO entre “ ” (aspas duplas) ou ‘’ (aspas simples), dependendo da linguagem.

Algumas linguagens de programação dividem esses tipos primitivos de acordo com o espaço necessário para os valores daquela variável. Na linguagem Java, por exemplo, o tipo de dados inteiro é dividido em quatro tipos primitivos: **byte, short, int e long**. A capacidade de armazenamento de cada um deles é diferente.

- **byte**: é capaz de armazenar valores entre -128 até 127. 

- **short**: é capaz de armazenar valores entre – 32768 até 32767. 
- **int**: é capaz de armazenar valores entre –2147483648 até 2147483647. 
- **long**: é capaz de armazenar valores entre –9223372036854775808 até 9223372036854775807.

Os tipos de dados compostos podem ser construídos tendo como base os dados primitivos ou também outros tipos de dados compostos. Esse processo é conhecido como COMPOSIÇÃO. São usados para descrever a estrutura das linhas de registro. No caso da linguagem C, as cadeias de caracteres são tipos de dados compostos. No caso do JavaScript esta característica é nativa da própria linguagem.

### Variáveis

Por regra, cada variável armazena apenas um tipo de dado. Variáveis de texto armazena caracteres, por exemplo, o nome da pessoa. Variáveis numéricas armazenam valores: idade, salário. Já na informação do sexo, armazena-se apenas um caractere. A informação de sexo, poderia ser numérica desde que se criasse um domínio na base de dados, indicando, por exemplo, que o número 1 indica feminino e 2, masculino. Para entender, compare o armazenamento em variáveis com objetos guardados em gavetas. Cada gaveta poderá guardar apenas um tipo de objeto: ou calças, ou camisas, ou jaquetas. O mesmo acontece com as variáveis, cada variável poderá armazenar apenas um tipo de dado: numérico, texto ou data, por exemplo.

Também podemos compreender a variável como algo incerto ou inconstante. Sua utilidade se baseia no fato de que o volume de informações a armazenar é muito grande e diversificado, justificando, dessa forma, a diversidade dos dados processados.

As variáveis, geralmente, são compostas por dois atributos distintos:

* nome
* o tipo de dados que armazenará

Dentro de um mesmo programa não poderão ser criadas duas ou mais variáveis com o mesmo nome.

Dicas importantes para a criação de variáveis:

- Usar nomes simples, que especificam sua funcionalidade, e ainda compostos e antecedidos por um prefixo. Ex.: AUX_SALARIO ou WW_SALARIO. Prefixos são importantes para identificar o termo como representativo de uma variável.
- Não usar palavras reservadas em linguagens de programação para criar variáveis. O mesmo se aplica para nomes de tabelas e colunas na base de dados.

- Não iniciar o nome das variáveis com símbolos ou caracteres especiais.
- O nome da variável deve indicar a função que a mesma irá exercer. Deve lembrar ou indicar a informação que será armazenada em sua estrutura.

---





---

> **PRÓXIMA AULA:** [Introdução ao Git e ao GitHub](../02-introducao-git-github)

---

> **LINKS DE APOIO**
>
> - [MAKERZINE - Pensamento computacional e seus 4 pilares](https://www.makerzine.com.br/educacao/pensamento-computacional-e-seus-4-pilares/)

