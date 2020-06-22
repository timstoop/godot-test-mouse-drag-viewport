# Mouse dragging the ViewPort/Camera

I'm trying to make it so I can get the effect from most RTS games, pressing the
left button on my mouse to "grab" the world and dragging the mouse to pan the
view. But it seems the Camera2D does not get sent any unhandled events? Did I
make a mistake?

## Solution

A ColorRect is a Control object as well, so we need to make sure it ignores
mouse events.
