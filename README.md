# Ezlo RF Switch Door and Window Sensor
This product will be part of Ezlo Low Power RF Devices Initiative that will focus on providing users with capability to control RF devices using EzloPi or directly through RF using the Ezlo RF HUB.

## Project Requirements
- Study the Existing Door and Window senors and their teardowns available through Chinese OEMs just to get an idea.
- Develop a hardware that can work in a battery powered environment and has the following features:
    - EzloPi capable using EzloPi ESP32
    - Contains an RF tranceiver that can cover multiple frequencies as configured. CC1101 based module can be reused here from IR-RF Blaster product
    - The trigger from door and window sensor should fall on a EXT pin on ESP32
    - The latch circuit for Wake up / Power Up designed in IR-RF blaster should be added
    - The ESP32 should be able to wake up from both sensor trigger as well as RF signal
    - The overall size and cost should be kept as low as possible

