# Trabalho JSON
## Giovani Garcia Abel R.A.: 7122

JSON, é um formato de texto utilizado para transações de dados, sua sigla significa JavaSript Object Notation e é um subset da linguagem JavaScript. Possui duas estruturas, a primeira, comumente chamada de JSON Object, é uma coleção de pares compostas por chave e valor, sendo sua chave um texto e seu valor um dos seguintes tipos:

Tipo | Valor
-----|------
objeto | { "profissao" : "professor"}
vetor | [1, 2, 3.14, 42]
texto | "Fábio é legal"
numerico | 42
booleano | true
nulo | null

E a segunda uma lista ordenada de valores, comumente chamada de JSON Array.
```javascript
[ "valor1", "valor42", "pamonha" ]
```

Um objeto JSON devidamente estruturado pode ser representado da seguinte maneira:
```javascript
{
    "nome": "Um nome qualquer",
    "idade": 25,
    "objeto": {
                "booleano": true
    },
    lista: [
        "pamonha",
        "abacate",
        "limão"
    ],
    "nada": null
}
```

# Exemplo Prático - Pizzaria
Este é um exemplo prático de uma utilização da estrutura JSON para o cadastro de pizzas, garçons e pedidos.
## Cadastro de Pizzas
### Pizza de Calabresa
```javascript
{
    "nome": "calabresa",
    "ingredientes": ["massa", "cebola", "calabresa", "mussarela"],
    "valor": 18.90
}
```
### Pizza Portuguesa
```javascript
{
    "nome": "portuguesa",
    "ingredientes": ["massa", "cebola", "tomate", "ovo", "mussarela"],
    "valor": 20.90
}
```
### Pizza de Atum
```javascript
{
    "nome": "atum",
    "ingredientes": ["massa", "atum", "tomate", "azeitona", "mussarela"],
    "valor": 19.90
}
```
