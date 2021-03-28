# Nald
Nald is a programming language, created with Python

## RUN
Open your terminal.
```
$ nald
$ =] run("{filename}.nald")
```

## VARIABLE
```
loc a = 0
loc b = a
loc c = "String"
loc d = true
loc e = false
```

## PRINT
```
out("Hello, world!")
out(1 + 2)
out(a)
```

## IF...ELSE
```
if a == b do out("a = b") elif a == 2 do out("M") else out("N")

if a == 1 do
  out("Y")
elif a == 2 do
  out("M")
else
  out("N")
end
```

## FUNCTION
```
func add(a, b) -> out(a + b)

func add(a, b)
  out(a + b)
end

add(4 + 2)
```

## FOR LOOP
```
for i = 0 to 10 do out(i)

for i = 0 to 10 do
  out(i)
end
```

## WHILE LOOP
```
while false do out("false")

while true do
  out("true")
end
```
