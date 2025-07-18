# Online Voting System

This is a simple **Online Voting System** built using Python's `Tkinter` library for the graphical user interface (GUI). The system allows registered voters to log in, verify their identity using OTP, select their state and political party, and cast their vote. The results are stored in an Excel file for further analysis.

## Features

1. **Login**: Voters can log in with their Aadhar number and Voter ID.
2. **OTP Verification**: After logging in, an OTP is generated and sent (simulated with a print statement), and the user must enter the OTP to proceed.
3. **State Selection**: Voters can select their state from a dropdown menu.
4. **Political Parties**: Based on the selected state, the available political parties are displayed.
5. **Vote Submission**: After selecting a political party, the voter can submit their vote.
6. **Vote Results**: The vote results are saved in an Excel file, and the voting status is updated.

## Requirements

To run this project, you will need the following Python libraries:

- `tkinter` (for the GUI)
- `pandas` (for handling data and saving vote results in Excel format)
- `random` (for OTP generation)

You can install the necessary libraries using `pip`:

```bash
pip install pandas openpyxl
