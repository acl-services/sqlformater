
Performs formatting of basic SQL statements (DML + query).

Direct conversion in javascript of this hibernate java code from
http://grepcode.com/file/repo1.maven.org/maven2/org.hibernate/hibernate-core/4.3.6.Final/org/hibernate/engine/jdbc/internal/BasicFormatterImpl.java#BasicFormatterImpl

### Installation

```bash
$ npm install sqlformatter
```

###Examples

```js
var sqlformatter = require('sqlformatter')
var sql = "select * from dual";

console.log(sqlformatter.format(sql));
```
Output:
```
 select
     *
 from
     dual
```

###Tests

To run the test suite, first install the dependancies, then run npm test:
```bash
$ npm install
$ npm test
```
