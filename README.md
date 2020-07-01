# flexbox_twitter
 Copy of the Twitter layout to practice FLEXBOX - rocketseat
 
 Veio com o CSS3 para a criação de layouts responsivos. Essa tecnologia veio adaptada e inspirada na maneira em que o Android utiliza o 'linear layout' que estiliza as aplicações. Trouxe umagrande flexibilidade para trabalhar com layouts adaptativos na web (diferentes tamanhos de tela).  

VsCode → extensão: Live Server

ctrl+shift+p → Live Server: Open with Live Server

### Começando com o flexbox

colocar 'display: flex; ' na div ou elemento que estiver por fora dos elementos que queremos alinhar.

'flex-direction: row' → propriedade padrão do flexbox

### Alinhamento de conteúdo

'align-items: flex-end' → alinha os elementos no eixo contrario ao direction

- flex-start
- flex-end

'justify-content: space-around' → alinha os elementos no mesmo eixo

- space-around
- space-between

### Redimensionamento

'flex-grow: 1'    → componentes ocupam toda largura disponivel em tela

'flex-shrink: 1'   → diz se nosso componente tem a capacidade de se espremer

'flex-shrink: 0'   → cria a barra de rolagem

flex = grow + shrink → 'flex: 1 0'; → '**flex: 1**';

### Configurando WARP de itens

'flex-wrap: wrap' → quebra de linha

nova propriedade de alinhamento:

'align-content: center ' → alinhar os elementos quando estao e mais de uma linha

- center
- flex-start
- flex-end
- space-around
- space-between
- 

### Ordenação

Quando o layout é resposivo as vezes os componentes tem que trocar de posição

'order: 0;'     'order: 1;' 

# Twitter:

**Dar um 'reset' nos elementos nativos**

* {

margin: 0;

padding: 0;

box-sizing: border-box;

}

box-sizing: border-box; → faz um padding interno ex 300 - 20 de cada lado

**Site para encontrar Icons:**

[https://www.iconfinder.com/](https://www.iconfinder.com/)


![WhatsApp Image 2020-07-01 at 10 44 57](https://user-images.githubusercontent.com/47497767/86256399-ac60da00-bb8e-11ea-970f-0044ce52e83b.jpeg)
![WhatsApp Image 2020-07-01 at 10 44 21](https://user-images.githubusercontent.com/47497767/86256405-acf97080-bb8e-11ea-9dbe-087daac60fc2.jpeg)

