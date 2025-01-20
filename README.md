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
-Física: caminhão, óculos, prédio ...
-Conceitual: Formas abstratas, não palpáveis ( como matemática, sentimentos, pensamentos...)
-De software: Quando representa sistemas( como usuários, e-mais, acesso ...)

Um objeto é uma entidade com fronteiras e identidade bem definidas que encapsulam o estado e comportamento

è representado pelas operações e métodos e máquinas de estado. Ele determina como o objeto age ou reage auma requisição de outro objeto. É representado pelas operações que ele pode realizar

<h3>Princípios de orientação a objetos</h3>
