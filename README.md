Usage
==================================================
```js
var bf = new Blowfish({
	key: "some key",
	verification: "verify string"
});

var cipher_binary = bf.encrypt('some data');
var data = bf.decrypt( cipher_binary );

var cipher_base64text = bf.encrypt64('some data');
var data = bf.decrypt64( cipher_base64text );
```
