# Wordle - Stay Safe!

Wordle is an easy and userfriendly desktop-application giving you the opportunity to save important information more secure. 
The app uses AES-Encryption to safe your data with a password you can set so only you can acces the file.

## Features

- **Secure saving**: Safe your data locally or in the cloud with our special `.wordle`-files.
- **Passwordsecurity**: The data will be safed with passwords set by you. As the mechanism is the same on any app you can quickly transfer the data to other devices.
- **User friendly**: Intuitive Userinterface with better optics and cool design.
- **Cross-platform**: Developed with [Electron](https://www.electronjs.org/), runs on Windows (tested), Linux and macOS.
- **Open Source**: The source-code will soon be open source, as this app will first be on steam and only later on github.

---

## Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Projectstructure](#structure)
4. [Development](#development)
5. [License](#license)

---

## Installation

### Requirements

- [Node.js](https://nodejs.org/) (Version 16 oder höher)
- [npm](https://www.npmjs.com/) oder [yarn](https://yarnpkg.com/)

### Step for step

1. Klonen Sie das Repository:
   ```bash
   git clone https://github.com/username/wordle.git
   cd wordle
2. Install dependencies
    ```bash
    npm install

3. Start the application in dev mode
    ```bash
    npm start
4. Build the runable application
    ```bash
    npm run make

## Usage

### Mainfunction

1. New files:
    + click on ``` File > New```
    + Now you can start writing
2. Save file
    + click on ```File > Save```
    + Select the path to your file and enter the password used for the encryption
3. Open file
    + click on ```File > Open```
    + Choose a ``` .wordle```-File and enter your password
4. Password-dialogue
    + We have a special dialogue just for you to enter a password. 

## Structure
```
wordle/
├── app/
│   ├── [index.html](http://_vscodecontentref_/2)          # Haupt-HTML-Datei
│   ├── [script.js](http://_vscodecontentref_/3)           # Haupt-JavaScript-Datei
│   ├── [styles.css](http://_vscodecontentref_/4)          # Haupt-CSS-Datei
│   └── info/
│       └── [index.html](http://_vscodecontentref_/5)      # Info-Seite
├── forge.config.js         # Electron Forge Konfiguration
├── [main.js](http://_vscodecontentref_/6)                 # Electron Hauptprozess
├── [package.json](http://_vscodecontentref_/7)            # Projektkonfiguration und Abhängigkeiten
```
