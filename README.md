# js-code-style
javascript style guide

## indentation

always 4 spaces

bad:
```javascript
{
  const foo = 'bar';
}
```

good:
```javascript
{
    const foo = 'bar';
}
```

## variables

use const, sometimes let

bad:
```javascript  
var foo = 'bar';
```

good:
```javascript
const foo = 'bar';
```

good:
```javascript
let foo;
foo = 'bar';
```

## alignment

no single const

bad:
```javascript  
const foo = 'bar',
      val = 123;
```

bad:
```javascript  
const foo = 'bar',
    val = 123;
```

good:
```javascript
const foo = 'bar';
const val = 123;
```

no values alignment

bad:
```javascript  
const foo = 'bar',
      val = 123;
```

bad:
```javascript  
const foo =                   'bar',
const superLongVariableName = 'Jonh';
```


```javascript  
const foo                   = 'bar',
const superLongVariableName = 'Jonh';
```

good:
```javascript
const foo = 'bar';
const superLongVariableName = 123;
```
