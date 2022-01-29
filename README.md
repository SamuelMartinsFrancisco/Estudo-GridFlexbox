# Estudo-GridFlexbox
Estudo sobre CSS grid e flexbox -> Formas de posicionamento de elementos

    - Divisão de toda a página em linhas e colunas
    - Colocar elementos onde quiser nessa divisão
    - Grid = duas dimensões (linhas e colunas)
    - Flexbox = Uma dimensão (linhas ou colunas)
    - São complementares

    - Propriedades
        * container ******************
            - display: grid;
            - grid-template-columns;
            - grid-template-rows;
            - grid-gap
                * grid-row-gap
                * grid-column-gap
            - grid-template-areas;
        * item(s) ******************** 
            - grid-column
                * grid-column-start
                * grid-column-end
            - grid-row
                * grid-row-start
                * grid-row-end
            - grid-area
        * Alinhamento *****************
            - justify-content
            - align-content
            - justify-items
            - align-items
            - justify-self
            - align-self

                // start
                   end
                   center
                   stretch
                   space-between
                   space-around
                   space-evenly

Observações:
    - "grid-column: 1/3" é o mesmo que: 
            grid-column-start: 1;
            grid-column-end: 3;
            //
            
            
            
Tutoriais base:
    <li> https://www.youtube.com/watch?v=x-4z_u8LcGc&t=647s&ab_channel=Origamid </li>
    <li> https://www.youtube.com/watch?v=HN1UjzRSdBk&ab_channel=Rocketseat </li>
