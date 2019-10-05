
# Semana Omnisteck

## API Methods

GET, POST, PUT, DELETE

* req.query = Acessar query params (Para Filtros)

```bash
/users/?idade=25
```

* req.params = Acessar route params (Para Edição e Delete)

```bash
/users/1
```

* req.body = Acessar o corpo da requisição (Para Criação)

```bash
{
    "Idade" : 25
}
```

### Mongo DB Atlas

https://www.mongodb.com/cloud/atlas