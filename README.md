# STM32-Servo-Motor
STM32 firmware examples for controlling servo motors with PWM and adjusting servo position.


# STM32 Servo Motor Control

A collection of STM32 firmware examples for controlling a servo motor using pulse-width modulation (PWM). An STM32 timer generates the PWM signal, and changing the pulse width commands a positional servo to move.

## Getting Started

1. Choose an example and check which STM32 board or microcontroller it targets.
2. Open the project in the development environment used for that example.
3. Connect the servo’s signal wire to the PWM output pin configured in the firmware.
4. Power the servo according to its specifications and connect the servo power supply ground to the STM32 ground.
5. Build and flash the firmware, then test the servo movement.

## Adjusting the Servo Position

Change the PWM pulse width in the example code to command a different position. Use the pulse-width range specified for your servo model.

## Adding an Example

For each new example, document the target STM32 board, timer and channel, PWM output pin, servo model, and expected movement.
