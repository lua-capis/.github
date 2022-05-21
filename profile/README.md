# Lua C-APIs

<!-- ---------------------------------------------------------------------------------------- -->

C-APIs for native [Lua] module interoperation

[Lua]:      https://www.lua.org

<!-- ---------------------------------------------------------------------------------------- -->

### Carray C API

The [Carray C API] makes it possible to handle arrays of primitive numeric 
C data types in Lua script code and also in native C code for enhancing module 
interoperability and performance.

<!-- ---------------------------------------------------------------------------------------- -->

### Notify C API

The [Notify C API] can be used to get asynchronous notifications from native code running in 
other threads, e.g. a GUI thread may get a notification interrupting the event loop for 
processing result data from another thread.
 *  Lua objects implementing the Notify C API can receive asynchronous notifications.
 *  Native C code invoking the Notify C API can send asynchronous notifications from any thread.


<!-- ---------------------------------------------------------------------------------------- -->

### Receiver C API

The [Receiver C API] can be used to get asynchronous messages from native code running in 
other threads.
 * Lua objects implementing the Receiver C API can receive asynchronous messages.
 * Native C code invoking the Receiver C API can send asynchronous messages from any thread.
 
<!-- ---------------------------------------------------------------------------------------- -->

### Sender C API

The [Sender C API] can be used to send asynchronous messages to native code running in other 
threads.
 * Lua objects implementing the Sender C API can send asynchronous messages.
 * Native C code invoking the Sender C API can read the asynchronous messages from any thread.

<!-- ---------------------------------------------------------------------------------------- -->

[Carray C API]:   https://github.com/lua-capis/lua-carray-capi
[Notify C API]:   https://github.com/lua-capis/lua-notify-capi
[Receiver C API]: https://github.com/lua-capis/lua-receiver-capi
[Sender C API]:   https://github.com/lua-capis/lua-sender-capi

