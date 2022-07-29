# wsn_E5
UiO Lora E5 logger hardware design



Electronic design of the Lora E5 Mini logger for RIOT firmware. The logger is designed for optimized power consumption, connectivity, and prioritizing data collection in remote and cold regions. The logger handles a variety of digital protocols (SDI-12, I2C, UART) to communication to sensors. Radio uses the LoRa protocol. 

Open-source License MIT, see the file [`LICENSE`](https://github.com/spectraphilic/wsn_E5/blob/main/LICENSE)



## Logger V1

The designed is made out of commercial breakout boards. All break out are joined by a main PCB board using through-hole components. To open the files, use the open source software [KiCad](https://www.kicad.org/).

**Objectives for V1:**

- complete a functional design
- deploy design in real conditions
- Iterate design and finalize a SMD PCB for V2

### Resources

- RIOT LoRa E5 [webpage](https://doc.riot-os.org/group__boards__lora-e5-dev.html)
- E5 Mini [tutorial](https://stm32python.gitlab.io/fr-version-lora/lora-e5-mini.html)

