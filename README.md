# Postman_HW_1

## :small_blue_diamond:HW during Vadim Ksendzov course:small_blue_diamond:

Создать запросы в Postman.
<br>
<br>Protocol: http
<br>IP: 162.55.220.72
<br>Port: 5005

1. 
- Method: GET
- EndPoint: /get_method
- Request url params: 
  <br>&nbsp;&nbsp;name: str
  <br>&nbsp;&nbsp;age: int
```
http://162.55.220.72:5005/get_method?name=Olga&age=60
```
2. 
- Method: POST
- EndPoint: /user_info_3
- Request form-data: 
  <br>&nbsp;&nbsp;name: str
  <br>&nbsp;&nbsp;age: int
  <br>&nbsp;&nbsp;salary: int
```
http://162.55.220.72:5005/user_info_3

Body form-data:
name: Olga
age: 50
salary: 60000
```

3. 
- Method: GET
- EndPoint: /object_info_1
- Request url params: 
  <br>&nbsp;&nbsp;name: str
  <br>&nbsp;&nbsp;age: int
  <br>&nbsp;&nbsp;weight: int
```
http://162.55.220.72:5005/object_info_1?name=Olga&age=60&weight=70
```

4. 
- Method: GET
- EndPoint: /object_info_2
- Request url params: 
  <br>&nbsp;&nbsp;name: str
  <br>&nbsp;&nbsp;age: int
  <br>&nbsp;&nbsp;salary: int
```
http://162.55.220.72:5005/object_info_2?name=Olga&age=60&salary=60000
```

5. 
- Method: GET
- EndPoint: /object_info_3
- Request url params: 
  <br>&nbsp;&nbsp;name: str
  <br>&nbsp;&nbsp;age: int
  <br>&nbsp;&nbsp;salary: int
```
http://162.55.220.72:5005/object_info_3?name=Olga&age=60&salary=70000
```

6. 
- Method: GET
- EndPoint: /object_info_4
- Request url params: 
  <br>&nbsp;&nbsp;name: str
  <br>&nbsp;&nbsp;age: int
  <br>&nbsp;&nbsp;salary: int
```
http://162.55.220.72:5005/object_info_4?name=Peter&age=34&salary=67000
```

7. 
- Method: POST
- EndPoint: /user_info_2
- Request form data: 
  <br>&nbsp;&nbsp;name: str
  <br>&nbsp;&nbsp;age: int
  <br>&nbsp;&nbsp;salary: int
```
http://162.55.220.72:5005/user_info_2

Body form-data:
name: Olga
age: 50
salary: 60000
```
