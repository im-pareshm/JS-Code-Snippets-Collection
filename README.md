# JS-Code-Snippets-Collection
> Click :star:  if you like the project. Pull Request are highly appreciated.

### Table of Contents
| No. | Title |
|---- | ---------
|1  | [Checking if a Variable has a Valid Value](#Checking-if-variable-has-valid-value) |
|2  | [Unique Objects from Array of Objects](#Unique-Objects-from-Array-of-Objects) |
|3  | [Unique Value from Array of Objects](#Unique-Value-from-Array-of-Objects) |






### Checking if variable has valid value **[⬆ Back to Top](#table-of-contents)**
```javascript
// This code snippet is used to check if a variable has a valid value 

if(Boolean(a)){
    // this code will be executed if a is not a falsy value
    console.log('a has a valid value a: ' + a )
}else{
    // this code will be executed if a has a falsy value like null, undefined, empty string("")
    console.log('a has a invalid value a: ' + a )
}
```

### Unique Objects from Array of Objects **[⬆ Back to Top](#table-of-contents)**
```javascript
// This code will get you unique object from array of objects by a perticular key

[...new Map(array.map(item => [item[Key], item])).values()]

```

### Unique Value from Array of Objects **[⬆ Back to Top](#table-of-contents)**
```javascript
// This code will get you unique value from array of objects by a perticular key

[...new Set(data.map(item => item.group))]
