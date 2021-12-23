# Awesome Web Serial [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Awesome resources for serial communication using the browser. Includes these very awesome APIs: Web Serial, Web Bluetooth, Web USB, Web HID, Web MIDI, Sensor, and Gamepad.

## Contents

- [Code utilities](#code-utilities)
- [Documentation / Implementation / Tutorials](#documentation-implementation-tutorials)
- [Demos](#demos)
	- [Terminals](#terminals)
- [Compatible Devices](#compatible-devices)

## Code utilities

- [fromWebSerial](https://rxjs.ninja/modules/utility.html#fromwebserial) - RxJS Ninja utility function that returns the serial read data as an Observable, and can also receive an Observable to use as a write stream.

## Documentation / Implementation / Tutorials

- [MDN Official Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Web_Serial_API) - includes a deep dive into the API, example code, browser support, and other helpful links.
- [Google Codelab Getting Started with Web Serial](https://codelabs.developers.google.com/codelabs/web-serial#0) - Easy to follow starter project for use with the BBC micro:bit.

## Demos

- [Web Serial API Example Project](https://github.com/drohen/serial-web-test) - A slightly more advanced "hello world" with a [live demo](https://drohen.github.io/serial-web-test/) (requires a serial device running the project's micropython code). Utilises 2 variable resistor values controlling 2 Web Audio API oscillators.

### Terminals

- [Windows XP -inspired web serial controller](https://webserial.app/) - Fun demonstration of a serial communication tool that resembles the UI of the Windows XP desktop.

## Compatible Devices

- [BBC micro:bit](https://microbit.org/) - Educational microcontroller with tonnes of peripherals and lots of kid-friendly programming tools and projects, many based in the browser.
- [Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/) - ARM-based, cheap, microcontroller that can be programmed with Arduino C, Micropython, Circuitpython, and has serial available via its built-in USB port.
- [Arduino Uno](https://www.arduino.cc/en/Main/Products) - Entry-level microcontroller that can be used for web serial projects.