# API e Entity Framework .NET
www.dio.me

## Desafio de projeto 👨‍💻📝
Conclusão com sucesso do desafio de um sistema gerenciador de tarefas em .NET com API e Entity Framework!

## Contexto 📈❎🚫
O sistema oferece funcionalidades abrangentes de CRUD (Create, Read, Update, Delete) para tarefas, permitindo aos usuários:

- Criar novas tarefas: Inserir título, descrição, data e status para cada tarefa, definindo seus objetivos com clareza e precisão.
- Visualizar tarefas: Obter uma visão geral de todas as tarefas cadastradas, priorizando as mais importantes e acompanhando o progresso geral.
- Atualizar tarefas: Modificar as informações de tarefas existentes, ajustando prazos, prioridades ou qualquer outro detalhe relevante.
- Excluir tarefas: Eliminar tarefas concluídas ou irrelevantes, liberando espaço para novas conquistas.

Para garantir a confiabilidade do sistema, foram implementadas medidas de segurança e validação de dados:

- Validação de entrada: Assegurei que apenas informações válidas e consistentes sejam armazenadas, evitando erros e inconsistências.
- Proteção contra dados incorretos: Manter a integridade do banco de dados e a confiabilidade do sistema.

![Diagrama da classe Tarefa](diagrama.png)

Migração de banco de dados: Atualização automática do banco de dados para acompanhar as mudanças na sua aplicação

## Métodos esperados
Foram criados os seguintes métodos:


**Swagger**


![Métodos Swagger](swagger.png)


**Endpoints**


| Verbo  | Endpoint                | Parâmetro | Body          |
|--------|-------------------------|-----------|---------------|
| GET    | /Tarefa/{id}            | id        | N/A           |
| PUT    | /Tarefa/{id}            | id        | Schema Tarefa |
| DELETE | /Tarefa/{id}            | id        | N/A           |
| GET    | /Tarefa/ObterTodos      | N/A       | N/A           |
| GET    | /Tarefa/ObterPorTitulo  | titulo    | N/A           |
| GET    | /Tarefa/ObterPorData    | data      | N/A           |
| GET    | /Tarefa/ObterPorStatus  | status    | N/A           |
| POST   | /Tarefa                 | N/A       | Schema Tarefa |

Esse é o schema (model) de Tarefa, utilizado para passar para os métodos que exigirem

```json
{
  "id": 0,
  "titulo": "string",
  "descricao": "string",
  "data": "2022-06-08T01:31:07.056Z",
  "status": "Pendente"
}
```


## Recursos úteis 👍

- Repositório do desafio: [https://www.dio.me/]
- Documentação do Entity Framework: [https://learn.microsoft.com/en-us/ef/]
- Tutoriais sobre APIs REST: [https://www.freecodecamp.org/news/tag/rest-api/]

## Desafio Concluído com sucesso ✅

Continuarei explorando o mundo do desenvolvimento .NET e criando soluções ainda mais incríveis!
