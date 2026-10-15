# First_CI_Pipeline

A Python project demonstrating **Continuous Integration (CI)** using GitHub Actions, Python, and pytest. This repository contains Python programs with automated test cases to verify their functionality.

---

## Project Overview

The project covers the following Python programming problems:

- Finding the largest word in a sentence
- Checking whether two strings are anagrams
- Sorting a list without using `sort()` or `sorted()`
- Merging two sorted lists
- Finding the maximum and minimum elements in a list
- Calculating the sum of list elements
- Rotating a list by K positions
- Finding the intersection of two sets
- Checking Armstrong numbers
- Converting a decimal number to binary without using `bin()`

---

## Technologies Used

- **Python** — implementing the programs
- **pytest** — automated testing
- **Git and GitHub** — version control and repository hosting
- **GitHub Actions** — automated testing through CI

---

## Project Structure

```text
First_CI_Pipeline/
├── .github/
│   └── workflows/
│       └── python-ci.yml
├── Codes/
│   ├── largest_word.py
│   ├── anagram_strings.py
│   ├── sort_without_sort.py
│   ├── merge_sorted_lists.py
│   ├── max_min_list.py
│   ├── sum_of_list.py
│   ├── rotate_list.py
│   ├── set_intersection.py
│   ├── armstrong_number.py
│   └── decimal_to_binary.py
├── Test_cases/
│   ├── test_largest_word.py
│   ├── test_anagram_strings.py
│   ├── test_sort_without_sort.py
│   ├── test_merge_sorted_lists.py
│   ├── test_max_min_list.py
│   ├── test_sum_of_list.py
│   ├── test_rotate_list.py
│   ├── test_set_intersection.py
│   ├── test_armstrong_number.py
│   └── test_decimal_to_binary.py
├── .gitignore
├── README.md
└── requirements.txt
```

---

## Setup and Installation

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd First_CI_Pipeline
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your repository's HTTPS URL.

### 2. Create a virtual environment (optional)

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

The `requirements.txt` file should contain:

```text
pytest
```

---

## Running the Programs

Run these commands from the project's root directory in the VS Code terminal.

| No. | Program | Terminal Command |
|-----|---------|------------------|
| 1 | Find the Largest Word | `c:\Raza\First_Cl_Pipeline\Codes\largest_word.py` |
| 2 | Check Anagram Strings | `c:\Raza\First_Cl_Pipeline\Codes\anagram_strings.py` |
| 3 | Sort Without Using `sort()` | `c:\Raza\First_Cl_Pipeline\Codes\sort_without_sort.py` |
| 4 | Merge Two Sorted Lists | `c:\Raza\First_Cl_Pipeline\Codes\merge_sorted_lists.py` |
| 5 | Find Maximum and Minimum | `c:\Raza\First_Cl_Pipeline\Codes\max_min_list.py` |
| 6 | Sum of List Elements | `c:\Raza\First_Cl_Pipeline\Codes\sum_of_list.py` |
| 7 | Rotate a List by K Positions | `c:\Raza\First_Cl_Pipeline\Codes\rotate_list.py` |
| 8 | Find Set Intersection | `c:\Raza\First_Cl_Pipeline\Codes\set_intersection.py` |
| 9 | Check Armstrong Number | `c:\Raza\First_Cl_Pipeline\Codes\armstrong_number.py` |
| 10 | Decimal to Binary Conversion | `c:\Raza\First_Cl_Pipeline\Codes\decimal_to_binary.py` |

---

## Running the Test Cases

Run each test file separately using pytest.

| No. | Test Case | Terminal Command |
|-----|-----------|------------------|
| 1 | Largest Word | `python -m pytest Test_cases\test_largest_word.py` |
| 2 | Anagram Strings | `python -m pytest Test_cases\test_anagram_strings.py` |
| 3 | Sort Without `sort()` | `python -m pytest Test_cases\test_sort_without_sort.py` |
| 4 | Merge Sorted Lists | `python -m pytest Test_cases\test_merge_sorted_lists.py` |
| 5 | Maximum and Minimum | `python -m pytest Test_cases\test_max_min_list.py` |
| 6 | Sum of List Elements | `python -m pytest Test_cases\test_sum_of_list.py` |
| 7 | Rotate a List | `python -m pytest Test_cases\test_rotate_list.py` |
| 8 | Set Intersection | `python -m pytest Test_cases\test_set_intersection.py` |
| 9 | Armstrong Number | `python -m pytest Test_cases\test_armstrong_number.py` |
| 10 | Decimal to Binary | `python -m pytest Test_cases\test_decimal_to_binary.py` |

### Run All Test Cases

```bash
python -m pytest
```

---

## Continuous Integration with GitHub Actions

GitHub Actions automatically runs the test suite when changes are pushed to the repository or a pull request is opened against the configured branch.

The CI workflow:

1. Checks out the repository.
2. Sets up Python.
3. Installs the required dependencies.
4. Runs pytest.
5. Reports whether the tests passed or failed.

To check the result, open your GitHub repository and select the **Actions** tab. A green check indicates that the workflow completed successfully.

---

## Learning Objectives

- Practice Python problem-solving and functions.
- Write automated tests using pytest.
- Organize code and test files into separate folders.
- Use Git and GitHub for version control.
- Understand how a CI pipeline automatically checks code changes.
