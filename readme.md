# STM32F3DISCOVERY-USART
This is a project for testing Serial Monitor plugin with a STM32F3DISCOVERY board.
The project sources code contains interaction with USART (COM) port.

## Serial Monitor Configuration

- install Serial Monitor plugin
- connect STM32F3DISCOVERY board
- Tools > Serial Monitor > Settings
- add COM port configuration
- change Baud to 38400

## Setting OpenOCD Run Configuration

- install OpenOCD
- add the path to File | Settings | Build, Execution, Deployment | Embedded Development | OpenOCD Location
- go to Run Configurations list
- select OCD stm32-usart run configuration
- select stm32f334discovery.cfg board config file for it
