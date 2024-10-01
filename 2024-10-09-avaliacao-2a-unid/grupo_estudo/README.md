# Projeto da Segunda Unidade de Desenvolvimento Web 1

Nesse projeto você vai criar as páginas para um site de uma empresa. Essas páginas devem ser responsivas de acordo com as definições do projeto do figma. O layout deve quebrar nas larguras abaixo, diferente disso apenas se adaptar a mudança da largura:
- Desktop: 1440px
- Mobile: 375px

O projeto é composto por 4 páginas, e no modo Desktop podemos ver as opções de menu abaixo associadas as suas páginas que devem ser abertas ao clicar na opção do menu:
- Home: index.html
- Disciplinas: disciplinas.html
- Planos: planos.html
- Contato: contato.html

Obs: As páginas já estão com o texto das páginas para vocês ganharem tempo! É preciso organizar a estrutura delas com os elementos HTML.

Use em seu código:
- Variáveis para as cores
- Reset no início do css
- Valorize os seletores de menor especificidade possível
- Evite o uso de IMPORTANT
- Tente reutilizar formatações, para não ficar muito repetitivo no código css

Atenção:
- No figma é possível verificar informações como espaçamento entre os elementos, no arquivo ZIP do projeto tem uma pasta layout com todos as telas e suas variações
- Os layouts são simples, não complique o HTML com estruturas desnecessárias!
- NÃO GERE O CÓDIGO A PARTIR DE PLUGINS DO FIGMA, É POSSÍVEL IDENTIFICAR ISSO!!!!

## Todas as páginas
- No modo Mobile o menu deve ser escondido e um botão de sanduíche deve ser exibido em seu lugar! 
- Cores:
    - Background: #74C69D
    - Botão: #212529
    - Texto: #ffffff
- Ao passar o mouse sobre o menu:
    - Mudar a cor do texto das opções para: #5569AF
    - E o background das opções para: #FAAD3A
    - ![alt text](image.png)    
- Botões:
    - Background color: #EEEEEE
    - Bordas arredondadas: 5px
- Os textos estão usando formatação no CSS para estarem com todas as primeiras letras em maiúsculas como no exemplo abaixo:
    - Atualmente Estamos Estudando As Seguintes Tecnologias
- O logo do TADS aparece na aba de cada página
- ![alt text](image-1.png)


## Home
- Usar grid areas para o layout dos componentes
- Usar flexbox para o interior dos componentes
- Ao passar o mouse sobre o botão Explore:
    - Mudar sua largura para 100% do container
    - Aplicar um efeito para que a transição dure 1 segundo para terminar

## Portfolio
- Usar grid com controle de quantidade de colunas (sem area) para o layout dos componentes

## Planos
- Os indicadores verdes ao lado dos itens devem ser um ícone do Material Icons: https://fonts.google.com/icons
- Os planos tem uma sombra ao redor das caixas, não deixem de fazer!

## Contact Us
- Os campos dos formulários devem ter: 
    - background color: #EEEEEE
    - Bordas arredondadas: 5px

## Extra
- Tente exibir o menu ao clicar no Sanduiche! 
- Fizemos isso em sala e você pode usar o target ou um checkbox para isso!
    - O menu deve ser exibido por cima da página atual (POSITION)
    - O menu deve apresentar as opções na vertical
