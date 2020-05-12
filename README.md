# Trimacth

## Entidades
* Cliente
* Hospedagem
* Voo
* Pacote
* Reserva
* Venda
* Relatório

## Atributos

### Cliente
* CPF #
* Número *
* Email o
* Nome *
* Compras o

## Hospedagem
* UID #
* Tipo *
* Local *
* Extras (mudar nome) o
* Valor diária *

## Voo
* UID #
* Aviação (Chave e.?)
* Disponibilidade
* Assento
* Classe
* Tempo de voo
* Valor

## Pacote
* Estadia *
* Quantidade de pessoas *
* Alimentação *
* Disponibilidade *
* Valor total *
* Hospedagem (Chave e.) (NÃO COLOQUEI NA TABELA)
* Voo (Chave e.) (NÃO COLOQUEI NA TABELA)
* UID #
* Adicionais (passeios, etc..) (?) (NÃO COLOQUEI NA TABELA)

## Venda
* Cliente (Chave e.)
* Pacote (Chave e.)
* Valor
* Lucro (?)

| Cliente     | Hospedagem        | Voo               | Pacote            | Venda | Relatório | Reserva |
| *---------* | *---------------* | *---------------* | *---------------* | *---* | *-------* | *-----* |
| CPF #       | UID #             | UID #             | UID #             |       |           |         |
| Nome *      | Tipo *            | Aviação *         | Qtd. de pessoas * |       |           |         |
| Telefone *  | Local *           | Disponibilidade o | Alimentação o     |       |           |         |
| Email o     | Extra o           | Assento *         | Disponibilidade o |       |           |         |
| Compra o    | Valor diária *    | Classe *          | Valor total*      |       |           |         |
|             | Disponibilidade o | Tempo de voo *    |                   |       |           |         |
|             |                   | Valor *           |                   |       |           |         |
