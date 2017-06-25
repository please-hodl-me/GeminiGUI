# GeminiGUI
### Windows .NET GUI for Gemini Cryptocurrency Exchange

*Donate* 12fj5Stp31SrYjtcN9T1jnXPGKUsEF92KD

![image](http://i.imgur.com/PRtZ9ZC.png)

## Details:

The actual GUI application itself is closed source at the moment, but it is essentially a wrapper around the open source Gemini API library (Gemini.dll) I've [published here](https://github.com/please-hodl-me/Gemini). Feel free to recompile the DLL or modify it.

* Written in C#, using no external libraries to increase security.
* API Keys are stored as AES-256 encrypted files
* Data is ONLY transmitted to Gemini. User data is NEVER stored anywhere you don’t specify
* Ability to place limit order, and psuedo-stop orders
* No telemetry, no automatic updates, no communicating with unknown servers.
* Free!

## Setup:

1. Make an account at Gemini
2. Enable API Access, and generate a Key and Secret
3. Open GeminiGUI->File->Wallet->New. Paste your Key and Secret, and choose a password to encrypt them
4. Load your "wallet" file, and start using the client!


