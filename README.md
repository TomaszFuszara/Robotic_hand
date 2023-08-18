# Robotic_hand

Robotic hand is project based on the STM32 platform. It consists of communicating two microprocessors with each other through two hc-05 bluetooth modules. One microcontroller receives data about the bias of the potentiometers connected to the ADC and through the USART sends the data to the bluetooth module. The other microcontroller receives via USART the data from the bluetooth module and generates the appropriate PWM signal using timer to control the servomotors of the robotic arm.
