# Morse Package

Python package for converting text to Morse code and vice versa.

## Installation

You can install the `morse-package` from PyPI using pip:

```bash
pip install morse-package
```
# Usage
## Converting Text to Morse Code
```bash
from morse.Morse import Morse

m = Morse()

text = "Hello, World!"
morse_code = m.to_morse(text)
print(f"Text '{text}' in Morse code: {morse_code}")
```
## Converting Morse code to Text
```bash
from morse import Morse

m = Morse()

morse_code = ".... . .-.. .-.. --- --..-- / .-- --- .-. .-.. -.. -.-.--"
text = m.to_string(morse_code)
print(f"Morse code '{morse_code}' decoded to text: {text}")
```
## Getting Morse code dictionary
```bash
from morse import Morse

m = Morse()

codes_dict = m.get_morse_codes()
print("Morse code dictionary:")
for key, value in codes_dict.items():
    print(f"{key}: {value}")
```
# License
This project is licensed under the MIT <a href="LICENSE">License</a>. See the LICENSE file for details.
# Contributing
Contributions are welcome! Feel free to open issues or pull requests on the <a href="https://github.com/rahulaauji-30/morse.git">GitHub repository</a>.
# Support
For support or questions, please contact <a href="mailto:rahulaauji71@gmail.com">Rahul Parihar</a>