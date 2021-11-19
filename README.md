# QA Interview Todo API

This api implement endpoints to manage todo items.
It uses rest and json

# Todo data schema
A todo item should have the following fields
```
id: number
text: string
done: boolean
```

# API

Get all todo items
```
GET /todos
```

Get a single todo item by its id
```
GET /todos/{id}
```

Create a new todo item
```
POST /todos 
{
    "text": string,
    "done": boolean
}
```

Update a todo item
```
PUT /todos/{id}
{
    "text": string,
    "done": boolean
}
```

Delete a todo item
```
DELETE /todos/{id}
```