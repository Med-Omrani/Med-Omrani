# Mohamed Omrani

**Embedded software engineer — STM32, RTOS, edge AI.**

I build firmware for systems that have to be right: a motor that stops when the guard
opens, a sensor frame that cannot be altered in transit, a fault caught before it
becomes a breakdown. Bare metal or FreeRTOS, C or Python, from the datasheet to a
board that has been tested.

Currently looking for an embedded role on a physical product — Tunisia or Europe.

---

## What I work on

- **Industrial control** — test benches and machines: cycle control, safety
  interlocks, operator interface on STM32.
- **Edge AI** — inference on the device rather than in a cloud: TensorFlow Lite and
  NCNN, models small enough to ship.
- **Connected sensing** — LoRa, BLE and MQTT links where the payload is
  authenticated, not merely encrypted.

## Selected repositories

| Repository | What it is |
|---|---|
| **[cable-endurance-bench](https://github.com/Med-Omrani/cable-endurance-bench)** | Control firmware for a cable fatigue test bench — keypad-set cycles, OLED status, stepper drive, E-stop and guard interlock. STM32F103, embedded C. |
| **[secure-field-monitoring](https://github.com/Med-Omrani/secure-field-monitoring)** | Sensor link sealed with AES-128 and HMAC-SHA256 before it leaves the node. ESP32 + LoRa → Raspberry Pi. |
| **[live-object-detection](https://github.com/Med-Omrani/live-object-detection)** | Real-time object detection from a USB camera on a Raspberry Pi, YOLO exported to NCNN — CPU only, no accelerator. |
| **[access-code-lock](https://github.com/Med-Omrani/access-code-lock)** | Digital combination lock in VHDL on an Intel MAX 10: keypad scan, debouncing, 7-segment output, lockout. |

## Toolbox

`C` · `STM32 HAL/LL` · `FreeRTOS` · `I²C / SPI / UART / CAN` · `Python` ·
`TensorFlow Lite` · `NCNN` · `VHDL` · `ESP32` · `LoRa` · `BLE` · `MQTT` ·
`GDB / ST-Link` · `Git` · `Docker`

## Contact

[Email](mailto:mohamed.omrani.eng@gmail.com) ·
[LinkedIn](https://linkedin.com/in/mohamed-omrani-220591367) ·
[CV (PDF)](./Mohamed_Omrani_CV.pdf)
