# Hey, it's Brian 👋

**Embedded tinkerer, wireless security researcher, recovering YAML wrangler.**

I build small, cheap hardware that helps regular people stay safe, and firmware that makes a $15 dev board do things it has no business doing. Most of it runs on an ESP32.

"It's 2.4 GHz to the access point, I've got a full LiPo, half a spool of solder, it's dark, and I'm wearing sunglasses. Hit it."

## 🔭 What I'm into right now

- **Wireless security research.** Wi-Fi, BLE, sub-GHz (CC1101), 2.4 GHz (nRF24), LoRa, and GPS. I care most about detection: learn what "normal" looks like on the air, then flag what changed.
- **ESP32 firmware.** ESP-IDF and PlatformIO, LVGL and LovyanGFX, on everything from a C3 Super Mini to the ESP32-P4.
- **Custom hardware.** KiCad carrier boards, 3D printed enclosures, and a parts bin that really ties the room together.
- **Hardening my own repos.** Disclosure policies, CodeQL, Dependabot, pinned dependencies, signed firmware updates. Curse your sudden but inevitable CVEs.

## 📡 Wireless and security

| Project                                                                             | What it does                                                                                                                                                                                                           |
| ----------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [skimmer-detector](https://github.com/hey-its-brian/skimmer-detector)               | Pocket BLE/Wi-Fi sniffer that flags the radio modules hidden inside card skimmers. XIAO ESP32-C6, OLED, custom PCB. This aggression will not stand, man.                                                               |
| [rf-sentinel](https://github.com/hey-its-brian/rf-sentinel)                         | Receive-focused RF and GNSS monitoring node on an M5Stack ESP32-C5. Listens on 433 MHz, 2.4 GHz, and LoRa, builds a baseline, and raises events when something changes. You can't stop the signal, but you can log it. |
| [netmon](https://github.com/hey-its-brian/netmon)                                   | Log-O-Matic. Local-first pfSense log monitor with threshold rules, statistical baselines, and rule-to-log correlation against the real firewall ruleset.                                                               |
| [nRFBox-Capybara-Edition](https://github.com/hey-its-brian/nRFBox-Capybara-Edition) | My fork of the nRFBox 2.4 GHz research toolkit. One of several forks I use to learn how the well-known firmwares work.                                                                                                 |

## 🖥️ Cyberdecks and firmware

| Project                                                           | What it does                                                                                                                                                                                                                                  |
| ----------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [tab5-cyberdeck](https://github.com/hey-its-brian/tab5-cyberdeck) | **DECK//OS.** Cyberdeck firmware for the M5Stack Tab5 (ESP32-P4). SSH terminal, Ollama chat, markdown notes (including Obsidian self-hsoted livesync), file manager, music player, and signed over-the-air updates. API and App Repo to come. |
| [Core-OS](https://github.com/hey-its-brian/Core-OS)               | **Core//OS.** DECK//OS ported to a pocket-size M5Stack CoreS3 with a 35-key keyboard.                                                                                                                                                         |
| [cryptlings](https://github.com/hey-its-brian/cryptlings)         | A cozy, gently creepy virtual pet. Raise Mothman, Bigfoot, Nessie, or the Fresno Nightcrawler on the real clock and the real moon.                                                                                                            |
| [bigtrak](https://github.com/hey-its-brian/bigtrak)               | A 1979 Big Trak rebuilt around two ESP32 boards, with a touchscreen copy of the original keypad. No flux capacitor required. Custom board created by me is helpful, though.                                                                   |
| [deskbot](https://github.com/hey-its-brian/deskbot)               | Two parts, four wires, and a little robot face that gets bored of you.                                                                                                                                                                        |
| [flipclock-s3](https://github.com/hey-its-brian/flipclock-s3)     | Split-flap clock animation on a LilyGO T-Display S3.                                                                                                                                                                                          |
| [m5weather](https://github.com/hey-its-brian/m5weather)           | Color E Ink weather station with a browser config page and themes. No API key, no account.                                                                                                                                                    |

## 🏠 Home and homelab

|Project|What it does|
|---|---|
|[Project-Hestian](https://github.com/hey-its-brian/Project-Hestian)|Self-built smart thermostat for a heat pump. M5Stack Dial, ESPHome, Home Assistant, and it keeps running when the Wi-Fi does not.|
|[bambu-screen](https://github.com/hey-its-brian/bambu-screen)|Touchscreen controller for a Bambu Lab P1S over local MQTT. Clouds? Where we're going, we don't need clouds.|
|[bambu-logger-controller](https://github.com/hey-its-brian/bambu-logger-controller)|P1S monitor as a terminal TUI or a Docker web dashboard.|

There are also a few native macOS menu bar apps ([OneScreen](https://github.com/hey-its-brian/OneScreen), [repaste](https://github.com/hey-its-brian/repaste), [snipbook](https://github.com/hey-its-brian/snipbook), [Caffn8](https://github.com/hey-its-brian/Caffn8-App)) and one text adventure with zero dependencies ([saltmarrow](https://github.com/hey-its-brian/saltmarrow)).

## 💼 What would you say... you do here?

Senior developer in govtech/healthtech for 8+ years. Rails, Kubernetes (k3s and EKS), Terraform, AWS, GitOps, data remediation, runbooks, and incident response. I still run a k3s cluster, pfSense, and Pi-hole at home, and yes, I got the memo about the TPS reports.

The platform work is where the security habits come from. The radios are where the fun is.

## 🧰 Toolbox

**Embedded:** ESP32 (C3, C5, C6, S3, P4) • ESP-IDF • PlatformIO • ESPHome • LVGL • LovyanGFX • RadioLib • KiCad | **Radio:** Wi-Fi • BLE • CC1101 • nRF24 • LoRa/Meshtastic • GPS • NanoVNA | **Platform:** Kubernetes • Terraform • AWS • Argo CD • Docker • pfSense • Linux/Bash | **Languages:** C/C++ • Python • Ruby • Swift • Bash

## 📜 House rules

- Defense first. I build detectors, monitors, and baselines. Fun later.
- Don't be a skid.
- I only test gear and networks that I own or have written permission to test. See rule #2.
- If you find a security issue in one of my repos, use the private vulnerability report on that repo. That would be shiny.

## 📫 Find me

- 🌐 Virginia Beach, VA. Remote-first.
- 💬 Ask me about: cheap hardware for home network security, ESP32 firmware, safe data remediation, runbooks.
- ✉️ [brian@heyitsbrian.com](mailto:brian@heyitsbrian.com)
