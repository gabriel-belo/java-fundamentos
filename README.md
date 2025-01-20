# java-fundamentos
Aprendendo fundamentos de Java com curso da FIAP "Java fundamentos"

<h1>Capítulo 1 - Orientação a objeto</h1>
A escolha de uma linguagem para o desenvolvimento de sistemas leva em consideração diversas variaveis estratégicas, como: maturidade da plataforma, custo, velocidade de desenvolvimento e curva de aprendizagem.

A características que fazem com que Java seja uma linguagem autamente utilizada: portabilidade, simplicidade entre outros

Uma definição para linguagens de pragramação: Um conjunto limitado de instruções (vocabulário), associado a um conjunto de regras (sintaxe) que define como as instruções podem ser associadas.

<h3>Portabilidade</h3>
Um código Java pode ser aplicado em qualquer sistema operacional sem a necessidade de adaptações, isso se da por causa da existencia de uma máquina virtual, conhecida como JVM (Java Virtual Machine), que é capaz de interpretar (executar) os arquivos Java compilados. 

A linguagem Java é compilada e interpretada. Primeiramente, os arquivos de código fonte Java com extensão ".java" são compilados para bytecodes, também como arquivos de extensão ".class"

Após esse processo, os bytecodes são interpretados pela JVM, iniciando a execução do software

<h3>Orientação a Objeto</h3>
A programação orientada a objeto é uma técnica de programação que focaliza os dados e interfaces com esses objetos. 

Exemplo
Foco nos Dados: A classe Carro tem atributos que armazenam informações sobre o carro, como modelo, cor e ano. Esses atributos representam os dados do objeto Carro.
Interface com Objetos: Os métodos mostrarInformacoes() e pintar(String novaCor) definem como interagir com o objeto Carro.
O método mostrarInformacoes() exibe os dados do carro.
O método pintar() permite mudar a cor do carro.
Conclusão

Os objetos são gerados cada qual com suas informações. Caso uma atualização seja necessária, a Classe é alterada e a mudança é refletida para todos os sistemas que utilizam este molde e, consequentemente, a todos os objetos gerados também.

Um objeto pode representar uma entidade física, conceitual ou de software
<ul>
  <li>Física: caminhão, óculos, prédio ...</li>
  <li>Conceitual: Formas abstratas, não palpáveis ( como matemática, sentimentos, pensamentos...)</li>
  <li>De software: Quando representa sistemas( como usuários, e-mais, acesso ...)</li>
</ul>

Um objeto é uma entidade com fronteiras e identidade bem definidas que encapsulam o estado e comportamento

è representado pelas operações e métodos e máquinas de estado. Ele determina como o objeto age ou reage auma requisição de outro objeto. É representado pelas operações que ele pode realizar

<h3>Princípios de orientação a objetos</h3>
<ul>
  <li>Abstração: Entendimento e análise das necessidades do sistema, abstraindo o do mundo real. Exemplo: Os moldes (classes) devem ser pensados com base nas características reais de um aluno (registro, nome, endereço, curso, data de nascimento etc) e que sejam relevantes para o sistema.</li>
  <li>Encapsulamento: Programar em partes, o mais isolado possível, encapsulando-as. O objetivo é tornar o software mais flexível, fácil de modificar e evoluir. As classes devem proteger as suas informações e comportamentos, ou seja, devem possuir proteção no acesso a seus atributos e métodos.
  As classes devem permitir que outras classes somente acessem as suas funcionalidades, sem a necessidade de conhecer a sua lógica interna</li>
  <li>Hierarquia: Na programação orientada a objetos existe herança, assim como no mundo real.Na programação é o mecanismo pelo qual uma classe pode estender (herdar) de outra classe para receber seus comportamentos (métodos) e variáveis (atributos)</li>
  <li>Modularização: É o processo de dividir um todo em partes bem definidas, que podem ser construídas e examinadas separadamente e que consigam interagir entre si. A programação orientada a objetos permite a criação de componentes modulares, que podem ser reutilizados para diversos sistemas distintos. Por exemplo: A classe Aluno, se for criada seguindo princípios citados de alunos, para o sistema financeiro da faculdade, lançamento de notas, consulta ao boletim, entre outros.</li>
</ul>
