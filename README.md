Description
------------

An electronic speed control or ESC is an electronic circuit that controls and regulates the speed of an electric motor. It may also provide reversing of the motor and dynamic braking. Miniature electronic speed controls are used in electrically powered radio controlled models. Full-size electric vehicles also have systems to control the speed of their drive motors.

Here is a small ESC library for control brushless motor (BLDC).

Initialize and usage
--------------------

To initialize, you must use the `ESC_Init`.

You can get motor position use the `ESC_getEnginePosition`.

Custom variable type
--------------------

Library use `stdint.h` variable types.

```
#include <stdint.h>

// Signed custom variables types
typedef int8_t      s8;
typedef int16_t     s16;
typedef int32_t     s32;

// Unsigned custom variables types
typedef uint8_t     u8;
typedef uint16_t    u16;
typedef uint32_t    u32;
```
