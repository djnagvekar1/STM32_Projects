# Project3_Bluetooth_with_BlueNRG

## Description

This project demonstrates interfacing Bluetooth using the BlueNRG module onboard the STM32L4S5I-IOT01A Discovery Kit. The BlueNRG-MS M0A module communicates with the STM32 M4 cortex processor via the SPI3 interface.

The project is built using STM32CubeMX for configuration and STM32CubeIDE for development and compilation.

## Features

- Bluetooth Low Energy (BLE) communication using BlueNRG-MS
- SPI interface integration between STM32 and BlueNRG module
- Basic BLE setup and configuration

## Hardware Requirements

- STM32L4S5I-IOT01A Discovery Kit (includes BlueNRG-MS module)

## Software Requirements

- STM32CubeMX (for project configuration)
- STM32CubeIDE (for code development and building)
- Git (for cloning the repository)

## Setup Instructions

1. **Clone the Repository:**
   ```
   git clone https://github.com/dhirajnagvekar1/STM32_Projects.git  
   cd Project3_Bluetooth_with_BlueNRG
   ```

2. **Open in STM32CubeMX:**
   - Launch STM32CubeMX
   - Open the `Dhiraj_BlueNRG.ioc` file
   - Generate the code for your preferred IDE (STM32CubeIDE)

3. **Import into STM32CubeIDE:**
   - Open STM32CubeIDE
   - Import the project as an existing STM32CubeMX project
   - Select the generated code directory

4. **To read how I setup the cubeMX project (.ioc) refer this() file**


## Building the Project

1. In STM32CubeIDE, right-click on the project in the Project Explorer
2. Select "Build Project"
3. The build output will be in the `Debug` directory

## Flashing and Running

1. Connect the STM32L4S5I-IOT01A board to your computer via USB
2. In STM32CubeIDE, click the "Run" button or use "Run > Run"
3. Select the appropriate debug configuration
4. The program will be flashed to the board and executed

## Usage

- Once flashed, the board will initialize the BlueNRG module and set up BLE communication. Monitor the output via UART or use a BLE scanner app on your phone to detect the device.
- You can use the Ligthblue app or the nrfconnect app to subscribe to the data being sent.(You can read it by setting it to UTF-8 encoding)
-   
## Project Structure

- `Dhiraj_BlueNRG.ioc`: STM32CubeMX project configuration
- `Core/`: Main application code
  - `Inc/`: Header files
  - `Src/`: Source files
- `Drivers/`: STM32 HAL drivers and BSP
- `Middlewares/ST/BlueNRG-MS/`: BlueNRG middleware
- `Debug/`: Build artifacts and makefile

## Contributing

Feel free to submit issues and pull requests for improvements.

## License

This project is provided as-is for educational purposes.