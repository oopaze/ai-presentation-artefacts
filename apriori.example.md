Dado uma lista de transações:

id da nota | items compradors |
|---|-------|
| 1 | Leite, Ovo, Piso |
| 2 | Leite, Queijo, Cebola |
| 3 | Ovo, Piso |
| 4 | Queijo, Cebola |
| 5 | Ovo, Leite, Piso, Queijo |
|---|----------|

Support(Leite) => {

    numero de transações que Leite aparece: 3
    numero total de transações: 5
    resultado: 3 / 5 => 0.6
}

Confidence(Leite -> Queijo) => {

    Support do Leite e Queijo juntos: 2 / 5 => 0.4
    Support do Leite: 3 / 5 => 0.6
    resultado: 0.4 / 0.6 => 0.67
}

Lift(Leite -> Queijo) => {

    Support de Leite e Queijo: 2 / 5 => 0.4
    Support do Leite: 3 / 5 => 0.6
    Support do Queijo: 3 / 5 => 0.6 

    resultado: 0.4 / (0.6 * 0.6) => 1.11
}

