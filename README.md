# LEDStatusAnimator

`LEDStatusAnimator` is an Arduino project designed for managing a status light using WS2811 LEDs. It offers smooth color transitions by setting start and end colors and has the ability to toggle between various color states. The `StatusLED` class allows for easy updates to the animations with a single call.

## Features

- Dynamic animations with smooth color transitions for WS2811 LEDs.
- Toggles between different color states every 10 seconds.
- Blinking effect when transitioning between states.
- Color conversion from HSV to RGB using the `ColorConverter` class.

## Usage

1. **Setup**: Define the number of LEDs and the pin you're using with the `LED_COUNT` and `LED_PIN` constants, respectively.
2. **Execution**: Upload the code to your Arduino board and watch the LEDs animate between the colors defined in `setColors`.
3. **Add More States**: Modify or add more states in the `setColors` function to include different color transitions.

## Dependencies

- [Adafruit_NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel) library.

## Files

- **Main File**: Contains the LED control logic and state transitions.
- **StatusLED.h**: Defines the `StatusLED` class for controlling and animating the WS2811 LEDs.
- **ColorConverter.h**: Provides tools for working with and converting colors in different formats, especially from HSV to RGB.

## Acknowledgements

This project has been made possible thanks to the libraries and tools provided by the Arduino community.
