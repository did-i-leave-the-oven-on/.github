```lua
local function HelloWorld(text)
  local hello = string.gsub(text, text, "fuck you")
  local world = game

  print(hello)
  world:Destroy()
end

HelloWorld("print")
```
<img width="1058" height="300" src="https://github.com/user-attachments/assets/8f56f0fc-bcfe-4e79-8972-cdc7317d959a" />
