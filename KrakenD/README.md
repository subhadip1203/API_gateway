### Krakend config file

1. create a file "krakend.json"
2. run command: `krakend run -c krakend.json `
3. check health : `localhost:8080/__health`



### json and array

for array return , we have to use :
```
"encoding":"json",
"is_collection":true 

```

for jsut JSON object 
```
"encoding":"json",

```


### matrix
check this api point : http://localhost:8090/__stats

