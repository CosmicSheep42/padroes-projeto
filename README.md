<h1 align="left">Trabalho Padrões de Projeto - BCC304</h1>

###

<p align="left">O seguinte repositório é destinado a realização da atividade de Padrões de Projeto da disciplina Engenharia de Software (BCC304)</p>

###

<h2 align="left">I Princípios selecionados</h2>

###

<p align="left">1 - Princípio da Responsabilidade Única (Single Responsibility Principle)<br>2 - Princípio da substituição de Liskov (Liskov Substitution Principle)<br>3 -  Princípio da Segregação da Interface (Interface Segregation Principle)<br>4 - Princípio de Demeter (Principle of Least Knowledge)<br><br>Cada princípio possui dois exemplos de sua aplicação, sendo um correto e um inadequado.</p>

###

<h2 align="left">I Responsabilidade Única</h2>

###

<p align="left"> Esse princípio pode ser compreendido como o ditado popular "Quem faz tudo ao mesmo tempo não faz nada direito", de acordo com ele, toda classe dentro do código deve possuir uma única responsabilidade. Essa abordagem ajuda a manter o código coeso, modular e de fácil compreensão. 
  
Quando uma classe tem múltiplas responsabilidades, ela se torna mais difícil de manter e evoluir ao longo do tempo, pois, qualquer mínimo erro pode resultar em múltiplos problemas em diversas funções dentro do código. Dividir funcionalidades em classes separadas com responsabilidades únicas aumenta a flexibilidade do código e facilita a reutilização em diferentes contextos.
</p>

###

<h2 align="left">I Substituição de Liskov</h2>

###

<p align="left">Pela definição desse princípio, uma classe não pode conter métodos que não englobem a totalidade de suas subclasses. Uma classe "ave" não pode conter o atributo "voar", pois anularia as subclasses "pinguim", "avestruz", "galinha", pois não compartilham deste método. </p>

###

<h2 align="left">I Segregação da Interface</h2>

###

<p align="left">De acordo com esse princípio, nenhuma classe deve depender de métodos que não utilize. Usando por exemplo um software de edição de imagens, como o photoshop, diferentes usuários, reprensentando nossas classes, tem necessidades de interfaces diferentes, um fotógrafo profissional não utiliza as mesmas ferramentas, representando os métodos, que um desenhista. Dessa forma, criando diferentes interfaces customizadas e adaptadas para cada classe, facilitamos o entendimento e modificação do código para alterações em cada classe.</p>

###

<h2 align="left">I Demeter</h2>

###

<p align="left">Segundo a lei de Demeter deve-se evitar interações excessivas com objetos indiretos, o código deve dialogar sempre diretamente com os objetos que deseja interagir. Essa abordagem ajuda a reduzir a complexidade do código, facilitando a manutenção e promovendo a reutilização de componentes.
Em uma anologia simples, poderiamos considerar o ato de acessar um arquivo dentro de múltiplas pastas aninhadas uma violação, representando um objeto sendo acessado através de outros. Porém, ao criar um atalho para o arquivo na área de trabalho, resolvemos a violação, permitindo um acesso simples e eficiente ao objeto sem depender dos demais.</p>

###
