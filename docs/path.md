# path

执行下面的代码，获取指定的文件名。

```javascript
const path = require('path');
console.log(path.basename('/foo/bar/baz.txt'));
```

执行下面的代码，获取指定的目录名。

```javascript
const path = require('path');
console.log(path.dirname('/foo/bar/baz.txt'));
```

执行下面的代码，获取指定文件的扩展名。

```javascript
const path = require('path');
console.log(path.extname('/foo/bar/baz.txt'));
```

执行下面的代码，拼接路径。

```javascript
const path = require('path');
console.log(path.join('/foo', 'bar/baz', 'qux'));
```

执行下面的代码，将指定的路径解析为绝对路径。

```javascript
const path = require('path');
console.log(path.resolve(__dirname));
console.log(path.resolve('/foo/bar', './baz', '../qux'));
```

执行下面的代码，规范化指定的路径。

```javascript
const path = require('path');
console.log(path.normalize(__dirname));
console.log(path.normalize('/foo/bar//baz/./qux/..'));
```

执行下面的代码，判断指定路径是否为绝对路径。

```javascript
const path = require('path');
console.log(path.isAbsolute('/foo/bar/baz'));
console.log(path.isAbsolute('foo/bar'));
```

执行下面的代码，获取从指定路径到另一个指定路径的相对路径。

```javascript
const path = require('path');
console.log(path.relative('/foo/bar/baz', '/foo/bar/qux'));
```

执行下面的代码，将指定路径解析为对象。

```javascript
const path = require('path');
console.log(path.parse('/foo/bar/baz/qux.txt'));
```

执行下面的代码，将指定对象格式化为路径。

```javascript
const path = require('path');
let obj = {
    root: '/',
    dir: '/foo/bar/baz',
    base: 'qux.txt',
    ext: '.txt',
    name: 'qux'
}
console.log(path.format(obj));
```

执行下面的代码，获取当前系统的路径分隔符。

```javascript
const path = require('path');
console.log(path.sep);
console.log(path.delimiter);
```
