## Pré-requisitos

Quais são os pré-requisitos para ler o livro? Antes de tudo, você deve estar familiarizado com o básico de desenvolvimento *web*. Deve saber como utilizar HTML, CSS e JavaScript. Talvez faça sentido também conhecer o termo [API][1], porque você irá utilizá-las no livro. No mais, eu lhe encorajo a entrar no [Grupo do Slack][2] oficial, para obter ajuda ou ajudar outras pessoas.

### React

Este livro utiliza React como biblioteca para ensinar o gerenciamento moderno de estado. Ele é a escolha perfeita, para demonstrar e aprender gerenciamento de estado em aplicações do mundo de hoje. Pelo motivo de React ser apenas uma camada de visão, fica a seu critério como lidar com o estado em sua aplicação. A camada de gerenciamento de estado pode ser permutada.

No fim, nem é necessário ser um desenvolvedor React, para aprender a respeito de gerenciamento de estado. Se você está desenvolvendo com algum outro *framework* (como Angular), ou biblioteca (como Vue), todas as coisas ensinadas aqui poderão ser utilizadas em suas aplicações.

Ainda assim, uma vez que o livro utiliza React para o propósito de ensinar gerenciamento de estado em um contexto, se você não estiver familiarizado com React ou precisar relembrar o tópico, eu lhe encorajo a ler o livro que precede este: [The Road to learn React][3]. Ele deve tornar qualquer um apto a aprender React e é gratuito. Se você quiser, pode pagar qualquer valor por ele, com o intuito de apoiar o projeto.

E, apesar de *The Road to learn React* não custar nada, pessoas que receberam pouca educação formal não têm acesso à estes recursos. Elas precisariam ter conhecimento de inglês (ou um dos idiomas das traduções oficiais) para poder consumi-los. *The Road to learn React* tenta, de vez em quando, [apoiar iniciativas de educação nos países em desenvolvimento][4], não sendo esta uma tarefa fácil, por o livro estar disponível no formato "pague quanto quiser".

*The Road to learn React* também lhe fornece a transição de JavaScript ES5 para JavaScript ES6. Depois de lê-lo, você irá possuir todo o conhecimento necessário para ler este livro, que se encaixa perfeitamente como a sequência para o primeiro.

### Editor e Terminal

E quanto ao ambiente de desenvolvimento? Você irá precisar de um editor de texto ou IDE e um terminal (ferramenta de linha de comando). Você pode [seguir meu guia de *setup*][5]. Ele foi concebido para usuários de MacOS, mas você pode encontrar um guia de *setup* para Windows também. Em geral, existe uma tonelada de artigos por aí, que irão lhe mostrar como configurar um ambiente de desenvolvimento para *web*, de forma mais elaborada para o seu SO.

Opcionalmente, você pode utilizar git e GitHub, enquanto prossegue pelos exercícios no livro, para manter seus projetos e progresso em um repositório. Eis um [pequeno guia][6] sobre como utilizar estas ferramentas. Mas, de novo, não é algo mandatório para acompanhar o livro e pode ser até um pouco demais, se tiver que aprender tudo ao mesmo tempo, do zero. Se você é novato no desenvolvimento *web*, pode pular esta parte e focar nas questões essenciais ensinadas neste livro.

### Node e NPM

Por último, mas não menos importante, você precisará ter instalados [node e npm][7]. Ambos são utilizados para gerenciar bibliotecas que você irá precisar ao longo do caminho. Neste livro, você irá instalar vários pacotes *node* via *npm* (*node package manager*). Estes pacotes podem ser desde bibliotecas, até *frameworks* inteiros.

Verifique suas versões instalada de *node* e *npm* pela linha de comando. Se não obtiver nenhum retorno no terminal, significa que precisará instalar ambos primeiro. As versões que possuo, no momento em que escrevo este livro, são:

{title="Linha de Comando",lang="text"}
	node --version
	*v8.9.4
	npm --version
	*v6.1.0

Se você leu *The Road to learn React*, já deve estar familiarizado com este *setup*. O livro lhe fornece uma pequena introdução sobre o ecossistema do *npm* na linha de comando. Caso ainda não saiba muito à respeito, recomendo, mais uma vez, que procure ler o primeiro livro.

[1]:	https://www.robinwieruch.de/what-is-an-api-javascript/
[2]:	https://slack-the-road-to-learn-react.wieruch.com/
[3]:	https://www.robinwieruch.de/the-road-to-learn-react/
[4]:	https://www.robinwieruch.de/giving-back-by-learning-react/
[5]:	https://www.robinwieruch.de/developer-setup/
[6]:	https://www.robinwieruch.de/git-essential-commands/
[7]:	https://nodejs.org/en/