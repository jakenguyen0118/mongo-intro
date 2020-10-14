## A)

```
db.classroom.insert([
{
    "name": "Jake",
    "favoriteFood": "mac and cheese",
    "age": 26,
    "os": "mac",
    "hobbies": [
        "video games", "watch movies"
    ]
},
{
    "name": "Allisyn",
    "favoriteFood": "tacos",
    "age": 30,
    "os": "mac",
    "hobbies": [
        "yoga", "concerts"
    ]
},
{
    "name": "Gore",
    "favoriteFood": "tacos",
    "age": 31,
    "os": "windows",
    "hobbies": [
        "video games", "drinking wine"
    ]
},
{
    "name": "Sampreet",
    "favoriteFood": "pizza",
    "age": 30,
    "os": "windows",
    "hobbies": [
        "music", "dance", "reading", "watching movies", "yoga"
    ]
}
])
```

## B)

### 1)
```
db.classroom.find()
```

### 2)
```
db.classroom.find({name: "Jake"})
```

## C)

### 1)
```
db.instructor_list.insert([
{
    "name": "Joe"
},
{
    "name": "Alex"
},
{
    "name": "Kenneth"
},
{
    "name": "Nathaniel"
},
{
    "name": "Aegean"
}
])
```

### 2)
```
db.instructor_list.remove({name: "Nathaniel"})
```