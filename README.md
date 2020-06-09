# Trimacth

## Entidades
* Cliente
* Hospedagem
* Voo
* Pacote
* Reserva
* Venda
* Relatório
* Parceiros (??)

## Atributos

### Cliente
* CPF #
* Número *
* Email o
* Nome *
* Sobrenome *
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
* Valor total *
* Forma de pagamento *
* Parcelas o
* Código da compra #

## Parceiros
* Empresa
* Tipo (Aviação, hotel, turismo..)
* Local
* Disponibilidade (SE ESSA ENTIDADE EXISTIR TEM Q TIRAR O ATRIBUTO DISPONIBILIDADE DAS OUTRAS ENTIDADES)

---


| Cliente     | Hospedagem        | Voo               | Pacote            | Venda             | Relatório | Reserva |
| :---------: | :---------------: | :---------------: | :---------------: | :---------------: | :-------: | :-----: |
| CPF #       | UID #             | UID #             | UID #             | Código compra #   |           |         |
| Nome *      | Tipo *            | Aviação *         | Qtd. de pessoas * | Forma pagamento * |           |         |
| Telefone *  | Local *           | Disponibilidade o | Alimentação o     | Parcelas o        |           |         |
| Email o     | Extra o           | Assento *         | Disponibilidade o | Valor total *     |           |         |
| Compra o    | Valor diária *    | Classe *          | Valor total*      |                   |           |         |
|             | Disponibilidade o | Tempo de voo *    |                   |                   |           |         |
|             |                   | Valor *           |                   |                   |           |         |
