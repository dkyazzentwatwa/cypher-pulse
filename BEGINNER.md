# Beginner's Guide to Cypher Pulse

## What is this project?
Cypher Pulse is an ESP32-based research platform that controls two CC1101 radio modules. It can scan for, record, and replay signals in the 433 MHz ISM band and can be configured for jamming experiments. The project is intended for learning about radio-frequency (RF) communication and for building your own experiments.

## Safety and Legal Notes
- **Know the law.** Operating a jammer or recording someone else's traffic may be illegal in your region. Only transmit or capture signals on frequencies you are licensed to use and with the explicit permission of all parties involved.
- **Use in a controlled environment.** Jamming can disrupt alarms, garage doors, or emergency communications. Perform tests in a Faraday cage or at very low power to avoid interfering with other devices.
- **You are responsible.** The authors and contributors provide this code for educational and research purposes only. They cannot be held liable for any damage, fines, or injuries that result from misuse.

## Getting Started
1. Review the [README](README.md) for hardware requirements and wiring.
2. Install the Arduino libraries listed in the README.
3. Upload `cypher-pulse.ino` to your ESP32 using the Arduino IDE or another compatible tool.
4. Use the on-board buttons and OLED display to navigate the menu.
5. Monitor serial output (115200 baud) for debugging information.

## Tips for New Users
- Start with the **TEST_CC1101** option to verify your radio connections before attempting other modes.
- Keep a notebook of frequencies you explore. It will help you understand the RF landscape and avoid accidental interference.
- If something stops responding, use the **RESET CC** or **STOP ALL** menu options to bring the device back to a known state.
- Share your improvements! Pull requests and issues are welcome.

## Further Reading
- [Evil Crow RF project](https://github.com/joelsernamoreno/EvilCrow-RF) – inspiration for this tool.
- [SmartRC-CC1101-Driver-Lib](https://github.com/LSatan/SmartRC-CC1101-Driver-Lib) – library used for CC1101 communication.

Use this project responsibly and keep experimenting!
