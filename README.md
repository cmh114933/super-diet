# super-diet

### GET /users

List all users, can be searched or sorted

**Query Params**

`name` - string, will fuzzy search using `LIKE '%name%'`

`age` - number, will match exactly

**Sample Response**

```
[
    {
        "id": 65,
        "name": "Ming Xiang",
        "age": 28
    }
]
```
---