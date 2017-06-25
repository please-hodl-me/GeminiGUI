# GeminiGUI
Windows .NET GUI for Gemini Cryptocurrency Exchange

The actual GUI application itself is closed source at the moment, but it is essentially a wrapper around the open source Gemini API library (Gemini.dll) I've [published here](https://github.com/please-hodl-me/Gemini). Feel free to recompile the DLL or modify it.

* Written in C#, using no external libraries to increase security.
* API Keys are stored as AES-256 encrypted files
* Data is ONLY transmitted to Gemini. User data is NEVER stored anywhere you don’t specify
* Ability to place limit order, and psuedo-stop orders
* No telemetry, no automatic updates, no communicating with unknown servers.
* Free!
