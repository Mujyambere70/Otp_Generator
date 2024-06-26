# OTP Generator

## Description
The OTP Generator project provides a secure solution for generating One-Time Passwords (OTPs) crucial for authentication purposes. By creating random and secure codes, it significantly enhances security across various applications, offering a robust defense against interception and unauthorized access.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

## Installation
To install the OTP generator, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Mujyambere70/Otp_Generator.git
    ```

2. Navigate to the project directory:
    ```bash
    cd otp-generator
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To utilize the OTP generator, execute the `main.py` script as follows:

```bash
python main.py
```

Different types of OTPs can be generated by invoking the respective methods:

- `Otp(10).digits` for numeric OTPs
- `Otp(10).bd_digits` for alphanumeric OTPs with uppercase letters
- `Otp(10).sd_digits` for alphanumeric OTPs with lowercase letters
- `Otp(10).sbd_digits` for alphanumeric OTPs with both uppercase and lowercase letters

Include screenshots of the output here if possible.

## Credits
Developed by [Mujyambere Jean Michel](https://github.com/Mujyambere70). Special thanks to contributors who have helped with the project.
