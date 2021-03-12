# create-html-node
Create a HTML element
## Install
$ npm install create-html-element
## Usage
```javascript
import createELem from './create-html-node'
const div = createELem(parentElem, 'div', 'class:superClass', 'id:superId', 'Some interesting text');
//=> '<div class="superClass" id="superId">Some interesting text</div>'
```
## License
MIT ©