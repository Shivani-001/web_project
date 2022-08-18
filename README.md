# web_project
Web Project in NetBeans where our project is using or working on JsonPowerDB.

Benefits of using JsonPowerDB:

- Proprietary algorithm for High Performance CRUD operations. Multiple times faster than popular DBMS.
- Provides Serverless support for faster development
- A UI developer can develop complete dynamic application.
- DBMS with built in web / application server and embedded caching makes the performance lightning fast.
- Server side Native NoSQL - best query performance.
- In-built support to query on multiple JPDB databases.
- Multi-mode DBMS - Document DB, Key-Value DB, RDBMS support.
- Nimble, Simple to use, In Memory, Real-time DBMS.
- Schema free - easy to develop and maintain.
- Web-services API - Can be used with any programming language that has support for HTTP.

Release History:

- PUT REQUEST

{
    "token": "90937507|-31949291518302949|90942895",
    "cmd": "PUT",
    "dbName": "Employee",
    "rel": "Emp-Rel",
    "jsonStr": {
        "name": "Ishika",
        "email": "gishika221@gmail.com",
      "mobile":18032425069
    }
}


- GET REQUEST

{
    "token": "90937507|-31949291518302949|90942895",
    "cmd": "GET",
    "dbName": "Employee",
    "rel": "Emp-Rel",
    "jsonStr": {
        "name": "Ishika", 
    }
}


- To Remove Records

{
    "token": "90937507|-31949291518302949|90942895",
    "cmd": "REMOVE",
    "dbName": "Employee",
    "rel": "Emp-Rel",
      "record": 1,
      "record": 5,
   
}


- UPDATE REQUEST

{
    "token": "90937507|-31949291518302949|90942895",
    "cmd": "REMOVE",
    "dbName": "Employee",
    "rel": "Emp-Rel",
    "jsonStr": {
      "record": 1,
      "record": 2
    }
}






Sources : https://login2explore.com/jpdb/docs.html
