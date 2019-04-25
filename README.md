# Frontend no Grupo Rovema
Somos uma empresa que atua em vários segmentos de mercado, com diferentes tecnologias, culturas e desafios. Por isso, gostamos de compor nossos times com profissionais multidisciplinares, que tenham alta capacidade de aprendizado, sejam detalhistas, resiliêntes, questionadores e curiosos. Você, como **Frontend Developer**, será o responsável por implementar, dar manutenção, aplicar correções e propor soluções em projetos de software, sempre buscando a melhor composição de tecnologias para cada cenário.

## Orientações
Para executar o desafio de **Frontend Developer**, você **deverá utilizar alguma framework Frontend (Angular, VueJS, React, EmberJS)** que for **confortável para você**, seguindo o [passo-a-passo](https://github.com/rovema/frontend-test#etapas) para a execução, atendendo aos [critérios de aceitação](https://github.com/rovema/frontend-test#crit%C3%A9rios-de-aceita%C3%A7%C3%A3o).

## Desafio
Nossa equipe é apaixonada por **Rick and Morty**, assim, o seu desafio será criar uma aplicação utilizando a API pública da série [https://rickandmortyapi.com/](https://rickandmortyapi.com/), para exibir a lista de  personagens. Veja a documentação [https://rickandmortyapi.com/documentation/#rest](https://rickandmortyapi.com/documentation/#rest).

Os requisitos da aplicação:

- Como usuário, desejo visualizar na página inicial, uma lista de 20 personagens, contendo **foto**, **nome** e **status**.
- Como usuário, desejo clicar em um personagem da lista, para visualizar informações detalhadas.
- Como usuário, desejo filtrar os personagens por **nome**, **espécie** e **status**.

## Etapas

#### 1 - Fazer um fork desse repositório
![https://i.imgur.com/o7tdjVJ.png](https://i.imgur.com/o7tdjVJ.png)


#### 2 - Criar um branch com o seu primeiro e último nome
```bash
git checkout -b joao-silva
```

#### 3 - Escreva a documentação da sua aplicação
Você deve, substituir o conteúdo do arquivo **README.md** e escrever a documentação da sua aplicação, com os seguintes tópicos: 
- **Projeto**: Descreva o projeto e como você o executou. Seja objetivo.
- **Tecnologias**: Descreva quais tecnologias foram utilizadas, enumerando versões (se necessário) e os links para suas documentações, bem como, qual guia de estilos de código você utilizou com o link para a sua documentação.
- **Como rodar**: Descreva como iniciar a sua aplicação, utilizando **Docker** e **Docker Compose**.

#### 4 - Faça uma Pull Request
Após implementada a solução, crie uma [pull request](https://github.com/rovema/frontend-test/pulls) com o seu projeto para esse repositório.

## Critérios de Aceitação
Para que seu teste tenha o mínimo necessário que atenda aos requisitos esperados, ele deve:
- Atender ao que foi proposto no [Desafio](https://github.com/rovema/frontend-test#Desafio).
- Automatização de build-scripts (Gulp, webpack, etc).
- Utilização de pré-processadores CSS (Sass, Less).
- Interfaces responsivas para desktop, tablets e smartphones.
- Compatibilidade entre browsers.
- Padrão de escrita CSS (BEM, OOCSS, SMACSS).
- Código JS escrito com base em algum guia de estilos: [AirBnB Standards](https://github.com/airbnb/javascript) ou [Javascript Standards](https://standardjs.com/).
- Utilizar padrões semânticos em mensagens de commit. (Gostamos do padrão de commits do repositório [AngularJS](http://karma-runner.github.io/3.0/dev/git-commit-msg.html))
- Sua aplicação deve conter uma implementação como container Docker.


## Dicas e Informações Valiosas

#### O que gostaríamos de ver em seu teste:
- Testar ele localmente com docker e validar comportamento de interfaces.
- Se possível, que seu teste estivesse hospedado em algum lugar. (Gostamos do [Heroku](https://www.heroku.com/)).
- Convenção de nome em classes, objetos, variáveis, métodos e etc.
- Um planejamento de entrega das tarefas do seu desafio. (Gostamos de [Kanban](https://blog.runrun.it/o-que-e-kanban/)).
- Testes automatizados.

**Observação:** Nenhum dos itens acima é obrigatório.

#### O que não gostaríamos de ver no seu teste:
- Saber que não foi você quem implementou.
- Processos manuais de inicialização da aplicação e build-scripts.
- Falta de organização de código.
- Falta de documentação.
- Histórico de commits desorganizado e despadronizado.
