API do Monde "beta"
===================

Seja bem-vindo a documentaço da API do Monde! Se você quer desenvolver alguma integração com o Monde, está no lugar certo. Nossa API é bem recente e ainda dá acesso a poucas partes do sistema, mas pretendemos ir expandindo ela priorizando a necessidade dos clientes.

Apesar da simplicidade atual da API, ela já é usada dentro da Monde por todos os nossos aplicativos, principalmente para iOS e Android, mas também por nosso aplicativo Windows, portanto fique tranquilo que a API é uma iniciativa bem séria pra gente e trabalhamos duro para mantê-la o mais estável possível.

Como ainda estamos em fase beta, a documentação está menos detalhada do que gostaríamos, portanto se tiver dúvidas ou precisar de qualquer ajuda, [crie uma issue](../../issues) aqui no próprio repositório que responderemos o mais breve possível.

Fazendo as requisições
----------------------

Endereço da API: https://web.monde.com.br/api

Deve ser adicionado o content type JSON ao Header da requisição:

```
Content-Type: application/json; charset=utf-8
```

## <code>V1</code>

### Formatos
- **[Pessoas](v1/full_format.md#pessoas)**
- **[Tarefas](v1/full_format.md#tarefas)**
- **[Históricos de tarefa](v1/full_format.md#histórico-de-tarefa)**
- **[Categorias de Tarefa](v1/full_format.md#categorias-de-tarefa)**

### Endpoints

#### Autenticação
- **[<code>POST</code> auth/auth_token](v1/authentication/POST_auth_token.md)**

#### Pessoas
- **[<code>GET</code> people](v1/people/GET_people.md)**
- **[<code>GET</code> people/:id](v1/people/GET_people_show.md)**
- **[<code>POST</code> people](v1/people/POST_people.md)**
- **[<code>PUT</code> people/:id](v1/people/PUT_people_edit.md)**
- **[<code>DELETE</code> people/:id](v1/people/DELETE_people.md)**


#### Tarefas
- **[<code>GET</code> tasks](v1/tasks/GET_tasks.md)**
- **[<code>GET</code> tasks/:id](v1/tasks/GET_tasks_show.md)**
- **[<code>POST</code> tasks](v1/tasks/POST_tasks.md)**
- **[<code>PUT</code> tasks/:id](v1/tasks/PUT_tasks_edit.md)**
- **[<code>DELETE</code> tasks/:id](v1/tasks/DELETE_tasks.md)**

#### Categorias de Tarefa
- **[<code>GET</code> task_categories](v1/task_categories/GET_task_categories.md)**

#### Vendas Importadas
- **[<code>GET</code> imported_sales](v1/imported_sales/GET_imported_sales.md)**
- **[<code>GET</code> imported_sales/:id](v1/imported_sales/GET_imported_sales_show.md)**
- **[<code>POST</code> imported_sales/refresh](v1/imported_sales/POST_imported_sales_refresh.md)**

#### Processos assíncronos
- **[<code>GET</code> async_process/:id](v1/async_process/GET_async_process_show.md)**

#### Arquivos
- **[<code>POST</code>file](v1/file/POST_file.md)**
- **[<code>GET</code>file](v1/file/GET_file.md)**
