# CRUD de Pessoas

## SOBRE A APLICAÇÃO :

É uma aplicação de CRUD básico que consiste em manipular dados no banco através da entidade Pessoa.

## FUNCÕES :

- Encontra uma pessoa registrada no sistema por ID.
- Encontra uma lista de pessoas registradas no sistema.
- Registra uma pessoa no sistema.
- Atualiza dados de uma pessoa do sistema.
- Deleta uma pessoa do sistema.

## VERSÃO :

Versão do Java: 17

Versão do Spring Boot: 3.0.2

## FERRAMENTAS :

Back end:

      - Java
      - Spring Data JPA
      - Maven

Dependências:

     Data JPA
     PostgreSQL 
     LomBok

- Schema :

<img src="https://user-images.githubusercontent.com/85299065/218934839-23a71182-808e-471b-8314-878347971218.PNG" width="60%" height="60%">

## Endpoints :

### Consultar pessoas
- **Endpoint**: `/person`
- **Método**: GET

### Consultar pessoa
- **Endpoint**: `/person/{id}`
- **Método**: GET


### Criar pessoa
- **Endpoint**: `/person`
- **Método**: POST
- **Entrada**: JSON contendo name, cpf e age
- **Exemplo**: {
    "name": "Gustavo",
    "cpf": "123456789"
    "age": 21
}

### Editar pessoa
- **Endpoint**: `/person/{id}`
- **Método**: PUT
- **Entrada**: JSON contendo o valor a ser alterado
- **Exemplo**: {
    "name": "Gustavo",
    "cpf": "123456789"
    "age": 21
}

### Deletar pessoa
- **Endpoint**: `/person/{id}`
- **Método**: DELETE
}
