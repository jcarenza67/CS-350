# CS 350 Final Project Reflection

## Project Summary
This project focused on building out an embedded system on a Raspberry Pi that grew in complexity over the term. It started with simple LED control and eventually included a button, multiple LEDs, a 16x2 display, and a temperature and humidity sensor. The goal was to create a working system that could react to user input, collect real data, and output information clearly. The project solved the problem of integrating hardware and software in a way that was consistent, reliable, and easy to test.

## What I Did Well
I kept my code organized and predictable. Using a clean state machine structure made the behavior easy to follow, and my wiring stayed neat so troubleshooting never became overwhelming. When something didn’t behave right, the structure made it simple to isolate the cause.

## Where I Could Improve
I could improve by documenting my small fixes more often. I solved issues quickly, but I didn’t always write down what caused them or how I resolved them. Better documentation while troubleshooting would help with long-term understanding.

## Tools and Resources I Added to My Support Network
I relied on the Raspberry Pi documentation, gpiozero guides, state machine examples, and class resources. These helped me check assumptions fast and avoid unnecessary mistakes. They’re all tools I’ll keep using for future embedded or IoT work.

## Transferable Skills
State machine design, timing control, hardware integration, debugging, and keeping code modular are all skills that carry over directly into other coursework and real projects. Understanding how sensors, displays, and GPIO interact is also valuable for any embedded or automation environment.

## How I Made the Project Maintainable, Readable, and Adaptable
I separated responsibilities clearly, used consistent naming, and kept timing and configuration values easy to adjust. The state machine made the flow easy to understand at a glance. The overall structure makes it simple for someone else to modify the behavior without rewriting the entire program.
