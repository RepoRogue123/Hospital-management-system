# IIT Jodhpur Hospital Management System

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Function Descriptions](#function-descriptions)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
Welcome to the IIT Jodhpur Hospital Management System. This system helps manage patient records, schedule doctor visits, and maintain medical histories in an efficient manner. It's designed to be used by both patients and doctors to streamline hospital operations.

## Features
- **Patient Management**: Create and update patient profiles.
- **Visit Scheduling**: Schedule visits to the hospital and maintain visit records.
- **Doctor Management**: Doctors can access patient records and view scheduled visits.
- **Secure Login**: Separate login for patients and doctors with password protection.
- **Data Storage**: All patient information is securely stored in text files.

## Installation
1. **Clone the Repository**
    ```sh
    git clone https://github.com/RepoRogue123/Hospital-management-system.git
    ```
2. **Navigate to the Project Directory**
    ```sh
    cd .\Hospital-management-system\
    ```
3. **Compile the Program**
    ```sh
    gcc hospital_management_system.c -o hospital_management_system
    ```
4. **Run the Program**
    ```sh
    ./hospital_management_system
    ```

## Usage
### Main Menu
When you run the program, you will be greeted with the main menu:
1. **Patient**
    - New Patient
    - Existing Patient
2. **Doctor**

### Patient Menu
- **New Patient**: Allows new patients to create their profiles.
- **Existing Patient**: Allows existing patients to log in and view/update their profiles, view visit records, and schedule new visits.

### Doctor Menu
- **Patient Record**: View all patient records.
- **Scheduled Visit**: View all scheduled visits.

## Function Descriptions
- **main()**: The entry point of the program. Displays the main menu and handles navigation.
- **patient_menu()**: Displays the patient menu.
- **doctor_menu()**: Displays the doctor menu.
- **newPatient()**: Handles new patient registration.
- **existingPatient()**: Manages existing patient login and subsequent actions.
- **createPatient()**: Creates a new patient profile.
- **searchPatient()**: Searches for a patient in the database.
- **showProfile()**: Displays a patient's profile.
- **updatePatient()**: Updates a patient's profile.
- **scheduleVisit()**: Schedules a visit for a patient.
- **visitRecord()**: Displays a patient's visit records.
- **createDate()**: Generates the current date.
- **createPath()**: Creates a unique file path for patient data.
- **extractText()**: Extracts specific text from a file.
- **extractPD()**: Extracts patient ID from a file.
- **removeBlankLines()**: Removes blank lines from a file.
- **cyan(), red(), blue(), reset()**: Functions for colored output.
- **baseline()**: Prints a baseline of asterisks for UI separation.

