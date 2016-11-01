# cefet-games-cauldron

Um caldeirão para se fazer poções mágicas incríveis.

## Composição da Cena

A cena é composta por dois modelos 3D chamados `fogueira.obj` e `caldeirao.obj`.
Uma fonte de luz foi colocada na cena e também foi configurada a luz ambiente
com intensidade de 40%.

![A cena final com o caldeirão, a fogueira e os efeitos de partículas](docs/cauldron.gif)

Deve haver dois efeitos de partículas na cena, sendo um para o fogo sob
o caldeirão e o outro para as borbolhas da sopa.

## Exercício

Ao fazer seu _fork_, clonar e executar a aplicação, a fogueira e o efeito de
partículas do fogo (`fogo.pfx`) já estão funcionando, mas o das
borbolhas (`bolhas.pfx`) não.

Este exercício é composto por 3 etapas:

1. Integrar o efeito de borbolha (que já está pronto, no
  arquivo `bolhas.pfx`) da sopa na aplicação
1. Estilizar o efeito do fogo para criar a poção mágica que você precisa:
  - Poção do amor: fogo vermelho, com movimentação selvagem, traz a pessoa
    amada em 5 dias
  - Poção da realeza: fogo amarelado, intensidade alta mas pouco movimento,
    torna-o rico no mesmo ano
  - Poção da nota alta em jogos: fogo esverdeado, movimentando-se em espiral,
    faz tirar nota bacana na melhor matéria do curso
  - Poção da moléstia: fogo acinzentado escuro, super intenso e movimentando
    apenas verticalmente, acomete a pessoa alvo com um resfriado leve
  - Poção da criatividade: de acordo com o alunoquimista
1. Estilizar a borbolha (quantidade de bolhas, frequência de surgimento, cor) e
  a sopa (textura `caldeirao-sopa.jpg`) com a cor da poção sendo criada
  - Só não vale a poção "de chocolate" padrão
