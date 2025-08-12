Primeiro passo instale o Angular: `npm install -g @angular/cli`
Segundo passo: (como o meu projeto é simples eu precisei mudar um pouco a rota de instalação)
Insira no git bash `ng new senpai-social --no-standalone`
Em seguida nas perguntas foram: 
1 - Would you like to enable autocompletion? This will set up your terminal so pressing TAB while typing Angular CLI commands will show possible options and autocomplete arguments. (Enabling autocompletion will modify configuration files in your home directory.) (Y/n)
(Tradução simplificada: Essa mensagem é do Angular CLI perguntando se você quer habilitar o autocompletion — ou seja, permitir que ao digitar comandos e apertar TAB, ele sugira e complete automaticamente os comandos e argumentos disponíveis. Eu informei "y" pois isso facilita no processo de criação.)

2 - Would you like to share pseudonymous usage data about this project with the Angular Team at Google under Google's Privacy Policy at https://policies.google.com/privacy. For more details and how to change this setting, see https://angular.dev/cli/analytics. (Y/n)
(Tradução simplificada: ele está perguntando se você autoriza compartilhar dados anônimos de uso com a equipe do Angular no Google. Eu informei "y" pois autorizo.)

3 - Do you want to create a 'zoneless' application without zone.js (Developer Preview)?(Y/n)
(Esse é um prompt novo do Angular CLI, especialmente nas versões mais recentes (como Angular 17+). Ele está perguntando se você quer criar uma aplicação "zoneless", ou seja, sem usar zone.js — uma biblioteca que o Angular usa para detectar mudanças e atualizar a interface automaticamente. Ou seja, não é recomendado para iniciantes ou projetos que precisam de estabilidade. A própria pergunta já avisa que é uma funcionalidade experimental. Inseri "n" pois como estou aprendendo não é recomendado.)

4 - Ele questiona qual dos 3 tipos quero usar:
CSS - Folhas de estilo padrão - Quem quer simplicidade
SCSS - Suporte a variáveis, aninhamento, mixins - Projetos mais avançados
SASS, LESS, Stylus - Outras opções menos comuns - Casos específicos
(Para o meu projeto selecionei o CSS)

5 - Do you want to enable Server-Side Rendering (SSR) and Static Site Generation (SSG/Prerendering)?
(Tadução simplificada: Você quer habilitar Server-Side Rendering (SSR) e Static Site Generation (SSG)? O conteúdo da página é gerado no servidor antes de ser enviado ao navegador. Ou O Angular gera páginas estáticas durante o build. Como estou criando um projeto padrão, informei "n").

6 - https://copilot.microsoft.com/shares/YgnZWGs5XYsDPoXBaJWWS
