# clean-architeture
clean architeture

Segregação e Imutabilidade
Segregar a aplicação ou os serviços nela contidos em componentes *mutáveis* & *imutavies*

- Componentes mutáveis relaizam suas tarefas de maneira puramente funcional, sem usar nenhuma variavel mutável. Os componenetes imutaveis se comunicam com um ou mais dos outros componentes que não são puramente funcionais, e eprmitem que o estado da variavel se altere.


# SOLID
Se os tijolos da construção não são bem feitos a arquitutura da construção perde o efeito, a importância.
Ainda assim é possível fazer uma bagunça com tijolos bem-feitos.

- Solid nos diz como organizar as funções e estruturas de dados em classese como as classes devem ser interconectadas.

Modulo: Um arquivo fonte.

srp - single responsability
Um módulo deve possuir um unico grupo de usuários. Um ator e deve mudar quando um grupo, ou ator exigir essa mudança. 
## Separar o código do qual diferentes atores dependem.
## separar o código que dá suporte a atores diferentes.

ocp - open/closed principle
Aberto para extensão. Fechado para modificação.
- As dependências transitivas violam o princípio geral de que as entidades de software não dependem de coisas que não usam diretamente.

-particionamos o sistema em componentes e organizamos esses componentes em uma hierarquia de dependência que proteja os componentes de nível mais alto das mudanças em componentes de nível mais baixo.

