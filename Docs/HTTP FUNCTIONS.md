## HTTP FUNCTIONS

# HTTP Request
```lua
<string> http(<table>)
```
This function is built in and will do requests to whatever website you want.
*DISCLAIMER
You can get IP logged or cookie logged
<br>
Example:
```lua
data = {
 Url : ''
 Method : 'Get'
 }
 R = http(data)
 console.log(R)
```
