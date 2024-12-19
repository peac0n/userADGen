# userADGen
A Python-powered AD username generator that crafts all possible naming combos in a snap. ⚜

userADGen is a Python-powered Active Directory username generator that can whip up a storm of user name combinations at your command. It handles uppercase and lowercase variations, multiple separators, truncation to fit AD constraints, and outputs them cleanly to your terminal or a file.

### Features
#### Multiple Formats: Generate usernames with dots, dashes, underscores, or no separator at all.
#### Case Variations: Automatically mixes uppercase and lowercase combos.
#### Quick & Efficient: Instantly get a hefty list of potential AD-compliant usernames from a single first and last name input.
#### Custom Output: Save all results to a file for easy integration into your workflows.

### Installation
#### Clone this repository and ensure you have Python 3 installed.
git clone https://github.com/<your-username>/userADGen.git
cd userADGen

### Usage
./userADGen --firstname "Ahmed" --lastname "Alamri" --outfile results.txt

#### --firstname and --lastname are required.
#### --outfile is optional. If provided, results are written directly to the file without printing them to the screen.

### For help:
./userADGen --help

### Example
./userADGen --firstname "Ahmed" --lastname "Alamri" --outfile usernames.txt
#### This command generates all possible AD-style usernames for "Ahmed Alamri" and saves them in usernames.txt.
