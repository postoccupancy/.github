# Projects

## Sensing and data 

| Project | Description | Source / interface |
| --- | --- | --- |
| **Resident Frequency (RF)** | A portable, self-contained local sensing and signal network that can operate without an Internet connection. Connects environmental sensors, audio inputs, signal-processing tools, and browser applications. | [Interface](https://rf.postoccupancy.com) |
| **Electric Sea** | Raspberry Pi server for the RF network. Hosts the `rf-router` Node.js service for USB, OSC, PCM, WebSocket, and HTTP communication, alongside browser applications for signal visualization, voice analysis, microphone input, Moiré patterns, and recording. | [Code](https://github.com/postoccupancy/electric-sea) · [Interface](https://rf.postoccupancy.com) |
| **Indoor Sky** | Indoor ESP32-S3 station with BME280 weather sensor and INMP441 microphone. Streams live 100Hz sensor data and 16kHz audio over USB to Electric Sea. | [Firmware](https://github.com/postoccupancy/indoor-sky) |
| **Electric Sky** | Outdoor ESP32-S3 CAM sensing station with BME weather sensor, INMP441 microphone, and camera. Streams live 100Hz sensor data and 16kHz audio over WiFi to Electric Sea. | [Firmware](https://github.com/postoccupancy/electric-sky) |
| **Weather Brain** | Windows-hosted Python/FastAPI and PostgreSQL backend for environmental archives, time-series analysis, spectral features, and LLM-assisted interpretation. | [Code](https://github.com/postoccupancy/weather-brain) |

## Generative sound and visualization

| Project | Description | Source / interface |
| --- | --- | --- |
| **Weather Music** | An audiovisual performance and art installation that translates live environmental data into a generative evolving experience. | [audio composer](https://github.com/postoccupancy/weather-music) · [visual composer](https://postoccupancy.com/instruments/wave-interference) · [chord extractor](https://postoccupancy.com/instruments/resident-frequency) |
| **DSP for Artists** | Interactive lessons and audiovisual instruments exploring harmonics, wave interference, spectral visualization, and live sensor-driven imagery using React, p5.js, and Web Audio. | [Workshop](https://postoccupancy.com/) · [Wave Interference](https://postoccupancy.com/instruments/wave-interference) |


## Web and community platforms

[postoccupancy](https://postoccupancy.com) — A Next.js/React/TypeScript app space for project documentation, sensor dashboards, interactive lessons, and audiovisual applications. [Code](https://github.com/postoccupancy/postoccupancy.com).

[capitolhillweb](https://github.com/capitolhillweb) — Git-based content management and community-oriented publishing tools. 
