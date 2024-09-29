# Ransomware Project

![License](https://img.shields.io/badge/license-MIT-green.svg)

## Overview
This project serves as an *educational demonstration* of ransomware behavior, showcasing the process of encrypting and decrypting files. Its purpose is to educate about the risks associated with ransomware attacks and to promote better cybersecurity practices.

### Important: 
*This project is for educational purposes only. It should not be used for illegal activities or malicious intent.*

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [License](#license)
- [Disclaimer](#disclaimer)
- [Contributing](#contributing)
- [Contact](#contact)

## Features
- *File Encryption*: Securely encrypt files in a specified directory using AES encryption.
- *File Decryption*: Decrypt files that have been encrypted with the corresponding key.
- *Ransom Note Display*: Notify users of the encryption and provide instructions on how to obtain the decryption key.

## Installation
For detailed installation instructions, please see [INSTALL.md](INSTALL.md).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Decrypting Files
To decrypt files that have been previously encrypted, you can use the decryption functionality within the same src/ransomware.py script. Ensure you have the correct encryption key.
1. Open the src/ransomware.py script in a text editor.
2. Ensure you have the correct encryption key that was generated during the encryption process.
3. Run the decryption command (you may need to implement the decryption functionality within the same script):
## bash  
 python src/ransomware.py decrypt --key your_encryption_key
 
 Replace your_encryption_key with the actual key you received after encryption.



## Disclaimer
This project is intended solely for educational purposes to raise awareness about ransomware threats. *Do not use this code for any illegal activities*. The creators are not liable for any misuse or damages caused by this code.

## Contributing
Contributions are welcome! If you have suggestions for improvements or features, please open an issue or submit a pull request. Ensure your contributions align with the educational intent of this project.

## Contact
For questions, feedback, or suggestions, please contact:
- *Your Name* - [your.email@example.com](mailto:your.email@example.com)
- *GitHub Profile*: [profile](https://github.com/MABDULAHAD-HUB)

---

Thank you for visiting this project! Stay safe and secure online.
