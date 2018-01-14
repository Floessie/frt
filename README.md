## frt – Flössie's ready (FreeRTOS) threading – Just add hardware

frt is an object-oriented wrapper around FreeRTOS tasks, queues, mutexes, and semaphores. It provides the basic tools for a clean multithreading approach based on the [Arduino_FreeRTOS_Library](https://github.com/feilipu/Arduino_FreeRTOS_Library) with focus on static allocation, so you know your SRAM demands at compile time.

This will compile just fine with the stock [Arduino_FreeRTOS_Library](https://github.com/feilipu/Arduino_FreeRTOS_Library), but if you want the advantages of static allocation you are welcome to try my [`minimal-static` branch](https://github.com/Floessie/Arduino_FreeRTOS_Library/tree/minimal-static) with frt.

** This is work in progress, so take it with a grain of salt...**

### Examples

There's a single example called `Blink_AnalogRead.ino` for now. `frt.h` itself isn't that big and magical as well, so take it as a reference until I've spent some more time on documentation.
