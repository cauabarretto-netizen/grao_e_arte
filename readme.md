☕ Grão & Arte — Torrefação e Café Especial

📌 Visão Geral e Objetivo do Projeto

O Grão & Arte é uma landing page desenvolvida para uma torrefação artesanal de cafés especiais de alta pontuação (acima de 85 pontos SCA). O projeto busca conectar pequenos produtores de café diretamente ao consumidor final, oferecendo uma experiência visual sofisticada, fluida e totalmente responsiva.

Objetivos do Projeto:

Simular um ambiente de desenvolvimento front-end profissional com foco em qualidade de código, arquitetura limpa e semântica web.

Apresentar a marca, seus microlotes exclusivos, processo de torra, clube de assinatura mensal e respostas a dúvidas frequentes.

Facilitar a conversão de clientes por meio do canal de atendimento direto via WhatsApp API.

Garantir acessibilidade, navegação suave e adaptação fluida em smartphones, tablets e desktops.
🛠️ Tecnologias e Conceitos Aplicados

Tecnologias Utilizadas

HTML5 Semântico: Estruturação utilizando tags apropriadas (<header>, <nav>, <main>, <section>, <article>, <details>, <summary>, <footer>) para otimização em motores de busca (SEO) e acessibilidade.

CSS3 Moderno: Estilização com variáveis globais (Design Tokens), Flexbox e media queries.

Google Fonts: Importação e tipografia com as famílias Merriweather (títulos) e Open Sans (corpo de texto).

Placehold.co / Unsplash: Provedores de imagens e placeholders temáticos em alta qualidade.

Conceitos e Boas Práticas Adotadas

Metodologia BEM (Block Element Modifier): Padronização rigorosa na nomenclatura de classes no HTML e seletores no CSS (bloco__elemento--modificador), promovendo manutenibilidade e legibilidade do código.

Arquitetura CSS e Separação de Responsabilidades: Rigorosa divisão entre conteúdo (HTML) e estilo (CSS), sem uso de estilos inline ou blocos <style> embutidos.

Escala de Tipografia com REM: Definição da fonte base no elemento raiz (html) e uso exclusivo da unidade relativa rem para fontes, espaçamentos (padding/margin) e bordas.

Unidades do Layout Relativas: Uso de porcentagem (%) para containers flexíveis, unidades de viewport (vh e vw) para seções em tela cheia e restrição de pixels (px) estritamente a bordas e detalhes finos.

Acessibilidade e Microinterações: Feedback visual suave via pseudo-classes (:hover, :focus), transições (transition) e elevação de cards (box-shadow).

Navegação Smooth Scroll & Offset: Rolagem suave (scroll-behavior: smooth) combinada com compensação de recuo superior para evitar sobreposição do menu fixo nos títulos das seções.
🚀 Instruções de Visualização e Execução

Para visualizar e testar o projeto localmente, siga os passos abaixo:

1. Clonar o Repositório

git clone https://github.com/seu-usuario/grao-e-arte.git
cd grao-e-arte


2. Executar a Aplicação

Como a aplicação foi desenvolvida puramente em HTML5 e CSS3, não é necessária a instalação de dependências de ambiente ou compiladores.

Opção 1: Abra o arquivo index.html diretamente em qualquer navegador moderno (Google Chrome, Firefox, Edge, Safari).

Opção 2 (Recomendado): Utilize a extensão Live Server no VS Code para ter atualização em tempo real ao modificar arquivos:

Abra a pasta do projeto no VS Code.

Clique com o botão direito sobre o arquivo index.html.

Selecione "Open with Live Server".

💡 Principais Desafios Técnicos e Aprendizados

1. Compensação do Menu Fixo na Navegação Interna (position: fixed)

Desafio: Ao utilizar position: fixed no topo (<header>), a navegação por links âncora (#inicio, #graos, etc.) fazia com que o menu cobrisse a parte superior dos títulos das seções.

Solução: Aplicação de propriedades como scroll-margin-top nas seções do layout para compensar exatamente a altura do menu, garantindo que o título apareça perfeitamente visível após o clique.

2. Implementação Rigorosa de Unidades Relativas (rem, %, vh)

Desafio: Manter o layout totalmente proporcional e legível em qualquer resolução de tela sem recorrer ao uso fácil de pixels (px).

Solução: Configuração da porcentagem base da fonte na raiz (html { font-size: 62.5%; } ou proporcional) para facilitar a conversão de rem, combinada com o uso de vh para áreas de tela cheia no Banner Principal e % na largura de cards flexíveis.

3. Estruturação Semântica do FAQ com Componentes Nativos

Desafio: Criar uma seção de Perguntas Frequentes interativa e acessível sem depender de JavaScript.

Solução: Utilização dos elementos semânticos HTML5 <details> e <summary>, estilizando o indicador de expansão e criando uma transição suave de abertura/fechamento apenas via CSS.

4. Aplicação do Padrão BEM e Manutenibilidade do CSS

Desafio: Evitar o vazamento de estilos entre componentes e seletores CSS frágeis.

Solução: Adoção estrita da nomenclatura BEM (ex: .card-grao__title, .nav__link--active), tornando o código autoexplicativo, altamente reutilizável e desacoplado da estrutura HTML.

📄 Licença e Créditos

Projeto desenvolvido como parte da atividade prática do módulo de desenvolvimento Web Front-End (SENAI Henrique Lupo).

Cliente Fictício: Grão & Arte — Torrefação e Café Especial

Ano: 2026