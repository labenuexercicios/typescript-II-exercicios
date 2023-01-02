# Exercício 2
Agora podemos praticar a manipulação de arrays e objetos!<br>
No arquivo database.ts temos os mocks dos dados da aplicação, mas por enquanto eles estão totalmente inérteis e sem dinamicidade.<br>

## Funcionalidades
Desenvolva uma função para cada funcionalidade.

### User
- createUser (cria uma nova pessoa na lista de users)
    - input: três parâmetros (id, email e password)
    - output: frase de sucesso ("Cadastro realizado com sucesso")
    - exemplo de chamada:
        ```createUser("u003", "beltrano@email.com", "beltrano99")```
- getAllUsers (busca todas as pessoas da lista de users)
    - input: nenhum
    - output: lista atualizada de users
    - exemplo de chamada:
        ```getAllUsers()```

### Product
- createProduct (cria um novo produto na lista de products)
    - input: três parâmetros (id, name, price e category)
    - output: frase de sucesso ("Produto criado com sucesso")
    - exemplo de chamada:
        ```createUser("u003", "beltrano@email.com", "beltrano99")```
- getAllUsers (busca todas as pessoas da lista de users)
    - input: nenhum
    - output: lista atualizada de users
    - exemplo de chamada:
        ```getAllUsers()```
- queryProductsByName (busca por produtos baseado em um nome)
    - input: um parâmetro (query)
    - output: lista de produtos com nomes iguais ou parecidos
    - exemplo de chamada:
        ```queryProducts("monitor")```
