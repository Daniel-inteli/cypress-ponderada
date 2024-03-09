# Cypress-ponderada
## O que é o Cypress e para que serve?

O Cypress é uma ferramenta utilizada principalmente por profissionais de QA para construção de testes automatizados em aplicações. É desenvolvida em Node.js e serve para escrever e executar testes, visando garantir qualidade dos aplicativos web.

## Vantagens e desvantagens do Cypress em relação a outras ferramentas de teste.
Diferente de outras ferramentas de testes, utilizando o Cypress, o desenvolvedor consegue fazer uso de diversos recursos na mesma biblioteca, por executar diretamente no navegador, ele consegue acessar diversas informações e fornecer relatórios mais detalhados e informações mais precisas sobre os testes. 

As desvantagens do Cypress estão relacionadas com algumas limitações nativas da bibliotca, como por exemplo, a linguagem de programação, limitando a scrips de testes somente em JavaScript. Assim como limitação de testes para alguns navegadores como Internet Explorer, Safari e Opera, apesar de já estarem sendo desenvolvidas algumas atualizações de suporte para alguns desses navegadores. Outro ponto negativo é não possuir suporte para testes em dispositos móveis.


## Arquitetura do Cypress.

Como já dito anteriormente, funciona com base em Node.js e conseguentemente em JavaScript, tem como característica executar diretamente no navegador, o que fornece a possibilidade de manipular o DOM e alterar solicitações e respostas de rede conforme forem sendo executadas, também por operar diretamente no navegador, ele pode acessar funções do próprio navegador para realizar testes de comportamento na aplicação. 
O Cypress possui dois componentes principais: o Dashboard Service e o Test Runner. O dashboard permite acessar os testes que já foram executados e fornece informaçõe detalhadas através de gráficos e outros dados sobre os testes, enquanto o Test Runner é a interface que possibilita visualização dos testes em tempo real.

## Seletores de elementos no Cypress.
Os seletores são comandos que servem para apontar elementos dentro do DOM no navegador, entre os mais utilizados, temos: `.get()`, `.contains()`, `.find()`, `.next()`, entre outros. 
## Comandos e asserções no Cypress.

Os seletores servem pra direcionar ou apontar para um elemento, mas também temos alguns comandos que servem para interagir diretamente com esses elementos, como: `.check()`,`.clear()`, `.click()`, `.select()`, entre outros. Também temos comandos de asserções, que servem para verificar o estado da aplicação, entre eles: `.and()`, `.should()`, `.expect()`.

## Descrição das etapas de preparação de um testes de interface, execução e verificação no Cypress.

Para executar os testes de interface, será necessário instalar a biblioteca do Cypress no seu projeto, ela possui integrações com diversos frameworks famosos, como Angular, React, Vue, que facilitam na preparação do ambiente, após seguir o passo a passo da instalação vem a parte de escrever os testes, e para isso podemos utilizar os comandos específicos do Cypress, assim como seletores e asserções que foram comentados acima.

## Como estruturar testes de forma eficiente no Cypress?

Geralmente os testes são elaborados a partir dos casos de uso, e assim como toda elaboração de código, devemos seguir padrões e regras para manter o código limpo e legível, seguindo nessa linha, os testes devem ser construídos em blocos, utilizando `describe()` e `it()`. Também podemos utilizar das funções integradas do Cypress para tarefas mais simples e agilizar processos de configuração dos testes.