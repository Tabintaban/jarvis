# JARVIS Voice Assistant

![We are NOT limited by the technology of our time!](poster.jpg)

`Jarvis` - is a voice assistant made as an experiment using neural networks for things like **STT/TTS/Wake Word/NLU** etc.

The main project challenges we try to achieve is:
 - 100% offline *(no cloud)*
 - Open source *(full transparency)*
 - No data collection *(we respect your privacy)*

Our backend stack is 🦀 **[Rust](https://www.rust-lang.org/)** with ❤️ **[Tauri](https://tauri.app/)**.<br>
For the frontend we use ⚡️ **[Vite](https://vitejs.dev/)** + 🛠️ **[Svelte](https://svelte.dev/)**.

*Other libraries, tools and packages can be found in source code.*

## Neural Networks

This are the neural networks we are currently using:

 - Speech-To-Text
	 - [Vosk Speech Recognition Toolkit](https://github.com/alphacep/vosk-api) via [Vosk-rs](https://github.com/Bear-03/vosk-rs)
 - Text-To-Speech
	 - [~~Silero TTS~~](https://github.com/snakers4/silero-models) *(currently not used)*
	 - [~~Coqui TTS~~](https://github.com/coqui-ai/TTS) *(currently not used)*
	 - [~~WinRT~~](https://github.com/ndarilek/tts-rs) *(currently not used)*
	 - [~gTTS~](https://github.com/nightlyistaken/tts_rust) *(currently not used)*
	 - [~~SAM~~](https://github.com/s-macke/SAM) *(currently not used)*
 - Wake Word
	 - [Rustpotter](https://github.com/GiviMAD/rustpotter) *(Partially implemented, still WIP)*
	 - [Picovoice Porcupine](https://github.com/Picovoice/porcupine) via [official SDK](https://github.com/Picovoice/porcupine#rust) *(requires API key)*
	 - [Vosk Speech Recognition Toolkit](https://github.com/alphacep/vosk-api) via [Vosk-rs](https://github.com/Bear-03/vosk-rs) *(very slow)*
	 - [~~Snowboy~~] *(currently not used)*
 - NLU
	 - Nothing yet.
- Chat
	- [~~ChatGPT~~](https://chat.openai.com/) (coming soon)

## Supported Languages

Currently, only Russian language is supported.<br>
But soon, Ukranian and English will be added for the interface, wake-word detection and speech recognition.

## How to build?

Nothing special was used to build this project.<br>
You need only Rust and NodeJS installed on your system.<br>
Other than that, all you need is to install all the dependencies and then compile the code with `cargo tauri build` command.<br>
Or run dev with `cargo tauri dev`.

<br><br>
*Thought you might need some of the platform specific libraries for [PvRecorder](https://github.com/Picovoice/pvrecorder) and [Vosk](https://github.com/alphacep/vosk-api).*

## Author

Abraham Tugalov

## Python version?
Old version of Jarvis was built with Python.<br>
The last Python version commit can be found [here](https://github.com/Tabintaban/jarvis/tree/943efbfbdb8aeb5889fa5e2dc7348ca4ea0b81df).

## License

[Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/)<br>
See LICENSE.txt file for more details.

## Ссылки на Видео
1) https://www.youtube.com/watch?v=YeS755SPSI8
[![Video Title](https://img.youtube.com/vi/YeS755SPSI8/0.jpg)](https://www.youtube.com/watch?v=YeS755SPSI8)
2) https://www.youtube.com/watch?v=BCeNEqH_15I
[![Video Title](https://img.youtube.com/vi/BCeNEqH_15I/0.jpg)](https://www.youtube.com/watch?v=BCeNEqH_15I)
3) https://www.youtube.com/watch?v=XTeGvaDaraI
[![Video Title](https://img.youtube.com/vi/XTeGvaDaraI/0.jpg)](https://www.youtube.com/watch?v=XTeGvaDaraI)
4) https://www.youtube.com/watch?v=Z5mXFkIKwmM
[![Video Title](https://img.youtube.com/vi/Z5mXFkIKwmM/0.jpg)](https://www.youtube.com/watch?v=Z5mXFkIKwmM)
5) https://www.youtube.com/watch?v=pTDTIkLRQKQ
[![Video Title](https://img.youtube.com/vi/pTDTIkLRQKQ/0.jpg)](https://www.youtube.com/watch?v=pTDTIkLRQKQ)
6) https://www.youtube.com/watch?v=PvbzrEaSm3s
[![Video Title](https://img.youtube.com/vi/PvbzrEaSm3s/0.jpg)](https://www.youtube.com/watch?v=PvbzrEaSm3s)
7) https://www.youtube.com/watch?v=mzL9BY1D2L0
[![Video Title](https://img.youtube.com/vi/mzL9BY1D2L0/0.jpg)](https://www.youtube.com/watch?v=mzL9BY1D2L0)
8) https://www.youtube.com/watch?v=E5wbrow870o
[![Video Title](https://img.youtube.com/vi/E5wbrow870o/0.jpg)](https://www.youtube.com/watch?v=E5wbrow870o)

https://www.youtube.com/watch?v=8dXuf-vuxMA
[![Video Title](https://img.youtube.com/vi/8dXuf-vuxMA/0.jpg)](https://www.youtube.com/watch?v=8dXuf-vuxMA)
https://www.youtube.com/watch?v=Aynk3YSdqzo
[![Video Title](https://img.youtube.com/vi/Aynk3YSdqzo/0.jpg)](https://www.youtube.com/watch?v=Aynk3YSdqzo)
https://www.youtube.com/watch?v=Pmu0vmrXEEY
[![Video Title](https://img.youtube.com/vi/Pmu0vmrXEEY/0.jpg)](https://www.youtube.com/watch?v=Pmu0vmrXEEY)
https://www.youtube.com/watch?v=BJ5UTshqHzU
[![Video Title](https://img.youtube.com/vi/BJ5UTshqHzU/0.jpg)](https://www.youtube.com/watch?v=BJ5UTshqHzU)




