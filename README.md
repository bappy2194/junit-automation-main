# Junit Automation Project

## Overview

The [Digital Unite Practice Webform](https://www.digitalunite.com/practice-webform-learners) web form submission process is automated by this Junit WebDriver project. The test submits the form, uploads a file up to 2 MB in size, and verifies the success message.

## Prerequisites

- Java
- ChromeDriver

## Getting Started

1. **Clone the repository:**

    ```bash
    git clone(https://github.com/bappy2194/junit-automation-main)
    ```

2. **Set the path to your ChromeDriver executable in `FormSubmissionTest.java`.**

3. **Run the tests:**

    ```bash
    ./gradlew clean test
    ```

## Test Execution

The test performs the following steps:

1. Fills in the form fields.
2. Uploads a file.
3. Submits the form.
4. Asserts the success message.

## Test Report
![Screenshot_1 - Copy](https://github.com/bappy2194/junit-automation-main/assets/160812376/8a1603d1-c563-4970-ad53-19e1d025690f)

## Contributing
Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.


