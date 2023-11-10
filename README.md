<div align="center">

  ![Logo Dark](assets/reprograma-fundos-escuros.svg#gh-dark-mode-only)

</div>

<div align="center">

  ![Logo Light](assets/reprograma-fundos-claros.png#gh-light-mode-only)

</div>

# Tema da Aula

Turma Online 28 - Imersão JavaScript | Semana 09 | 2023 | Professora: [Luara Kerlen](https://github.com/luarakerlen)

### Instruções
Antes de começar, vamos organizar nosso setup.
* Fork esse repositório 
* Clone o fork na sua máquina (Para isso basta abrir o seu terminal e digitar `git clone url-do-seu-repositorio-forkado`)
* Entre na pasta do seu repositório (Para isso basta abrir o seu terminal e digitar `cd nome-do-seu-repositorio-forkado`)
* [Add outras intrucoes caso necessario]

### Objetivo
Refatorar o código do projeto em andamento.

### Resumo
O que veremos na aula de hoje?
- [Tema da Aula](#tema-da-aula)
    - [Instruções](#instruções)
    - [Objetivo](#objetivo)
    - [Resumo](#resumo)

- [Conteúdo](#conteúdo)

  - [O que é](#o-que-e)
  - [Para que serve](#para-que-serve)
  - [Por que refatorar?](#por-que-refatorar)
  - [Processo de refatoração](#processo-de-refatoração)
  - [Como refatorar?](#como-refatorar)

- [Vamos praticar!](#vamos-praticar)
- [Contatos](#contatos)

# Conteúdo

## O que é
Refatoração é o **processo de alterar o código fonte** de uma maneira que **não altere seu comportamento** externo e ainda melhore a sua estrutura interna. É uma técnica disciplinada de limpar e organizar o código, e por consequência minimizar a chance de introduzir novos bugs.

## Para o que serve
Ela é utilizada para manter um software bem projetado mesmo com o decorrer do tempo e as mudanças que ele virá a sofrer. 

O código sofre grandes alterações ao longo do tempo, alterações capazes de mudar toda a sua estrutura inicial. Com várias equipes de desenvolvimento trabalhando, as vezes podem gerar certos code smells, pequenas bagunças que precisam ser ajustadas.

O processo de refatoração é uma otimização. Precisamos sempre pensar em código para melhorar a sua conformidade com padrões e a legibilidade.

OBS: A refatoração visa apenas à melhoria interna do código fonte.

## Por que refatorar?
Refatorar o software é uma técnica que pode, e deve, ser utilizada por diversas razões. Vejamos algumas delas:

### 1. Melhora o projeto
Sem refatoração a estrutura interna de um software geralmente se degrada com as mudanças que ocorrem no decorrer do tempo. Programadores que nunca viram o código antes são encarregados de adicionar uma nova funcionalidade e provavelmente vão fugir um pouco do padrão que foi utilizado quando o software foi projetado. Aplicar refatoração após a adição dessa nova funcionalidade poderá deixá-la em conformidade com os padrões que foram utilizados nas outras funcionalidades que o software já possui;

### 2. Torna o software fácil de entender
Desenvolvedores geralmente estão sempre com pouco tempo para terminar suas tarefas e entregar a funcionalidade pronta. Para conseguir entregar dentro do prazo, alguns acabam se apressando na hora de codificar, o que pode prejudicar a legibilidade (clareza do código) e alguns bugs podem passar despercebidos. 
> Erros comuns são: não nomear as variáveis corretamente, duplicar código, colocar métodos em classes inadequadas, entre outros. Ao empregar a refatoração, muito provavelmente, tais "sujeiras" serão removidas do código, o que o tornará muito mais fácil de compreender e manter;

### Ajuda a achar bugs
Quando um desenvolvedor vai refatorar certo código, ele deve entender exatamente o que aquele código está fazendo. Entendendo muito bem o seu funcionamento, os possíveis bugs existentes naquele código acabam se tornando evidentes. Como o desenvolvedor já está alterando o código, recomenda-se também eliminar o bug;

### Ajuda a programar mais rápido
Com todas as vantagens citadas até agora, pode-se notar que quando a refatoração é aplicada por uma pessoa que tem domínio sobre a técnica, a qualidade do software aumenta e o código fica mais fácil de entender. Assim, quando um desenvolvedor pega o código para adicionar uma nova funcionalidade e consegue compreendê-lo mais rapidamente, o processo de desenvolvimento também ocorre de maneira mais rápida e tranquila.

## Processo de Refatoração
Entender o código de outra pessoa não é uma tarefa trivial. Ainda mais quando é um software muito grande e complexo. Quando uma pessoa modifica um código que não é de sua autoria é possível que ela cometa alguns deslizes (métodos e variáveis mal nomeadas, duplicação de código, etc.) e com isso o código vai se tornando mais difícil de compreender.

Deste modo, após algum tempo, a inserção de novas funcionalidades se tornará uma tarefa mais complicada do que deveria, pois o desenvolvedor não conseguirá, ou terá muitas dificuldades em, entender exatamente o que código está fazendo.

Para evitar que o código fique complexo com o passar do tempo devido às atividades de manutenção e adição de novas funcionalidades, devemos refatorá-lo conforme as atualizações forem implementadas.

## Como refatorar?

O Ideal é tentar sempre tornar o código menos complexo possível, e ajustar o entendimento dele com o ambiente externo.

Pense sempre na entrada, processamento e saída para que você possa montar uma estrutura funcional e conseguir fazer as devidas alterações. 

Refatoração se implica em otimizar e melhorar um código fonte existente funcional, ou seja, um código que funcione corretamente.

# Vamos praticar!
## Revisão
- [Code Smells](https://github.com/reprograma/on28-ijs-codigolimpo1/blob/main/material/8.3%20-%20Code%20Smells.md)
- [Anti-patterns](https://github.com/reprograma/on28-ijs-codigolimpo1/blob/main/material/8.4%20-%20Anti-Patterns.md)
- [Boas práticas](https://github.com/reprograma/on28-ijs-codigolimpo1/blob/main/material/8.5%20-%20Boas%20Pr%C3%A1ticas.md)

## Parte 1
Vamos auxiliar na refatoração dos nossos códigos! Seremos divididas em trios ou quartetos e cada uma fará a revisão para a refatoração de 2 projetos.
- Leia todo o código do projeto;
- Tente entender o que está acontecendo;
- Escreva o que está acontecendo no código da maneira mais detalhada possível, como se fosse uma documentação (faça isso em um documento no Google Docs);
- A medida que você lê e cria a sua documentação, escreva comentários para que o código do projeto seja refatorado, seguindo as regras de Código Limpo.

Tenha em mente: o código precisa ser limpo, simples e legível. Releia os conceitos de código limpo e aplique-as nos projetos.

No fim desse processo, compartilhe as documentações que criou dos dois projetos que você leu.

```
Exemplo de informações que precisam estar na documentação

O objetivo geral do projeto é tal...
O projeto possui as classes X, Y e Z.

- Classe X:
  - É responsável por...
  - Recebe os atributos...
  - Possui os métodos A, B e C
    - O método A é responsável por...
    - O método A recebe os parâmetros ... e a saída é ...

- Como as classes se conversam entre si?
- Como o objetivo final do projeto é atingido?
- ...
```

Na medida que você tentar responder essas perguntas, você poderá ter dúvidas, e essas dúvidas provavelmente seriam respondidas por si só se o código tivesse escrito de uma maneira mais clara. A partir disso, faça suas sugestões de refatoração para que o código fique mais limpo, claro e legível.

## Parte 2
Hora de refatorar o nosso código!
- Leia o seu próprio código e os comentários realizados pelas revisoras na parte 1;
- Veja o que faz sentido e refatore seguindo as dicas recebidas;
- Leia as documentações que foram escritas pelas revisoras e veja se elas conseguiram compreender plenamente o seu código;
- Por fim, reveja se seu código ainda pode ser refatorado em mais algum lugar.


### Contatos

- [LinkedIn da prô](https://www.linkedin.com/in/luarakerlen/)
- [Github da prô](https://github.com/luarakerlen)
- [Instagram da prô](https://www.instagram.com/luaratech/)

<p align="center">
Desenvolvido com :purple_heart:  
</p>
