# Software Debouncing
Buttons are faulty mechanical devices that can "bounce" when pressed. When the button bounces it turns on and off. To fix this problem a delay can be writtern in code to disable the button for a period of time, and then turn it on. 

When the button is pressed the an interrupt occurs. The interrupt disables the button interrupt and starts a timer for debounce. When the register reaches a value the timer interrupt stops clock. It then delays and enables the button interrupt.

Both codes are similar but just use different ports and bits. The interrupts are also labeled differently.
