# Zed Editor Snippets

This directory contains custom code snippets for Zed editor.

Type the prefix and press `Tab` to expand the snippet. Use `Tab` to navigate between placeholders.

---

## Go Snippets

File: `go.json`

### Package & Structure

#### `pkgm` - Package main with main function

```go
package main

func main() {

}
```

#### `ffn` - Function definition

```go
func name(params) error {

}
```

#### `meth` - Method definition

```go
func (receiver Type) name(params) error {

}
```

#### `st` - Struct definition

```go
type Name struct {
    Field Type
}
```

#### `int` - Interface definition

```go
type Name interface {
    Method(params) returns
}
```

### Control Flow

#### `iff` - If statement

```go
if condition {

}
```

#### `ife` - If-Else statement

```go
if condition {

} else {

}
```

#### `switch` - Switch statement

```go
switch expression {
case value:

default:

}
```

#### `select` - Select statement for channels

```go
select {
case v := <-channel:

default:

}
```

### Loops

#### `for` - Traditional for loop

```go
for i := 0; i < count; i++ {

}
```

#### `forr` - For range loop (index and value)

```go
for index, value := range collection {

}
```

#### `forrv` - For range loop (value only)

```go
for _, value := range collection {

}
```

#### `forri` - For range loop (index only)

```go
for index := range collection {

}
```

#### `whi` - While-style loop

```go
for condition {

}
```

#### `fori` - Infinite loop

```go
for {

}
```

### Error Handling

#### `iferr` - If err != nil check

```go
if err != nil {

}
```

#### `ifer` - If err != nil with return

```go
if err != nil {
    return err
}
```

#### `err` - Create error with errors.New()

```go
errors.New("error message")
```

#### `errf` - Create formatted error with fmt.Errorf()

```go
fmt.Errorf("error message: %w", err)
```

### JSON Operations

#### `jsonm` - JSON Marshal with error check

```go
data, err := json.Marshal(value)
if err != nil {

}
```

#### `jsonu` - JSON Unmarshal with error check

```go
var data Type
err := json.Unmarshal(bytes, &data)
if err != nil {

}
```

---

## TypeScript Snippets

Files: `typescript.json`, `tsx.json`

### Classes & Objects

#### `class` - Class definition

```typescript
class name {
    constructor(parameters) {

    }
}
```

#### `ctor` - Constructor with super()

```typescript
/**
 *
 */
constructor() {
    super();

}
```

#### `method` - Method definition

```typescript
/**
 *
 */
name() {

}
```

#### `public method` - Public method with JSDoc

```typescript
/**
 * name
 */
public name() {

}
```

#### `private method` - Private method definition

```typescript
private name() {

}
```

### Properties

#### `get` - Property getter with type

```typescript
public get value() : string {
    return
}
```

#### `set` - Property setter with type

```typescript
public set value(v : string) {
    this. = v;
}
```

#### `prop` - Full property with getter and setter

```typescript
private _value : string;
public get value() : string {
    return this._value;
}
public set value(v : string) {
    this._value = v;
}
```

### Modules & Imports

#### `import` - Import statement

```typescript
import {  } from "module";
```

#### `ref` - Triple-slash reference

```typescript
/// <reference path="" />
```

### Console

#### `log` - console.log()

```typescript
console.log();
```

#### `warn` - console.warn()

```typescript
console.warn();
```

#### `error` - console.error()

```typescript
console.error();
```

### Control Flow

#### `iff` - If statement

```typescript
if (condition) {

}
```

#### `ife` - If-Else statement

```typescript
if (condition) {

} else {

}
```

#### `switch` - Switch statement

```typescript
switch (key) {
    case value:

        break;

    default:
        break;
}
```

#### `trc` - Try-Catch statement

```typescript
try {

} catch (error) {

}
```

### Loops

#### `fih` - For-In loop with hasOwn check

```typescript
for (const key in object) {
    if (!Object.hasOwn(object, key)) continue;
    const element = object[key];

}
```

#### `fof` - For-Of loop

```typescript
for (const element of object) {

}
```

#### `fao` - For-Await-Of loop

```typescript
for await (const element of object) {

}
```

#### `whi` - While loop

```typescript
while (condition) {

}
```

#### `dwh` - Do-While loop

```typescript
do {

} while (condition);
```

### Async & Promises

#### `newpromise` - Create new Promise

```typescript
new Promise((resolve, reject) => {

})
```

### Other

#### `ffn` - Function statement

```typescript
function name(params) {

}
```

#### `new` - New instance statement

```typescript
const name = new type(arguments);
```

#### `throw` - Throw exception

```typescript
throw new Error("");
```
