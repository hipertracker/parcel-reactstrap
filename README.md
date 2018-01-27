This repo shows the error in Parcel JS

```
$ parcel index.html
Server running at http://localhost:1234
🚨  /Users/hipertracker/github.com/hipertracker/parcel-reactstrap/node_modules/reactstrap-tether/dist/js/tether.js:549:21: Cannot resolve dependency './utils' at '/Users/hipertracker/github.com/hipertracker/parcel-reactstrap/node_modules/reactstrap-tether  547 | function _inherits(subClass, superClass) { if (typeof superClass !== 'function' && superClass !== null) { throw new TypeError('Super expression must either be null or a function, not ' + typeof superClass); } subClass.prototype = Object.create(superClass && superClass.prototype, { constructor: { value: subClass, enumerable: false, writable: true, configurable: true } }); if (superClass) Object.setPrototypeOf ? Object.setPrototypeOf(subClass, superClass) : subClass.__proto__ = superClass; }
  548 |
> 549 | var _utils = require('./utils');
      |                      ^
  550 |
  551 | var _utils2 = _interopRequireDefault(_utils);
  552 |
  ```