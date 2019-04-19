# Tutorial Angular: Construindo uma PokeDex

Este tutorial tem como objetivo desenvolver um conhecimento básico do framework Angular para incitar e facilitar as pesquisas e o auto aprendizado. Nele serão apresentados os conceitos carregados pelo framework, sua disposição e organização de arquivos, e seu funcionamento de uma forma básica.

Será desenvolvido uma PokeDex simples (baseada na [PokéAPI](https://pokeapi.co/)) com a listagem dos Pokemons da primeira geração e a visualização mais detalhada de cada um separadamente.

## Motivações

- Angular é um dos frameworks SPA (Single Page Application) mordernos mais completos e utilizados no mundo.
- Mantido pela Google.
- Angular trabalha com o conceito [Reactive Programming](https://en.wikipedia.org/wiki/Reactive_programming).
- Utiliza por padão o typescript.
- Organização te força de maneira confortável a reutilizar muito bem o código, assim melhorando a manutenabilidade, legibilidade e reduzindo code smells.

## Cronograma
- O que é um framework Single Page Application?
- Principais componentes de um App Angular
  - Modules
  - Components
  - Services
- app-component: explorando um component
  - CSS global e CSS local
  - Variaveis e one-way data bind: {{}} e []
  - Diretivas *ngIf, *ngFor
- Rotas
  - criando uma nova rota
  - rotas filhos
  - rota 404
- Criando um modulo shared e entendendo a organização
  - Shared: Módulo de componentes compartilhados
  - Módulos específicos: Agrupa componentes do sistema baseado numa atividade específica. Ex: Pokedex Module
- Iniciando a pokedex:
  - Criando um módulo para a PokeDex
  - Criando o primeiro Service
  - Entendendo (ou tentando) Observables
  - Fazendo uma requisição e se inscrevendo (subscribe) na resposta
  - Exibindo a lista dos Pokemons, componentizando cada elemento
  - Criando componente para visualização detalhada e adicionando variavel na rota
  - Deixando o módulo em lazy load

## Dependências
- Node.js 8.x ou 10.x

## Instalando Angular CLI (Command Line Interface)
Para instalar o angular de forma global basta rodar no terminal ou cmd (Windows)
```
npm install -g @angular/cli
```