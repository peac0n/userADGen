![Supported Python versions](https://img.shields.io/badge/python-3.10+-blue.svg)

🚩 This is the open source repository of userADGen maintained by passionate Chill Guy :dizzy:
# userADGen - The Username AD Generator Tool
[![CircleCI](https://circleci.com/gh/ropnop/kerbrute.svg?style=svg)](https://circleci.com/gh/ropnop/kerbrute)

This project was initially created in 2024 by [@peac0n](https://github.com/peac0n).

#### A Python-powered Active Directory username generator that crafts all possible naming combos in a snap. :zap:


# Installation in Linux
#### Clone this repository and ensure you have Python 3 installed.
```
git clone https://github.com/peac0n/userADGen.git
cd userADGen
```


# Usage Example
```
./userADGen --firstname "Ahmed" --lastname "Alamri" --outfile usernames.txt
```
 * `--firstname` and `--lastname` are required.
 * `--outfile` is optional. If provided, results are written directly to the file without printing them to the screen.
 * This command generates all possible AD-style usernames for "Ahmed Alamri" and saves them in `usernames.txt`.


# For Help:
```
./userADGen --help
```
