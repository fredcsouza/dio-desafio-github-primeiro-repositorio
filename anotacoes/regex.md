<h1 align="center">RegEx</h1>

## Metodos

```
regex.test(/*../) - retorna um boolean.

regex.exec(/*../) - retorna um array com os resultados.
```

---

## Caracteres

```
\ - Escapa caracteres especiais.

^ - Inicia com determinado caractere.

$ - Finaliza com um determinado caractere.
```

---

## Grupos de caracteres

```
[abc] - Aceita qualquer caractere dentro do grupo

[^abc] - Não aceita qualquer caractere dentro do grupo

[0-9] - Aceita qualquer caractere entre 0 e 9

[^0-9] - Não aceita qualquer caractere entre 0 e 9

[a-zA-Z] - Aceita qualquer caractere entre "a" e "z" maiusculo e minusculo
```

---

## Quantificadores

```
{n} - Quantifica um número específico.

{n,} - Quantifica um número mínimo.

{n,m} - Quantifica um número mínimo e um número máximo.

? - Zero ou um.

* - Zero ou mais.

+ - Um mou mais.
```

---

## Metacaracteres

```
\w - Representa o conjunto [a-zA-Z_]

\W - Representa o conjunto [^a-zA-Z_]

\d - Representa o conjunto [0-9]

\D - Representa o conjunto [^0-9]

\s - Representa um espaço em branco

\S - Representa um não espaço em branco

\n - Representa uma quebra de linha

\t - Representa um tab
```

---

## Grupos de captura

```
( ) - Determina um grupo de captura para realizar a extração de valores de uma determinada String.
```

---