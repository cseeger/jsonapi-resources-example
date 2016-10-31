Exploratory Todos implementation using `jsonapi-resources` gem.

* POST new Todo

```
curl -X POST -H "Content-Type: application/vnd.api+json" -H "Accept: application/vnd.api+json" -H "Cache-Control: no-cache" -H "Postman-Token: 0d293e98-c576-241a-8a78-a4fd666a3d8d" -d '{
  "data": {
    "type": "todos",
    "attributes": {
      "title": "Sample title",
      "description": "Sample description"
    }
  }
}' "http://localhost:3000/todos/"
```

* GET all Todos

```
curl -X GET -H "Content-Type: application/vnd.api+json" -H "Accept: application/vnd.api+json" -H "Cache-Control: no-cache" -H "Postman-Token: b4264320-c376-a79c-3826-c5df7debfa1a" "http://localhost:3000/todos/"
```
