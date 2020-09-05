## HTTP FUNCTIONS

# Http Get
```lua
<string> httpGet(<string>)
```
This will get what's ever on the website you request a get from.
<br>
Example:
```lua
local Flyhacks = http.get('Mixon://Example.com/Flyhacks.mixon')
log(Flyhacks) -- Will return as 'Nah skid'
```

# Http Post
```lua
<void> httpPost(<string>,<table>)
```
This will post to the website you listed.
<br>
Example:
```lua
data = {blah, blah} -- If your researching this you prob know what to send same as other ones
httpPost(url,data)
```
