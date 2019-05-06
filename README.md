# Display

A tile-based display intended for roguelikes. 

## Usage
```lua
local Display = require 'display'

function love.load()
   --Create display with size 20 x 20 and scale 1
   d = Display:new(20, 20, 1, {1, 0, 0}, {0, 0, 0})
   d:drawText(1, 1, 'Hello')
end

function love.draw()
   root:draw()
end
```