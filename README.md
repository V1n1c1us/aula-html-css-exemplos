# aula-html-css-exemplos

### **`display: inline;`**
> Path: display/inline.html

Como funciona:  

1. O valor **inline** permite que os elementos fiquem um ao lado do outro.
2. Ao declarar um elemento **inline**, você não conseguirá mais utilizar as proprieradades _**width**_ e _**height**_, pois elas não funcionaram.
3. Os elementos _**inline**_ não aceitam largura e nem altura pois, o tamanho do elemento é definido pelo conteúdo que ele contém.
4. O elemento com **display: inline**, ganha o **comportamento de uma palavra**.

### **`display: block;`**
> Path: display/block.html

Como funciona:  

1. Já que o display **inline** não aceita as proprieradades _**width**_ e _**height**_, para que o elemento HTML aceite uma  _**width**_ e _**height**_, precisamos defninir o valor do _**display**_ como _**block**_.
2. Todos elementos definidos com _**display: block**_, aceitam as propriedades  _**width**_ e _**height**_.
3. Todo elemento definido como block ocupa a linha inteira, ou seja, não deixa outro elemento ocupar a mesma linha que ele.

### **`display: inline-block;`**
> Path: display/inline-block.html

Como funciona:  

1. A melhor definição para o nome _**inline-block**_ é basicamente a junção dos comportamnetos dos valores _**inline + block**_. 
3. Com _**display: inline-block**_ nós conseguimos definir uma largura (width) e altura (height) da mesma forma que conseguimos com o _**display: block**_, esse é o único comportamento que o _**inline-block**_ herda do _**block**_.
2. Para conseguirmos definir uma _**width**_ e _**height**_ para cada um dos nossos elementos, é necessário que todas eles tenham o valor block na propriedade display, ou seja, acabamos de cair em um impasse. É desse impasse que nasceu o _**display: inline-block**_.
3. Quando um elemento _HTML_ é definido como _**display: inline-block**_ ele também ganha o comportamento de uma palavra, esse é o segundo comportamento que herdamos do _**display: inline**_.
