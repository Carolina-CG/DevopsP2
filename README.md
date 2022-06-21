# DevopsP2 
Simulado e Conteudo 

https://gitlab.com/a9898/ecm971-projetoapimusica/-/tree/AtividadeT2

### Ex1

```Descreva o funcionamento de cada stage de seu projeto. Cite explicitamente o nome de cada e, a seguir, explique seu funcionamento. ```

Stage do projeto:
 *  Stage Build - responsável pela instalação do software, suas aplicações e pela criação do projeto.  
 *  Stage Test - testa suas aplicações , verificando se instalação e execução estão certas, sendo eles
- ping pong: conexão com o ping para retornar uma resposta de pong.
- testa ordenacao: ordena uma avaliação dos termos, depois do seu nome. 
- cadastra musica: cadastros dos itens (musicas). 

### Ex2

```Considerando que seu grupo conclua o stage de deploy no Heroku, é possível dizer que ao longo do desenvolvimento desde a primeira fase, seu projeto teve caracterizada a entrega contínua? Responda sim ou não explicitamente e explique.```

NÃO, no nosso projeto não tem características de entrega continua. Pois a entrega continua se da a um curto período de tempo, e no desenvolvimento do projeto fizemos todas as aplicações e um deploy foi feito depois de concluir a parte do desenvolvimento e os testes serem executados corretamente. 

### Teste Unitário

```
O que é ?
```

É uma prática de desenvolvimento de software onde os desenvolvedores, com frequência, unem as suas alterações de código em um repositório central onde são aplicados os testes automatizados antes do deploy da aplicação.

Os unitários, por serem testes em trechos pequenos, são de maior importância durante a etapa de desenvolvimento, onde o programador pode ter um feedback quase que imediato do trechinho que está desenvolvendo.

O teste unitário consiste em verificar o comportamento das menores unidades em sua aplicação. Tecnicamente, isso seria uma classe ou até mesmo um método de classe em línguas orientadas a objetos, e seria um procedimento ou função em línguas processuais e funcionais.

### Entrega Continua 

```
O que é ?
```
Presente no Manifesto Ágil, a entrega contínua também conhecida como DevOps é uma abordagem que prevê ciclos curtos de entrega de softwares, por exemplo. Assim, eles são lançados a qualquer momento e de forma confiável.

A abordagem DevOps normalmente envolve a criação de um pipeline de entrega contínua. A metodologia DevOps descreve abordagens que ajudam a acelerar os processos necessários para levar uma ideia do desenvolvimento à implantação em um ambiente de produção no qual ela seja capaz de gerar valor para o usuário.

Entrega contínua é uma abordagem na qual os times de desenvolvimento lançam produtos de qualidade de forma frequente, previsível e automatizada. Em vez de fazer grandes entregas de uma vez, fazem várias pequenas e rápidas — reduzindo as chances de erros e conquistando maior controle de qualidade.


### delivery em uma plataforma (heroku)

```
O que é Heroku?
``` 

Trata-se de uma PaaS (Plataforma como um Serviço) que permite hospedagem, configuração, testagem e publicação de projetos virtuais na nuvem. Entre outras funções, ele facilita o trabalho dos desenvolvedores na configuração da infraestrutura para o deploy, ou seja, a implantação das aplicações.

Uma das formas para hospedar uma aplicação na Heroku é por um repositório no GitHub, uma plataforma de hospedagem de código fonte. Se você não usa ainda, corre! Primeiro você precisa criar o repositório e colocar todo o código da aplicação lá.


