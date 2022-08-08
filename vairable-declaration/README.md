# Go-Notes

### Variable declaration 

#### regular syntax
`var varialbeName variableType`

#### shorthand syntax - declare and initialize the variable
`variableName := initValue`

##### Type inferencing
if the variable is assigned to another type, it throws an error.
`a:= 1`
`a = "Hello" //error`

##### Declaring multiple variable
`variableName1, variableName2 := initValue1, initValue2`

##### Declaring functions
declare an anonymous function
`f := func(){
  fmt.Println("Hello World")
}`

##### Advantages of short declaration
Short and concise
Assign mutiple values at the same time - especially error handling 

##### Disadvantage of short declaration
It must be inside a function
