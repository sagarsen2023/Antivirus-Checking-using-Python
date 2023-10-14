# Antivirus Checking Program

Antivirus Checking Program is a Python-based tool designed for detecting malware and viruses using an extensive database of hash files. With nearly 20 lakh (2 million) combinations of malware/virus hash files, this program offers a powerful solution for identifying malicious software.

## Features

- **Extensive Database:** Contains a collection of 20 lakh malware/virus hash combinations for accurate detection.
- **Fast and Efficient:** Utilizes optimized algorithms for quick hash matching, ensuring efficient scanning.
- **Easy to Use:** Simple and intuitive command-line interface for easy interaction.
- **Developer-Friendly:** Includes a separate hash file (data_dict.json) containing necessary hash values for developers to work with.

## Prerequisites

- Python 3.x installed on your system.

## How to use

1. **Paste the file name of which you want to check if it contains a harmful file**
   ```sh
   malwareDetection("yourFileName.extension") # Paste your file name here (You'll find it in the last line of the code).
   ```
2. **You will see the output in the console.**

**This is a simple antivirus checking program but it can be used for some advanced type of development.**
1. Developers can create their own antivirus program using this file.
2. It is easier to maintain.
3. Time to time both the data_dict.json and the source code will be updated.
4. Used Python dictionary for faster iteration.

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
