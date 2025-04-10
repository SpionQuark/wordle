# Wordle - Stay Safe!

Wordle is an easy and userfriendly desktop-application giving you the opportunity to save important information more secure. 
The app uses AES-Encryption to safe your data with a password you can set so only you can acces the file.

Quick install with our new [installer](https://github.com/SpionQuark/wordle/blob/main/wordle-installer.exe) or at [release](https://github.com/SpionQuark/wordle/releases/wordle_publish)

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
│   ├── [index.html](http://_vscodecontentref_/2)          # Main-HTML-File
│   ├── [script.js](http://_vscodecontentref_/3)           # Main-JavaScript-File
│   ├── [styles.css](http://_vscodecontentref_/4)          # Main-CSS-File
│   └── info/
│       └── [index.html](http://_vscodecontentref_/5)      # Information-site
├── forge.config.js                                        # Electron Forge Configuration
├── [main.js](http://_vscodecontentref_/6)                 # Electron main-process
├── [package.json](http://_vscodecontentref_/7)            # Project-configuration
```

## Development

### Scripts

```npm start```: Starts the application in development mode.
```npm run make```: Creates an executable.
```npm run package```: Verpackt die Anwendung ohne Installer.
```npm run build```: Creates a build for the application.

### Technologies

- Electron: For crossplatform development and usage.
- CryptoJS: For AES-encryption
- HTML/CSS/JavaScript: For better interface.

### Security

- Local saving: All data is being saved locally and wont be transmitted to any exernal server.
- AES-encryption: Strong encryption can save your Data from unauthorized access.

## License

### Hobbyist License
### Copyright (C) 2025 SpionQuark

* DE (Deutsch):

1. Diese Software darf ausschließlich für private, nicht-kommerzielle Zwecke genutzt werden.

2. Es ist nicht gestattet, die Software zu verändern, weiterzugeben oder zu veröffentlichen.

3. Jegliche kommerzielle Nutzung, einschließlich Verkauf, Vermietung oder Integration in kommerzielle Produkte, ist ausdrücklich untersagt.


* EN (English):

1. This software is for private, non-commercial use only.

2. It is strictly prohibited to modify, distribute, or publish the software.

3. Any commercial use, including selling, renting, or integrating it into commercial products, is explicitly prohibited.

## Author

Made by ***SpionQuark***

Feedback and Suggestions are welcome!

## Issue and bug report or new Ideas?

If you have any kind of problem or a good idea open a new [Issue](https://github.com/SpionQuark/wordle/issues)

## See for yourself

<img alt="Wordle Vorschau" src="https://via.placeholder.com/800x400?text=Wordle+App+Screenshot">
