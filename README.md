# JS-Code-Snippets-Collection
> Click :star:  if you like the project. Pull Request are highly appreciated.

### Table of Contents
| No. | Questions |
|---- | ---------
|1  | [Checking if a Variable has a Valid Value](#Checking-if-variable-has-valid-value) |



**[⬆ Back to Top](#table-of-contents)**
### Checking-if-variable-has-valid-value
```javascript
// This code snippet is used to check if a variable has a valid value 

if(Boolean(a)){
    // this code will be executed if a is not a falsy value
    console.log('a has a valid value a: ' + a )
}else{
    // this code will be executed if a has a falsy value like null, undefined, empty string("")
    console.log('a has a invalid value a: ' + a )
}
