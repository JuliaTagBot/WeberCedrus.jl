# WeberCedrus

This Julia package extends Weber, to enable the use of cedrus response-pad input. It adds a series of new keys, ranging from key":cedrus0:" to key":cedrus19:'. You can see which key is which by pressing the buttons while running the following code in julia.

```julia
using Weber
run_keycode_helper(extenstions=[CedrusXID()])
```

You can also query the precise time of button presses (relative to the start of a trial)
using the method `response_time`.
