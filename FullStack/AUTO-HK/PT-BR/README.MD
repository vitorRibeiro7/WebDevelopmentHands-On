<div>

<h2>Missão backend</h2>

Desenvolver uma **API RESTful** com **Node** utilizando **Prisma**, que utilize todos os métodos <br> (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`).
### Especificação

Monte uma base de veículo com a seguinte estrutura:

```
veiculo:   string
marca:     string
ano:       integer
descricao: text
vendido:   bool
created:   datetime
updated:   datetime
```

Utilize **MySQL** ou **SQLite** para armazenar os dados que a **API** irá consumir.

### API endpoints
- `GET /veiculos`: Retorna todos os veículos
- `GET /veiculos/find`: Retorna os veículos de acordo com o termo passado parâmetro `q`
- `GET /veiculos/{id}`: Retorna os detalhes do veículo
- `POST /veiculos`: Adiciona um novo veículo
- `PUT /veiculos/{id}`: Atualiza os dados de um veículo
- `PATCH /veiculos/{id}`: Atualiza apenas alguns dados do veículo
- `DELETE /veiculos/{id}`: Apaga o veículo

</div>

---
<br>

<h2>Missão frontend <h2>

<p>Desenvolver uma **UI (User Interface)** de acordo com o protótipo.</p>

### Especificação
- Consumir a **API** criada acima
- Criar uma tela que tenha...
    - Listagem de veículos
    - Detalhe do veículo
    - Busca
    - Formulário de novo/edição de veículos