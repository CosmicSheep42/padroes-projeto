<h1 align="left">Trabalho Padrões de Projeto</h1>

###

<p align="left">O seguinte repositório é destinado a realização da atividade de Padrões de Projeto da disciplina Engenharia de Software (BCC304)</p>

###

<h2 align="left">I Padrões escolhidos</h2>

###

<p align="left">1 - Observer<br>2 - Adapter<br>3 -  Prototype<br><br>Como indicado pelo professor, os padrões foram retirados do site https://refactoring.guru/pt-br<br> Cada padrão apresentara um exemplo e um diagrama UML</p>

###

<h2 align="left">I Observer</h2>

###

<p align="left"> Problema: <br>
Frequentemente um código pode precisar notificar múltiplos objetos sobre alterações de estado de um ou múltiplos objetos. Esse fluxo de notificações pode criar conflitos e tornar o código menos compreensível.<br>
<br>
Solução:<br>
O padrão Observer visa criar uma solução prática e eficiente, atribuindo uma "lista de inscrição" para os objetos observadores, dessa forma, eles serão notificados apenas quando ocorrerem as alterações de estado em que estão inscritos.<br>
<br>
Exemplo:<br>
Em um aplicativo hipotético, criado para notificar seus usuários sobre eventos relacionados à franquia Pokémon um Observer poderia ser implementado para possibilitar o utilizador a se inscrever em tópicos objetivos, como jogos específicos, mídias que se interessa e região onde vive, para ser notificado apenas dos eventos pertinentes.<br>
<br>
No diagrama há uma classe "AppADM" que pode criar objetos "Eventos", em suas atribuições, todo evento possúi uma mídia (Jogos ou TCG), uma organização (Oficial ou Comunidade), uma localização (JP, EU, NA ou Latam). A classe "observer" deve pegar essas atribuições dos objetos Evento e notificar objetos usuários que possuam correspondências com essas atribuições.
<br>
<img src="a.png">
</p>

###

<h2 align="left">I Adapter</h2>

###

<p align="left">Problema:<br>
Na elaboração de códigos ou sistemas mais complexos, por exemplo, um código utilizando uma base de dados de terceiro, podem ocorrer situações onde interfaces não consigam comunicar entre si, criando incompatibilidade entre partes do sistema. <br>
<br>
Solução:<br>
O Adapter visa agir como um "tradutor", um objeto especial no código que recebe informações de uma parte e as adapta para que possam ser processadas pela outra. Sendo um objeto com essa função exclusiva, torna-se mais fácil modificar a "tradução" caso venha a ser necessário.<br>
<br>
Exemplo:<br>
  
</p>

###

<h2 align="left">I Prototype</h2>

###

<p align="left"></p>

###


###
