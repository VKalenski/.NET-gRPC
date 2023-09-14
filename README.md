# gRPC-.NET-7


dotnet --version

dotnet new grpc -o ToDoGrpc --Framework net7.0

dotnet run

dotnet add package Microsoft.EntityFrameworkCore.Sqlite

dotnet add package Microsoft.EntityFrameworkCore.Design

dotnet add package grpc.tools

dotnet add package Microsoft.AspNetCore.Grpc.JsonTranscoding

dotnet-ef migrations add InitialMigration

dotnet-ef database update

Open with script:

select * from ToDoItems tdi -> Ctrl + Enter

---

### **Postman**

> **URL:**
```
localhost:7054
```

> **Greeter:**
```
SayHello
```

> **Message:**
```
{
    "name" : "Kalenski"
}
```

> **Response:**
```
{
    "message": "Hello Kalenski"
}
```
