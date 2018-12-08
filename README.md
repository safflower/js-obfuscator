# JS Obfuscator
Converts the JavaScript source code into obfuscated.

It uses only 10 different characters (`!+/()[]{},`) to write.

And it supports Chrome, IE and other some browsers.

However, this only works with the http and https protocols.

Because it use URL protocol as gadget.

## Code
``` python
code = 'alert("Hello, World!")'
code = obfuscate(code)
print(code)
```

## Result
``` javascript
[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[!![]+!![]]+([][[]]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(![]+[])[!![]+!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]])()([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]]+(![]+[])[!![]+!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]])()({})[+[]]+(!![]+!![]+!![]+!![]+!![]+[])+(!![]+!![]+!![]))+(!![]+[])[+[]]+(!![]+[])[+!![]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+([][[]]+[])[+!![]]+[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+(+(+!![]+(!![]+[])[!![]+!![]+!![]]+(+!![])+(+[])+(+[])+(+[]))+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]]+({}+[])[+!![]]+(![]+[])[+[]]+([]+[])[(![]+[])[+[]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(!![]+[])[+[]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+(!![]+[])[+!![]]]()[(+!![]+[])+(!![]+!![])]+([]+[])[(![]+[])[+[]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(!![]+[])[+[]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+(!![]+[])[+!![]]]()[(+!![]+[])+(!![]+!![])])()[!![]+!![]+!![]+!![]+!![]])()[(![]+[])[+[]]+(!![]+[])[+!![]]+({}+[])[+!![]]+[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+(+(+!![]+(!![]+[])[!![]+!![]+!![]]+(+!![])+(+[])+(+[])+(+[]))+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]]+({}+[])[+!![]]+(![]+[])[+[]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(+[]+[]))()[!![]+!![]]+[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]]+(![]+[])[!![]+!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]])()((+!![]+[])[(![]+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]]]())[!![]+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[+[]]+(![]+[])[+!![]]+(!![]+[])[+!![]]+[][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]]+(![]+[])[!![]+!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+([][(![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+!![]]][({}+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]]+(![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(!![]+[])[+[]]+({}+[])[+!![]]+(!![]+[])[+!![]]]((!![]+[])[+!![]]+(!![]+[])[!![]+!![]+!![]]+(!![]+[])[+[]]+(!![]+[])[!![]+!![]]+(!![]+[])[+!![]]+([][[]]+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]+!![]+!![]]+(![]+[])[!![]+!![]]+({}+[])[+!![]]+({}+[])[!![]+!![]+!![]+!![]+!![]]+(![]+[])[+!![]]+(!![]+[])[+[]]+([][[]]+[])[!![]+!![]+!![]+!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[+!![]])()+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]+!![]])()((+!![]+[])[(![]+[])[!![]+!![]+!![]]+(!![]+[])[!![]+!![]]+({}+[])[!![]+!![]]]())[!![]+!![]]+({}+[])[+!![]]+([][[]]+[])[!![]+!![]]+(!![]+[])[!![]+!![]+!![]]]((!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+[]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+[]+[])+(+!![]+[]),(+!![]+[])+(+!![]+[])+(!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+!![]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+[]),(!![]+!![]+!![]+!![]+[])+(+[]+[]),(!![]+!![]+!![]+[])+(!![]+!![]+!![]+!![]+[]),(!![]+!![]+!![]+!![]+!![]+!![]+!![]+[])+(!![]+!![]+[]),(+!![]+[])+(+[]+[])+(+!![]+[]),(+!![]+[])+(+[]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+[]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+!![]+[])+(+!![]+[]),(!![]+!![]+!![]+!![]+[])+(!![]+!![]+!![]+!![]+[]),(!![]+!![]+!![]+[])+(!![]+!![]+[]),(!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+!![]+[])+(+!![]+[]),(+!![]+[])+(+!![]+[])+(!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+[]+[])+(!![]+!![]+!![]+!![]+!![]+!![]+!![]+!![]+[]),(+!![]+[])+(+[]+[])+(+[]+[]),(!![]+!![]+!![]+[])+(!![]+!![]+!![]+[]),(!![]+!![]+!![]+[])+(!![]+!![]+!![]+!![]+[]),(!![]+!![]+!![]+!![]+[])+(+!![]+[])))()
```
