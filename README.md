# ESP32-FreeRTOS-Blinking-LED-with-Debug-Output
This project demonstrates basic multitasking on an ESP32 using FreeRTOS with the Arduino framework.
📝 Description:
This project demonstrates basic multitasking on an ESP32 using FreeRTOS with the Arduino framework. It consists of two independent tasks:
Led1Task: Toggles an onboard LED on GPIO 0 every 500 milliseconds.
DebugTask: Prints a debug message to the Serial Monitor every second.

This simple project illustrates how to run concurrent tasks on ESP32 using xTaskCreate() and manage task timing using vTaskDelay().

✅ Features:
Multitasking with FreeRTOS on ESP32
Non-blocking LED blinking task
Simultaneous serial debug printing task
Built with Arduino framework

📦 Requirements:
ESP32 development board
Arduino IDE (or PlatformIO)
FreeRTOS (comes with ESP32 Arduino core)

