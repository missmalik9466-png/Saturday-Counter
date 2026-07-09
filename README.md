# Saturday Counter

## Description

Saturday Counter is a Python command-line application that calculates the total number of Saturdays in a given year. The program determines the number of days in each month, accounts for leap years, and uses Python's built-in `datetime` module to identify Saturdays.

This project is suitable for beginners who want to learn about date handling, leap year calculations, loops, conditional statements, and the `datetime` module.

---

## Features

* Accept a year as input
* Detect leap years automatically
* Calculate the correct number of days in each month
* Identify Saturdays using the `datetime` module
* Display the total number of Saturdays in the selected year
* Simple command-line interface

---

## Technologies Used

* Python 3
* Python `datetime` module
* Command Line Interface (CLI)

---

## Project Structure

```text
Saturday-Counter/
│
├── saturday_counter.py
└── README.md
```

---

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Saturday-Counter.git
```

2. Navigate to the project directory.

```bash
cd Saturday-Counter
```

3. Run the program.

```bash
python saturday_counter.py
```

---

## Example

### Input

```text
Enter year: 2026
```

### Output

```text
Number of Saturdays = 52
```

---

## How It Works

1. The user enters a year.
2. The program determines the number of days in each month.
3. Leap year rules are applied for February.
4. Every date in the year is checked using the `datetime` module.
5. Each Saturday is counted.
6. The final total is displayed.

---

## Learning Objectives

This project demonstrates:

* Python loops
* Conditional statements
* Leap year calculation
* Date and time handling
* Working with the `datetime` module
* Calendar-based programming
* Command-line application development

---

## Future Improvements

* Count any weekday selected by the user
* Display the dates of all Saturdays
* Count weekends (Saturday and Sunday)
* Generate a yearly calendar
* Export results to a text or CSV file
* Create a graphical user interface (GUI)

---

## License

This project is open-source and intended for educational and learning purposes.

