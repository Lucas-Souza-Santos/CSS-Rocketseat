# CSS-Rocketseat
Curso básico de css

# Introdução

##  O que significa CSS ?
* Cascading Style Sheet 
* Código para criar estilos no HTML 
* HTML é a estrutura, e o CSS é a beleza 
* Não é uma linguagem de programação
* É uma linguagem de style sheet

## Comentários 
* Não irá afetar o seu código 
* Ajuda a lembrar blocos de códigos 
* Deixa dicas para leitura 
* Ajuda outros a entenderem 
* Nunca esqueça de fechar um comentário aberto 

Comentários começa com `/*` e terminan com `*/`

```
    CSS

    /*Básico*/
    /*------------------------*/
    
    body{
        font: 1em/150% Helvetica, Arial, sans-serif;
        padding: 1 em;
        margin: 0 auto;
        max-width: 33em;
    }

```

# Anatomia 
```
    CSS
    h1{
        color: blue;
        font-size: 60px;
        background: gray;
    }
```

* Selector
* Declaration 
* Properties 
* Property Value 

# selector
    Conecta um elemento HTML com o CSS 

## Tipos 
* Global selector `*`;
* Element/Type selector `h1, h2, p, div`
* ID Selector `#box, #container`
* Class Selector `.red, .m-4`
* Attribute selector, Pseudo-class, Pseudo-element, e outros

# Caixas 
* Você irá perceber que (quase ) tudo são caixas do CSS
* Posicionamentos, tamanhos, espaçamentos, bordas, cores 
* Caixa pode ficar ao lado uma da outra, ou acima 
* Elementos HTML são caixas

# Adicionando CSS 

## inline 
* atributo `style`

## <style>
* tag html que irá conter o css 

## <link>
* arquivo css externo 

## @import 
* arquivo css externo

