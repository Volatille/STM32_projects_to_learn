#STM32 All my projects.
Here i uploaded my projects of STM32. From child level to senior embedded (dream, but i hope so)


## 1. Interpput Button to Power All Leds [04.04.2021] Learn time: ~ 3 hours.
First project, to power leds with HAL libary. First use interpput on button in STM32

### Description:
 Program use Hal library.
 Define 3 leds (define in code):
  - GREEN: Pin PC7
  - BLUE Pin PB7
  - RED Pin PB14

Button:
  - User button Pin PC13 

Interrput:
  - Mode: Rising / Falling
  - GPIO Pull-down
  - function interput: HAL_GPIO_EXTI_Callback
