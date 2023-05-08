/*1 – Selecionar todas as tuplas da relação conta cujo saldo é maior que 900. */
/* σ saldo > 900 (Conta)
/*2 – Selecionar todas as tuplas da relação conta cujo nome da agência é “Blumenau” possua saldo menor que 800. */
/* σ saldo < 800 ∧ Nome_Agencia = 'Blumenau' (Conta)

/* Selecionar o numero da conta de todas as tuplas da relação conta cujo nome da agência é “Blumenau” possua saldo menor que 800. */
/*Exemplo:*/
π Numero_Conta (σ saldo < 800 ∧ Nome_Agencia = 'Blumenau' (Conta))
