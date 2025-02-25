# *CafénoLar - Página de Receitas de Café* ☕🍫🤍

## Descrição
O projeto **CafénoLar** é uma página interativa e responsiva dedicada a amantes de café. O objetivo principal é criar uma experiência imersiva, exibindo receitas deliciosas e visualmente atraentes para quem deseja preparar café em casa. A página é otimizada para dispositivos móveis e desktop, garantindo uma navegação fluída em qualquer formato de tela.

## Funcionalidades
- **Design Responsivo:** A página se adapta ao tamanho da tela do dispositivo, garantindo uma boa experiência tanto em dispositivos móveis quanto em desktops.
- **Menu Hamburguer:** Implementação de um menu colapsável para telas menores, proporcionando uma navegação mais limpa e intuitiva.
- **Animação de Entrada:** Ao carregar a página, um efeito de deslizamento de direita para esquerda é aplicado ao conteúdo principal, criando uma experiência visual dinâmica.
- **Receitas Interativas:** Seção com receitas de café que destacam as mais populares e amadas, com imagens, avaliações e descrições.
- **Footer com Créditos:** Rodapé da página com informações sobre copyright e autoria do projeto.

## Estrutura dos Arquivos

- **index.html**: Contém a estrutura básica da página, com cabeçalho (header), conteúdo principal (main) e rodapé (footer).
- **style.css**: Responsável pelos estilos e layouts, incluindo design responsivo e animações.
- **efeitos.js**: Contém os scripts para animações e funcionalidades, como o toggle do menu hamburguer e o efeito de transição do container principal.

## Detalhes do Código

### HTML (Estrutura Básica)
O HTML é estruturado em três seções principais:
1. **Header**: Contém o título da página "CafénoLar" e um menu de navegação com links para diferentes seções, incluindo "Home", "Receitas", "Novidades" e "Melhor Avaliadas". Em dispositivos móveis, um menu hamburguer é exibido, permitindo a navegação de forma compacta.
   
2. **Main**: A seção principal da página, onde estão as informações sobre novidades e as receitas em destaque. Utilizamos uma estrutura de layout flexível para garantir que os elementos se alinhem adequadamente em qualquer dispositivo.

3. **Footer**: Um rodapé simples que contém informações sobre copyright e créditos do projeto.

### CSS (Estilos e Responsividade)
O CSS é projetado para garantir que o design seja responsivo, ou seja, se ajuste bem a diferentes tamanhos de tela. As principais considerações incluem:

- **Reset de estilos globais**: Usamos o `*{}` para garantir que todas as margens e paddings sejam zeradas, criando um ponto de partida uniforme.
  
- **Estilo para o Header**: No cabeçalho, o título "CafénoLar" é destacado com a fonte "Teko". O menu é flexível e utiliza uma paleta de cores suaves, com hover effects para links de navegação. O menu hamburguer, que aparece apenas em telas menores, é implementado com a imagem `menu.png` e se ativa através do JavaScript.

- **Main e Conteúdo**: O conteúdo é dividido em seções, e o layout é flexível. Para a galeria de imagens e as receitas, utilizamos o sistema de colunas para otimizar o espaço, além de aplicar um efeito de transição para a entrada do container principal, que desliza da direita para a esquerda.

- **Responsividade**: Em telas menores que 768px (como smartphones), a estrutura do menu é alterada para um formato mais compacto. Além disso, a disposição das imagens e as receitas também se ajustam para ocupar melhor o espaço disponível.

### JavaScript (Interatividade)
O arquivo `efeitos.js` contém os scripts necessários para a interatividade da página:

1. **Efeito de Animação de Entrada (slide-from-right)**: Quando a página é carregada, o conteúdo principal (container) é animado para deslizar da direita para a esquerda, criando um efeito visual agradável.

2. **Menu Hamburguer**: O script implementa a função `menutoggle()`, que permite alternar a visibilidade do menu de navegação em dispositivos móveis. O menu expande quando clicado, revelando as opções de navegação.

### Responsividade
O design é totalmente responsivo e foi otimizado para oferecer a melhor experiência possível em qualquer dispositivo. O uso de media queries no CSS assegura que a página se ajuste de maneira eficiente:

- **Menus adaptáveis**: O menu se transforma em um menu hamburguer para dispositivos móveis, ocupando menos espaço e proporcionando uma navegação limpa.
- **Imagens e Cards**: As imagens da galeria e os cards de receitas são ajustados para se organizarem em uma coluna única em telas pequenas, e em múltiplas colunas em telas grandes.
- **Fontes e Layouts Flexíveis**: Utilização de fontes do Google Fonts para garantir legibilidade e harmonia visual, além do uso de layouts flexíveis para garantir que os elementos da página se ajustem adequadamente ao tamanho da tela.

### Página finalizada
![image](https://github.com/user-attachments/assets/094dfb18-c741-4bed-aaf2-96e5b1cfcd07)
![image](https://github.com/user-attachments/assets/c61d6fb6-d2b9-47fd-8c43-3a73f2289c03)
![image](https://github.com/user-attachments/assets/7b9c8bdc-9a5f-4a9e-9f43-980b89dc27f0)



