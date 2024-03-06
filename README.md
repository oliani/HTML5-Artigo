# HTML5 e a aplicação de Web Components e APIs

A versão mais recente da linguagem de marcação HTML é o HTML5, usada para estruturar página na web. Várias novidades foram introduzidas na última versão, como o suporte a coponentes, APIs de armazenamento local, e muitas outras melhorias.

Uma das principais novidades, são os webcomponents, que são elementos customizáveis que podem ser reaproveitados ao longo de várias telas, tornando o desenvolvimento mais rápido e pradronizado. A reutilizaçào de códigos é fundamental para facilitar e estruturar páginas web.

Os Web Components são formados por três tecnologias principais, que podem ser usadas juntas para criar elementos customizáveis de acordo com a necessidade de uso. Esses elementos podem ser reutilizados sem preocupação com conflito de código.

Eles basicamente são divididos em elementos customizados, que permitem que seus comportamentos sejam customizados; Shadow DOM, que é um conjunto de APIs JavaScript que incorpora uma árvore DOM encapsulada a um elemento, que é renderizada paralelamente ao DOM original do documento principal; e Templates HTML, que permitem que você escreva templates de marcação que não são exibidos na página.
Todos eles são reutilizáveis e podem ser utilizado diversas vezes ao longo do código.

Existem várias bibliotecas com componentes já pré-estruturados que facilitam ainda mais o desenvolvimento de aplicações web, padronizando e tornando ainda mais simples o seu uso.

Web Components também facilitam muito a acessibilidade, do ponto de vista do usuário. Com uma boa acessibilidade você permite que um usuário acesso o conteúdo da melhor forma possível.

A semântica também é um ponto muito importante, pois com quanto melhor ela for desenvolvida mais fácil é a aplicação dos WebComponents. Para usar Web Coponents, a semântica correta para a criação de um deve ser no seguinte padrão: `<meu-elemento>`. Enquanto o seguinte padrão está errado: `<meuElemento>`. 
Além de usar o hífen, algumas combinações de palavras reservadas também não poderão ser usadas como: `annotation-xml`, `color-profile`, `font-face`, `font-face-format`, `font-face-name`, `font-face-src`, `font-face-uri` e `missing-glyph`.

A performance é outro fator muito importante em sites e aplicações web. De que adianta o usuário ter acesso a melhor versão da página se ela demora muito pra carregar? Existem várias comprovações de que quanto uma página demora muito pra carregar, o usuário acaba desistindo de fazer o acesso. Diante desse cenário, os Web Components foram otimizados para que sejam carregados em tempo hábil.

As APIs web, como citado anteriormente, são construções disponíveis nas linguagens de programação que permitem a desenvolvedores criar funcionalidades complexas mais facilmente. Elas servem para você escrever um código de mais baixo nível que controla diretamente a GPU, por exemplo, facilitando o uso dos componentes disponíveis no dispositivo do usuário.

Existem muitas APIs disponíveis, nos navegadores modernos, que permitem uma liberdade de ação na hora de desenvolver uma aplicação. As categorias mais comuns de APIs são: **APIs para manipular documentos** carregados no navegador, **APIs**  **que buscam dados no servidor** para atualizar pequenas seções da página, **APIs para desenhar e manipular elementos gráficos** são completamente suportados nos browsers, **Audio and Video APIs** que permiten a você controlar multimedia como a criação personalizada controles de UI para executar audio e video, **Device APIs** São basicamente APIs para manipulação e recuperação de dados de hardware de dispositivo moderno de uma forma que seja útil para aplicativos da web, **Client-side storage APIs** estão se tornando muito mais difundidos em navegadores da web - a capacidade de armazenar dados no lado do cliente é muito útil se você quer criar um app que vai salvar seu estado entre carregamentos de página.

Toda essa combinação de APIs tornam o desenvolvimento mais fácil e tornar o uso da aplicação mais efetivo por parte do usuário.
