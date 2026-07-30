# Hi, I'm Max 👋

This is my workshop corner of the interne — the stuff I build in my own time, for my own reasons.

Usually it starts with a problem around the house, or just curiosity about a chip I haven't used yet.
I draw the part in Fusion 360, design the board that goes inside it, write the firmware, and then keep
fiddling with it long after it works.

Nothing here is polished product code. It's hobby code — but it's honest, and it runs.

---

## 🔧 Things I've built

| Project | What it is |
|---|---|
| [**Sensorstation**](https://github.com/Tinymaxi/Sensorstation) | The one that's been running longest. A Raspberry Pi watching my air: BME280, SCD30, TSL2591 and an SDS011 particulate sensor, all writing into InfluxDB and drawn in Grafana. A DIP switch on the case handles WiFi and shutdown; a PIR sensor wakes the display when I walk past. |
| [**NewKorndispenser**](https://github.com/Tinymaxi/NewKorndispenser) | A machine that dispenses grain by weight. Pico in C++, HX711 load cell, rotary-encoder menu, I²C LCD, NeoPixel ring so it can tell me what it's doing from across the room. |
| [**hx711-pico**](https://github.com/Tinymaxi/hx711-pico) | Fell down a rabbit hole getting the HX711 load cell ADC working properly on the Pico, so I pulled it out into its own driver. Uses PIO, does tare and calibration, stores the scale factor in flash. |
| [**Luftmessdaten**](https://github.com/Tinymaxi/Luftmessdaten) | An earlier air-quality box. Three sensors on SPI, one on serial, some OpenWeather data mixed in, a battery pack so it could go anywhere, and a live dashboard. Started as an excuse to really understand SPI. |
| [**Py-kneader**](https://github.com/Tinymaxi/Py-kneader) | A kneading machine with a mind of its own — relay control, SSD1306 display, DHT11, a buzzer to tell me when the dough is done. |

---

## 🧰 What I tinker with

**Hardware** Raspberry Pi · Pico / RP2350 · Fusion 360 for CAD *and* the PCBs · far too many sensors

**Code** C++ for anything embedded · Python for everything else

**Running at home** Pi-hole · Nextcloud · the sensor station · a seven-segment clock that has been on since 2020

---

Always happy to talk shop about load cells, dust sensors, or why the board never fits the enclosure the first time.
