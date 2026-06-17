# README 🎮🎮🎮

Ghost Busters is an embedded systems project that bidges hardware and game development. 
An STM32 microcontroller reads environmental sensors 
(temperature, pressure, humidity) and inertial sensors 
(gyroscope, accelerometer, magnetometer) in C and Assembly. 
The real-time sensr readings are streamed to a PC 
via UART communication protocol.

A Unity C# interface parses the terminal output and maps the live sensor readings to a game environment. 
Elements like ghost presence, proximity and whether the ghosts have been captured are driven by physical sensor values

Watch demo on youtube: [Ghostbusters](https://www.youtube.com/watch?v=j6OFqAWFTbM)
