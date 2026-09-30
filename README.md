![ssaprus_small_logo](assets/ssaprus_logo.jpg)

# WhisperOS

**WhisperOS** is firmware for small LoRa radio boards, like the Heltec V3 and V4. It lets you send text messages without internet or cell service. Devices talk to each other directly and relay messages through other devices to reach further.

Think of it as a walkie-talkie for text messages.

## Features

### Messaging
- **Off-grid text:** Send direct messages and channel messages over the mesh.
- **Contacts:** See who is on the network and when you last heard from them (e.g. "5m ago").
- **Quick messages:** Send preset phrases and see delivery status.
- **Languages:** English and Simplified Chinese interface. Messages display in Chinese, Japanese, Korean, and many other languages.

### Input
- **On-screen keyboard** with predictive text in English, plus full Pinyin input with phrase suggestions.
- **CardKB:** Plug in a CardKB mini keyboard at any time. The device detects it on its own.
- **Morse code input** as another way to type.

### Display
- **Always-on clock** with Default, Binary, Cat, and Dog faces, so your device can double as a desk clock.
- **Brightness and Zen mode:** Dim the screen or keep it off to save battery.
- **Notifications:** Buzzer, LED, or vibration. Turn each one off when you need quiet.

### Power
- **Long battery life:** Up to 7 days of standby with light messaging on Heltec V3 and V4.
- **Battery info:** Voltage readout and ADC calibration on the device.
- **USB power:** The screen stays on while USB power is connected, and turns off on battery.

### GPS
- **Duty cycle modes:** Pick how often GPS gets a fix, from Fast to Ultra Eco, to trade accuracy for battery life.
- **Location privacy:** Share exact coordinates, a rounded area, or none.

### Radio and Repeater
- **Radio setup on the device:** Change frequency, bandwidth, spreading factor, coding rate, and transmit power.
- **Radio status:** Signal strength of the last message with a history graph, plus live noise floor.
- **Repeater mode** with live stats. Set Routing to Standard or Max to skip 1-byte packets.

### Connection and Updates
- **Bluetooth or USB** to the MeshCore companion app. The device detects USB on its own.
- **Back up and restore** settings, contacts, and channels over the companion connection.
- **BLE OTA updates** on nRF52 devices.

## Who is it for?
- **Hikers and campers** in areas with no cell service.
- **Emergency preppers** who need a backup when towers are down.
- **Groups at festivals or large events** where mobile networks are congested.
- **Radio tinkerers** who want to experiment with mesh networking.

## 📥 Download

Flash the latest firmware from your browser at **[https://whisperos.dev](https://whisperos.dev)**.

See what's new in the **[changelog](https://whisperos.dev/changelogs)**.

## 🔔 Get Updates

- **Discord**: [https://discord.gg/73jThCU9cw](https://discord.gg/73jThCU9cw)
- **Telegram**: [https://t.me/whisper_dev](https://t.me/whisper_dev)
- **YouTube**: [https://www.youtube.com/@tsaokoming](https://www.youtube.com/@tsaokoming)

## 🐞 Report a Problem

Open an issue with the **[bug report or feature request form](https://github.com/ssaprus/whisperOS/issues/new/choose)**.

## The Fine Print 📝

* **Testing firmware:** These builds are experimental. Test them before you rely on them.
* **Back up your data:** Back up your settings and messages before you install new firmware.
* **No warranty:** Provided as-is with no guarantees.
* **Use responsibly:** Follow your local radio regulations. You are responsible for lawful use.

## 🌐 Powered by MeshCore

[Learn more about MeshCore](https://github.com/meshcore-dev/MeshCore)
