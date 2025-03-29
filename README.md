# Word Processor Application

This project is a simple word processor that allows users to create, save, and open text files with encryption. It requires a password to access encrypted files, ensuring that your data remains secure.

## Features

- Create and edit text documents.
- Save documents with encryption.
- Open encrypted documents with a password.
- User-friendly graphical interface.

## Project Structure

```
word-processor-app
├── src
│   ├── main.py          # Entry point of the application
│   ├── encryption.py    # Functions for encrypting and decrypting text
│   ├── ui.py           # User interface components
│   └── utils.py        # Utility functions for file handling and validation
├── requirements.txt     # List of dependencies
└── README.md            # Project documentation
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd word-processor-app
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```
   python src/main.py
   ```

2. Use the graphical interface to create or open text documents.
3. When saving a document, you will be prompted to set a password for encryption.
4. To open an encrypted document, enter the correct password when prompted.

## Contributing

Feel free to submit issues or pull requests for improvements or bug fixes. 

## License

This project is licensed under the MIT License.
