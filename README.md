# IndiaCodex Hackathon 2025 - Cardano Hardware Implementation with Plant Monitoring

This project demonstrates a revolutionary integration of blockchain technology with IoT hardware for sustainable agriculture monitoring. Built on the Cardano blockchain (PreProd testnet), our system combines Arduino-based sensor networks with real-time transaction verification displays. The hardware implementation features dual Arduino Uno boards: one monitoring environmental conditions (soil moisture, temperature, humidity) through calibrated sensors, and another displaying blockchain transaction confirmations via I2C LCD interface. The system bridges physical plant health data with immutable blockchain records, creating a transparent and verifiable supply chain for agricultural produce. Key components include automated payment triggers based on sensor thresholds, real-time LCD transaction display with heartbeat monitoring, integration with Cardano's address management and UTXO model, and a comprehensive bridge system connecting hardware sensors to blockchain infrastructure. This solution addresses critical challenges in agricultural transparency, enables micro-payments for sustainable farming practices, provides immutable records of growing conditions, and demonstrates practical blockchain applications beyond traditional finance.

---

## 📜 License & Attributions

This project is licensed under the **MIT License**.

### Third-Party Libraries & Components

This project utilizes the following open-source libraries and tools:

#### **Arduino Libraries**
- **hd44780** by Bill Perry - LCD library with auto-detect I2C support (GPL-3.0)
- **DHT sensor library** by Adafruit - Temperature & humidity sensor (BSD License)
- **Adafruit Unified Sensor** by Adafruit - Unified sensor driver (Apache-2.0)
- **Arduino Core Libraries** - Standard Arduino libraries (LGPL-2.1)

#### **Node.js / JavaScript**
- **SerialPort** - Serial communication library (MIT)
- **Express.js** - Web framework (MIT)
- **Axios** - HTTP client (MIT)
- **dotenv** - Environment variable management (BSD-2-Clause)

#### **Python**
- **PySerial** - Python serial port access (BSD-3-Clause)
- **Requests** - HTTP library (Apache-2.0)

#### **Cardano Ecosystem**
- **Cardano Node** - Blockchain infrastructure (Apache-2.0)
- **cardano-cli** - Command-line interface (Apache-2.0)
- **Cardano PreProd Testnet** - Test network infrastructure

#### **MCP (Model Context Protocol)**
- **Sokosumi MCP Server** - Custom MCP server for plant monitoring (MIT)
- **Claude Desktop Integration** - AI assistant integration (Anthropic Terms of Service)

#### **Hardware Components**
- **Arduino Uno** - Microcontroller platform (CC BY-SA)
- **DHT22** - Digital temperature and humidity sensor
- **YL-69 / HL-69** - Capacitive soil moisture sensor
- **I2C LCD Display (16x2)** with PCF8574 I/O expander

### License Compliance

All third-party components are used in compliance with their respective licenses. Full license texts are available in the `LICENSES/` directory or from the original project repositories.

---

## 🙏 Thank You

We sincerely thank the IndiaCodex Hackathon 2025 organizers and judges for this incredible opportunity to showcase innovation at the intersection of blockchain technology and sustainable agriculture. Special appreciation to the Cardano community for their excellent documentation and testnet infrastructure, the Arduino community for robust hardware libraries, Anthropic for Claude and MCP framework, and all open-source contributors whose libraries and tools made this project possible. This hackathon has been an inspiring journey in pushing the boundaries of what's possible when cutting-edge technology meets real-world agricultural challenges.

**Team**: Masumi Cardano Hardware Implementation  
**Repository**: [IndiaCodexHackathon--25-Submission](https://github.com/DhanushKenkiri/IndiaCodexHackathon--25-Submission)  
**Default Branch**: hackathon-submission  
**License**: MIT

---

### MIT License

```
MIT License

Copyright (c) 2025 Masumi Cardano Hardware Implementation Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
