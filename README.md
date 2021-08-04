# java-spring-boot
Java Spring Boot API

with CRUD function

##GET
```
/api/v1/student
```
__Response 200__
```
[
    {
        "id": 1,
        "name": "Mariam",
        "email": "mariam@gmail.com",
        "dob": "2000-01-05",
        "age": 21
    },
    {
        "id": 2,
        "name": "Alex",
        "email": "alex@gmail.com",
        "dob": "2011-01-05",
        "age": 10
    }
]
```

##GET BY ID
```
/api/v1/student/id
```
__Response 200__
```
    {
        "id": 1,
        "name": "Mariam",
        "email": "mariam@gmail.com",
        "dob": "2000-01-05",
        "age": 21
    }
```

##Post
```
/api/v1/student
```
__Request Body__
```
{
    "name":"Jonny",
    "email":"jonny@gmail.com",
    "dob":"2002-12-17"
}
```
##Put
```
/api/v1/student/id?name=soleh
```
##Delete
```
/api/v1/student/id
```