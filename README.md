# Hey, I'm Maestro8484

I hold multiple professional licenses in psychiatric and substance use
disorder treatment. I am not an engineer. I grew up navigating DOS,
CDing my way to Wolfenstein and Duke Nukem, and somewhere between then
and now I became someone who wires ESP32s at midnight and argues with
local LLMs.

Everything here is self-taught, built in my spare time, and runs in
my house.

---

## What I Build

Maker, home lab tinkerer, and local AI enthusiast based in Utah.
Voice assistants, robot faces, addressable LED installations, retro
arcade systems, and home automation -- all running on my own hardware.
No cloud required.

---

## Active Projects

### IRIS -- AI Robot Face
Stationary interactive robot face with animated eyes, emotion system,
and voice. Built on a Teensy 4.1 (TeensyEyes), Raspberry Pi 4 (voice
pipeline), and ESP32-S3 (serial bridge). Uses local LLMs via Ollama.
- Repo: [IRIS-Robot-Face](https://github.com/Maestro8484/IRIS-Robot-Face)
- - Stack: C++, Python, PlatformIO, Ollama, Piper TTS, Wyoming Whisper
 
  - ### Jarvis -- Pi4 Voice Assistant
  - Always-on wake-word voice assistant running fully local.
  - Wake word detection, Whisper STT, Ollama LLM backend, Piper TTS,
  - LED feedback ring, PTT button, camera vision, and a kids mode.
  - - Stack: Python, Raspberry Pi 4, ReSpeaker HAT, Ollama (Gemma 3)
   
    - ### Batocera Arcade
    - FBNeo arcade emulation on Raspberry Pi 5 with game-time control
    - system -- 30-minute sessions, audio warnings, hard cutoffs, and
    - Home Assistant integration for parental control via HTTP commands.
    - - Stack: Batocera, Python, Home Assistant
     
      - ### NeoPixel Clock -- ESP32
      - Inspired by Steve Manley's 3-ring RGB LED clock design. His original
      - ran on an Arduino Nano with a hardware RTC and MSGEQ7 audio chip.
      - I rebuilt it from scratch for ESP32: eliminated the RTC (software
      - timekeeping), removed MSGEQ7, added WiFi with a web UI for time-setting,
      - and rewrote the architecture as modular C++ classes with thread-safe
      - ISR button handling.
      - - Design inspiration: [Steve Manley RGB LED Clock V2](https://www.youtube.com/@SteveManley)
        - - Repo: [neopixelClockESP32](https://github.com/Maestro8484/neopixelClockESP32)
         
          - ---

          ## WLED Lighting -- Home Installations

          Heavy user of [WLED](https://kno.wled.ge/) for addressable LED projects
          throughout my home, running on ESP32/ESP8266 hardware with Home Assistant
          integration.

          | Project | Details |
          |---|---|
          | Holiday exterior lighting | 1,420 WS2812/WS2815 LEDs, 5 ESP8266 nodes, whole-home roofline and landscape |
          | Interior accent lighting | Multiple zones, WLED-controlled, Home Assistant automations |
          | Large infinity cube | Custom laser-cut acrylic, mirrored interior |
          | Small infinity cube | Desktop scale, laser-cut acrylic |

          ---

          ## Fabrication

          Most enclosures, panels, and structural parts are designed and built in-house.

          - **Bambu Lab P1S** -- enclosures, mounts, and brackets
          - - **100W CO2 laser** -- acrylic cutting and engraving for panels, diffusers,
            -   infinity cube mirrors, and custom signage
            -   - Typical acrylic stock: 5.75mm, 0.16mm kerf dialed in
             
                - ---

                ## Tech I Work With

                ![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
                ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
                ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
                ![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=flat&logo=raspberry-pi&logoColor=white)
                ![Home Assistant](https://img.shields.io/badge/Home_Assistant-41BDF5?style=flat&logo=home-assistant&logoColor=white)
                ![WLED](https://img.shields.io/badge/WLED-FF6900?style=flat&logoColor=white)
                ![Ollama](https://img.shields.io/badge/Ollama-local_AI-black?style=flat)
                ![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat&logo=platformio&logoColor=white)

                ---

                ## Forks I've Modified

                | Repo | Original Author | What I Changed |
                |---|---|---|
                | [ESP32-Drawing-Robot](https://github.com/Maestro8484/ESP32-Drawing-Robot-ESP32-S3-DevKitC1-) | [MatixYo](https://github.com/MatixYo/ESP32-Drawing-Robot) | PlatformIO config, servo pin assignments, WiFiManager |
                | [TeensyEyes](https://github.com/Maestro8484/TeensyEyes) | [chrismiller](https://github.com/chrismiller/TeensyEyes) | Eyelid scale factor controls, eye config for IRIS emotions |
                | [WLED](https://github.com/Maestro8484/WLED) | [wled/WLED](https://github.com/wled/WLED) | Personal config only |
                | [MarlinConfigs](https://github.com/Maestro8484/MarlinConfigs) | [BDFife](https://github.com/BDFife/MarlinConfigs) | Config for my specific printers |

                ---

                ## YouTube

                [@schm3116](https://www.youtube.com/@schm3116) -- build videos, demos, and shorts

                ---

                *Building in public. Projects are documented as they ship.*
