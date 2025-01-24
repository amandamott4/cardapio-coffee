RESUMO DO CURSO (CSS) - FreeCodeCamp 

---
CSS - Cascading Style Sheets

**Projeto de Menu de Café**

- **Fundamentos do CSS:**
  - Neste projeto, você aprenderá os fundamentos do CSS (Cascading Style Sheets) criando um menu de café.
  - CSS é a linguagem usada para estilizar um documento HTML.
  - Descreve como os elementos HTML devem ser exibidos na tela.

- **Ponto e Vírgula no CSS:**
  - O ponto e vírgula (;) é usado para separar as diferentes declarações dentro de um bloco de regras.
  - Um bloco de regras é iniciado por um seletor seguido por chaves ({}) e contém uma ou mais declarações.
  - Cada declaração define uma propriedade CSS (como `color`, `font-size`, `background-color`, etc.) e seu valor correspondente.

- **Adicionar Estilos:**
  - Até agora, você estava limitado quanto à apresentação e aparência do conteúdo criado.
  -Para começar a ter controle, adicione um elemento de estilo dentro do elemento `head`.
  - Você pode adicionar o mesmo conjunto de estilos a muitos elementos criando uma lista de seletores, separados por vírgulas.
  - Quando há muitos estilos, é melhor colocá-los em um arquivo separado e vinculá-lo.

- **Vincular Arquivo CSS:**
  - É necessário vincular o arquivo `styles.css` para que os estilos sejam aplicados.
  - Dentro do elemento `head`, adicione um elemento `link` com o atributo `rel` com valor "stylesheet" e o atributo `href` com valor "styles.css".
  - O elemento `link` deve ser um elemento nulo, sem uma tag final.

- **Estilização Responsiva:**
  - Para que a estilização da página seja semelhante em dispositivos móveis e desktop, adicione um elemento `meta` com um atributo de conteúdo especial.
  - Exemplo: `<meta name="viewport" content="width=device-width, initial-scale=1.0" />`

- **Mudança de Cor de Fundo:**
  - Adicione uma outra estilização para alterar a propriedade `background-color` do elemento `body` para marrom.
  - Caso a cor marrom dificulte a leitura do texto, altere a cor de fundo do `body` para `burlywood`.

- **Elemento `div`:**
  - O elemento `div` é usado principalmente para fins de layout de design.
  - Adicione um elemento `div` dentro do elemento `body` e mova todos os outros elementos para dentro desse novo `div`.
  - Use a propriedade `width` do CSS para evitar que o `div` ocupe toda a largura da página.

- **Comentários no CSS:**
  - Comentários em CSS se escrevem assim: `/* comment here */`
  - Na folha de estilo, comente a linha que contém a propriedade e valor `background-color` para estilizar apenas o elemento `#menu`, tornando o fundo branco novamente.

- **Centralização e Largura:**
  - O texto está centralizado dentro do elemento `#menu`.
  - Atualmente, a largura (`width`) do `#menu` é especificada em pixels.
  - Altere o valor da propriedade `width` para 80%, tornando-a 80% da largura do elemento pai (`body`).
  - Para centralizar o `#menu` horizontalmente, defina as propriedades `margin-left` e `margin-right` como `auto`.

- **Seletor de Classe no CSS:**
  - Os seletor de classe é definido por um nome com um ponto na frente: `.class-name { }`
  - Aplique a estilização da classe removendo o atributo `id` e adicionando um atributo `class` ao `div`, com o valor `menu`.
  - Adicione a propriedade `background-image` e defina seu valor como `url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg)`.

- **Elementos do Menu e Artigos:**
  - Adicione um elemento `article` vazio sob o título de Café.
  - Os elementos `article` contêm múltiplos elementos com informações relacionadas, como sabor e preço de café.
  - Use suas novas classes para alinhar o texto da esquerda (`.flavor`) e direita (`.price`).

- **Estilização Inline:**
  - Elementos `p` são de nível de bloco, ocupando toda a largura do elemento pai.
  - Adicione o seletor `.item p { }` e defina a propriedade `display` como `inline-block` para que os elementos `p` se comportem como inline.
  - Ajuste a propriedade `width` das classes `flavor` e `price` para 49%.

- **Ajuste Fino de Largura:**
  - Altere a largura (`width`) das classes `flavor` para 75% e `price` para 25%.

### Adicionando Seções e Elementos ao Menu
- Adicionar uma segunda seção para exibir as sobremesas.
- Inserir dois elementos `p` com os textos "Donut" e "1.50" na mesma linha.

### Regras de CSS e Classes
- Adicionar a classe `dessert` à regra com a classe `flavor`.
- Adicionar padding à classe `menu`:
  - `padding-left` e `padding-right` com valor de 20px.
  - `padding-top` e `padding-bottom` com valor de 20px.
  - Substituir as propriedades de padding individuais por uma única propriedade `padding` com valor de 20px.
- Adicionar a propriedade `max-width` com valor de 500px à classe `menu`.

### Alterações na Tipografia
- Adicionar a propriedade `font-family` com valor `sans-serif` ao `body`.
- Tornar o texto "Est. 2020" em itálico, criando uma classe `established` e aplicando a propriedade `font-style: italic`.
- Tipografia dos cabeçalhos:
  - Usar `font-size` de 40px para `h1` e 30px para `h2`.

### Adicionando Elementos e Estruturando o Conteúdo
- Adicionar um elemento `footer` abaixo do elemento `main`.
- Dentro do `footer`, adicionar um elemento `p` com um link (elemento `a`) para `https://www.freecodecamp.org`, que abre em uma nova guia (`target="_blank"`).

### Personalização de Elementos
- Modificar a largura e cor do elemento `hr`.
  - Mudar a altura do `hr` e a cor de fundo para marrom.
  - Ajustar a espessura da borda para 5px.
- Adicionar espaço interno de 20px ao elemento `body` usando a propriedade `padding`.
- Ajustar margens dos itens do menu:
  - Usar `margin-top` e `margin-bottom` com valor de 5px.
  - Adicionar a classe `bottom-line` com `margin-top: 25px` ao segundo elemento `hr`.

### Estilo para o Rodapé
- Adicionar um comentário de estilo (`/*FOOTER*/`) no final do arquivo CSS.
- Definir o tamanho da fonte do `footer` para 14px.
- Tornar os links do `footer` sempre pretos, independentemente de terem sido visitados.

### Manipulação de Estados de Links
- Customizar a aparência dos links nos estados `visited`, `hover` e `active`.

### Ajustes na Aparência do Menu
- Aplicar a classe `address` ao elemento `p` contendo o endereço "123 Free Code Camp Drive".
- Adicionar uma imagem de café abaixo do título "Coffee".

### Alinhamento e Espaçamento de Imagens
- Usar `display: block` e valores de `margin` apropriados para centralizar a imagem.
- Ajustar margem superior negativa de -25px para os elementos `img` para melhorar o alinhamento vertical.
