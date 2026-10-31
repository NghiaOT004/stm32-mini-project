
# STM32 Embedded Systems Mini Project

A hands-on embedded firmware project developed using STM32CubeIDE and STM32 HAL drivers.

The project demonstrates communication protocols, peripheral interfaces, and embedded data processing through progressive laboratory exercises.

## Hardware

- MCU: STM32F767ZI (NUCLEO-F767ZI)
- Development environment: STM32CubeIDE
- Framework: STM32 HAL
- Programming language: C

## Project Roadmap

| Stage | Description | Status |
|-------|-------------|--------|
| Lab 2 | USB CDC Communication | Completed |
| Lab 3 | SPI Flash W25Q16 | Planned |

## Lab 2 - USB CDC Communication

### Objective

Implement USB communication between an STM32 microcontroller and a PC using the USB CDC (Virtual COM Port) class.

### Features

- USB CDC device configuration
- Serial communication with a PC terminal
- Command reception and string processing
- LED control through received commands
- Command echo for terminal interaction

### Implementation

The firmware uses the STM32 USB Device Library and HAL drivers.

Main application files:

- `Core/Src/main.c`
- `USB_DEVICE/App/usbd_cdc_if.c`
- `USB_DEVICE/App/usb_device.c`

### Testing

- USB CDC device recognized by Windows
- Communication tested using a serial terminal
- Command reception and LED response verified

## Future Development

The project will be extended with:

- External SPI NOR Flash (W25Q16)
- Gyroscope sensor data acquisition
- LCD-based data visualization
- Persistent sensor data logging

## Development Tools

- STM32CubeIDE
- STM32CubeMX
- Git and GitHub

## Author

GitHub: [NghiaOT004](https://github.com/NghiaOT004)
