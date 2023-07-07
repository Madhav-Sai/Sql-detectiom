
```markdown
# SQL Injection - User Password Extraction

![SQL Injection]

## Overview

The SQL Injection script is a Python script that performs SQL injection attacks to extract password hashes from a vulnerable website. It exploits SQL injection vulnerabilities to bypass authentication and retrieve the password hashes stored in the website's database. The script utilizes boolean-based blind SQL injection techniques to extract the password hashes character by character.

## Requirements

- Python 3.x
- Requests library

## Installation

1. Clone the repository:

```shell
git clone https://github.com/Madhav-Sai/Sql-detection.git
```

2. Navigate to the project directory:

```shell
cd sql-injection
```

3. Install the required libraries:

```shell
pip install requests
```

## Usage

1. Update the script:

   - Set the `target` variable to the URL of the target vulnerable website.
   - Adjust the `charset` variable to match the characters used in the password hash.
   - Modify the `needle` variable to match the expected response indicating a successful login.

2. Run the script:

```shell
python sql_injection.py
```

3. Enter the user ID when prompted:

   - Enter the ID of the user for which you want to extract the password hash.

4. Review the results:

   - The script will attempt to extract the password hash for the specified user ID.
   - It will display the length of the password hash and the total number of queries made during the extraction process.

## Important Note

**Please ensure that you have proper authorization and permission before performing any SQL injection tests. Unauthorized SQL injection attacks are illegal and unethical. Use this script responsibly and only on systems you are authorized to test.**


