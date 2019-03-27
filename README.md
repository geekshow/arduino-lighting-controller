# Arduino STM32 MQTT Controller
This Arduino project was created as the basis of a home automation controller that could support:
- Temperature / Humidity sensors (DHT22 / DS18B20)
- Relay outputs
- Other simple inputs (eg: PIRs and Door switches)

It rolls up the data and sends out to the MQTT broker, also receiving commands from the broker to switch on/off the relays.
