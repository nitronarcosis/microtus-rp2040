#  What
Microtus is a miniature joystick/button/rotary encoder board designed to approximate the functionality of a traditional mouse. The idea was to create a small, independent board that would communicate with a keyboard over I^2^C. I designed two versions, one based on the RP2040 that should be able to run KMK or QMK (eventually), the other as a minimum viable product based on the ATtiny85 which was abandoned when I realized how backwards the chip market is and the much less capable ATtiny cost more than the RP2040.
#### Parts

 - 5-way analog joystick --- for 2d pointer control
 - low-profile Kailh Choc switches --- dedicated buttons for left/right click
 - 90°? Rotary encoder --- for scrolling
 - USB type C 2.0 --- for programming or independent use
 - JST SH 4-pin connector --- for connecting via I^2^C (ala Qwiic)

# Why

I build a cool new keyboard and wanted to see if I could design a "mouse" that was complementary.
#### Name
It's not a mouse but it's a genus of small-eared voles. It's related enough but not the same.

