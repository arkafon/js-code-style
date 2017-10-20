# js-code-style
javascript style guide

## indentation

always 4 spaces

```javascript
// bad
{
  const name = 'John';
}

// good
{
    const name = 'John';
}
```

## variables

use const, sometimes let

```javascript  
// bad
var name = 'John';

// good
const name = 'John';

// good
let name;
name = 'John';
```

## alignment

no single const

```javascript  
// bad
const name = 'Jonh',
      age = 31;

// bad
const name = 'Jonh',
    age = 31;

// good
const name = 'Jonh';
const age = 31;
```

no values alignment

```javascript  
// bad
const superLongName = 'Jonh';
const age =           31;

// bad
const superLongName = 'Jonh';
const age           = 31;

// good
const superLongName = 'Jonh';
const age = 31;
```
