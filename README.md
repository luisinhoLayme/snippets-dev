# react-snippets-dev

This is for your extension "react-css-scss-snippets-dev". After writing up a brief description, we recommend including the following sections.

## Features

Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

\!\[feature X\]\(images/feature-x.png\)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Requirements

If you have any requirements or dependencies, add a section describing those and how to install and configure them.

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something

## React and Js

##### `clg` - log

```javascript
console.log(|)
```

##### `ti` - Etiqueta

```javascript
<Component />
```

##### `usedis` - useDispatch - redux

```javascript
const dispatch = useDispatch()
```

##### `usesel` - useSelector - redux

```javascript
const select = useSelector( state => state )
```

##### `ims` - Import styled-components

```javascript
import styled from 'styled-components'
```

##### `sc` - Export styled-components

```javascript
export const | = styled.|`
  |
`
```

##### `te` - Import Etiqueta

```javascript
<div
  |
>
  |
</div>
```

##### `scf` - component

```javascript
const Component = (|) => {
  return (
    |
  )
}

export default Component
```

##### `rcom` - Import React  Function Component

```javascript
import {} from 'react

const Component = (|) => {
  return (
    <div>
      |
    </div>
  )
}

export default Component
```

##### `fn` - Function Callback

```javascript
const | = (|) => {
  |
}
```

##### `ruse` - useState Hook

```javascript
const [ |, set| ] = useState(|)
```

##### `rusee` - useEffect Hook

```javascript
useEffect(() => {
	|
}, [])
```

##### `desct` - describe and test

```javascript
describe('|', () => {

  test('should |', () => {

    |

  })

})
```

##### `test` - test

```javascript
  test('should |', () => {

    |

  })
```

##### `imp` import module (ES6)

```javascript
import ${1:name} from '${2:module}'
```

##### `imn` import module (ES6)

```javascript
import '${1:module}'
```

##### `imd` import module (ES6)

```javascript
import { $2 } from '${1:module}'
```

##### `req` import module (ES6)

```javascript
const ${1:packageName} = require('${1:package}')
```

##### `env` import module (ES6)

```javascript
export const ${1:exportVariable} = ${2:localVariable}
```

##### `con` class constructor (ES6)

```javascript
constructor(${1:arguments}) {
  ${0}
}
```

##### `met` method (ES6 syntax)

```javascript
${1:method}(${2:arguments}) {
  ${0}
}
```

##### `get` getter (ES6 syntax)

```javascript
get ${1:property}() {
  ${0}
}
```

##### `set` setter (ES6 syntax)

```javascript
set ${1:property}(${2:value}) {
  ${0}
}
```

##### `foreach` forEach loop

```javascript
${1}.forEach((${2:item}) => {
  ${0}
})
```

##### `forof` for of loop (ES6)

```javascript
for (let ${1:key} of ${2:array}) {
  ${0}
}
```

##### `forin` for in loop

```javascript
for (let ${1:key} in ${2:array}) {
  if (${2:array}.hasOwnProperty(${1:key})) {
    ${0}
  }
}
```

##### `dco` destructuring const assignment

```javascript
const {${2:name}} = ${1:value}
```

##### `dar` destructuring const assignment

```javascript
const [${2:name}] = ${1:value}
```

##### `setinterval` setInterval

```javascript
setInterval(() => {
  ${0}
}, ${1:delay})
```

##### `settimeout` setTimeout

```javascript
setTimeout(() => {
  ${0}
}, ${1:delay})
```

##### `rprom` return Promise (ES6)

```javascript
return new Promise((resolve, reject) => {
  ${0}
})
```

##### `cll` console.log (labeled)

```javascript
console.log('${0}', ${0})
```

##### `clt` console.log (labeled)

```javascript
console.table(${1:object})
```

##### `forl` for loop

```javascript
for (let ${1:i} = 0, ${2:len} = ${3:iterable}.length; ${1:i} < ${2:len}; ${1:i}++) {
  ${0}
}
```

##### `if` if statement

```javascript
if (${1:condition}) {
  ${0}
}
```

##### `el` else statement

```javascript
else {
  ${0}
}
```

##### `ife` if/else statement

```javascript
if (${1:condition}) {
  ${0}
} else {

}
```

##### `ei` else if statement

```javascript
else if (${1:condition}) {
  ${0}
}
```

##### `while` while loop

```javascript
while (${1:condition}) {
  ${0}
}
```

##### `trycatch` try/catch

```javascript
try {
  ${0}
} catch (${1:err}) {

}
```

##### `switch` switch case

```javascript
switch (${1:expr}) {
  case ${2:value}:
    return $0
  default:
    return
}
```

##### `iife` immediately-invoked function expression (IIFE)

```javascript
((${1:arguments}) => {
  ${0}
})(${2})
```

##### `map` map

```javascript
${1}.map((${2:item}) => {
  ${0}
})
```

##### `filter` filter

```javascript
${1}.filter(${2:item} => {
  ${0}
})
```

##### `find` find

```javascript
${1}.find(${2:item} => {
  ${0}
})
```

##### `class` class (ES6)

```javascript
class ${1:name} {
  constructor(${2:arguments}) {
    ${0}
  }
}
```




## css

##### `mq` - Media Query

```css
  @media (min-width: |) {
    |
  }
```

## scss

##### `imv` - Variables

```scss
  @use '|' as v;
```

##### `imm` - Mixins

```scss
  @use '|' as m;
```

##### `mq` - Media Query in mixin

```scss
  @include m.| {
    |
  }
```

##### `in` - import mixin

```scss
  @include m.|
```


##### 1.1.0


-----------------------------------------------------------------------------------------------------------

**Enjoy!**
