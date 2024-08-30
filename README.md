# Módulo: Fundamentos do Bootstrap

---

## Módulo de Aprendizado

Este projeto se destina à avaliação dos conhecimentos adquiridos no módulo de aprendizado Fundamentos do Bootstrap.

Uma ferramenta já pouco utilizada, mas que foi muito importante, é o Bootstrap. Seu paradigma de criar páginas utilizando um sistema pré configurado de grid com vários componentes já estilizados, certamente trouxeram praticidade e agilidade para que desenvolvedores web trouxessem à vida seus projetos.

Por trás dos panos, o Bootstrap utiliza a tecnologia <code>SASS</code> para criar uma arquitetura modular e altamente customizável. Utilizando as várias ferramentas que o <code>SASS</code> oferece, o Bootstrap vem com dezenas de componentes como Modais, Alertas, Abas de Navegação, Tooltips, Formulários, Tabelas, entre outras, já estilizadas e prontas para uso, não requerendo nenhuma estilização ou criação de dinamismo por parte do usuário. Bastava consultar sua documentação e sair utilizando seus componentes.

Hoje em dia, para aplicações mais robustas, principalmente utilizando <i>frameworks</i> bem estabelecidos como o React, Angular ou Vue, o Bootstrap possa ter perdido um pouco de espaço, principalmente pelo uso extensivo do <code>Tailwind CSS</code> como alternativa. Porém, o estudo e aplicação do Bootstrap em módulos de ensino é justificável, principalmente do ponto de vista de importância e de seus paradigmas.

## O Projeto

Se trata da criação de um formulário simples que permita o usuário entrar com seu Nome, E-mail e Telefone.

### Funcionalidades exigidas e implementadas:

-   Adicionar o Bootstrap em uma página HTML utilizando a CDN;
-   Nesta página HTML, crie um formulário de cadastro que deverá conter os campos: nome, e-mail e telefone, e um botão para o envio;
-   Aplique as classes do Bootstrap nos elementos do formulário;
-   Crie uma branch chamada <code>exercicio_bootstrap</code> no repositório do curso.

### Funcionalidades adicionais implementadas:

-   Um footer para informações sobre a implementação;
-   Máscaras de formato de envio do e-mail e telefone utilizando o plugin <i>Mask</i> do jQuery;
-   Validação ativa dos campos do formulário, mostrando para o usuário quais campos ele deve preencher e como preencher, utilizando o plugin <i>Validate</i> do jQuery;
-   Alertas mostrando o envio ou não do formulário, com diferentes classes do Bootstrap para controlar a estilização;
-   Um alerta do tipo <code>primary</code> mostrando quais foram os dados fornecidos pelo usuário;
-   Os alertas sendo apresentados com a utilização do método <code>setTimeOut()</code> do componente <code>window</code> do DOM.

## Tecnologias utilizadas

-   [Bootstrap v5.3.3](https://getbootstrap.com/)
-   [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
-   [CSS3](<https(://developer.mozilla.org/en-US/docs/Web/CSS)>)
-   [Vanilla JS (ES6)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
-   [jQuery v3.7.1](https://jquery.com/)
-   [Validate, um plugin jQuery v1.19.5](https://jqueryvalidation.org/)
-   [jQuery Mask, um plugin jQuery v1.14.16](https://igorescobar.github.io/jQuery-Mask-Plugin/)
-   [VS Code](https://code.visualstudio.com/Download)

## Desafios resolvidos e conclusão

Durante a implementação não houve grandes desafios, pois, já havia tido a oportunidade de trabalhar com criação de outros antes. Talvez o
maior fluxo de pensamento criatividade ficou devido criação das funções que fazem a adição dos e as devidas utilizações método <code>setTimeOut()</code>. estilização foi básica, já o foco era na utilização do Bootstrap criação da aplicação. Portanto, mesmo sendo uma tecnologia de entrada pacotes de implementação desenvolvidos para o desenvolvimento web, Bootstrap ainda se mantém uma excelente alternativa desenvolvedores novatos simplesmente aventureiros do desenvolvimento web, já proporciona agilidade facilidade em lidar com dinâmicas um pouco avançadas como Modais e Alertas.
