# typescript

1. index.ts
```
   function sayhello(name: string){
    return "hello " + name;
}

var username = 'person'
document.body.innerHTML = sayhello(username);
```


1. type on cmd:   tsc index
2. type on cmd: touch index.html
3. index.html
```
   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TypeScript</title>
</head>
<body>
    <script src="index.js"></script>
</body>
</html>
```

# variable
1. let and var to declare varaible
   
# number
. let deciman: number = 6;
. let hex:  number = 0xf00d;
. let binary: number = 0b1010;
. let octal: number = 0o744;

# boolean
. let val:boolean = true;

# string
. let name:string = 'Alexis';
# string template
. let sentence:string = `My favorite restaurant is ${restaurant.name}`;

3 EXPRESSION
. ${price * quantity}

/Users/danny/SalesForce/typescript
