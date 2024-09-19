## Exercise 4.1
```bash
run (fromString "5+7");;
val it: int = 12
```

```bash
run (fromString "let y = 7 in y + 2 end");;
val it: int = 9
```

```bash
run (fromString "let f x = x + 7 in f 2 end");;
val it: int = 9
```
## Exercise 4.2
```bash
run (fromString "let sum x = if x=0 then 0 else x + sum(x-1) in sum 1000 end ");;
val it: int = 500500
```

```bash
run (fromString "let pow y = if y=1 then 3 else 3*pow(y-1) in pow 8 end");;
val it: int = 6561
```

```bash
run (fromString "let pow x = if x=0 then 1 else 3 * pow(x-1) in let sum n = if n=12 then 0 else sum(n+1) + pow(n) in
 sum 0 end end");;
val it: int = 265720
```
```bash
run (fromString "let pow x = x * x * x * x * x * x * x * x in let sum n = if n=1 then 1 else sum(n-1) + pow(n) in su
m 10 end end");;
val it: int = 167731333
```

## Exercise 4.3

## Exercise 4.4

## Exercise 4.5