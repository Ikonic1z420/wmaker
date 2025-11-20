Here’s the README file written in English for your Python program:

---

# Generate Hex Numbers

This program generates random hexadecimal values within a specified bit range using an input key and the SHA-256 algorithm. The hexadecimal values are displayed in a tabular format along with their respective ranges.

## Features

- Generate random hexadecimal values.
- Use an input key to ensure uniqueness of results.
- Display the values in a table format, including index, hexadecimal value, and a specific range.

## Installation and Setup

To use this program, ensure that Python (version 3 or higher) is installed on your system. Then follow these steps:

1. Download the program and save it in a file with a `wmaker.py` extension.
2. Navigate to the folder where the file is saved using your terminal or command prompt.
3. Run the program using the following command:

    ```bash
    python wmaker.py
    ```

If you use the repository's JavaScript tooling (linting, formatting), Node.js and npm are also required.

Node/npm quick start:

```powershell
Set-Location 'C:\Users\thekilldro\warpwallet_cracker\wmaker'
npm install
npm run lint       # Check JS/TS files with ESLint
npm run lint:fix   # Auto-fix fixable lint issues
```

## Usage

When you run the program, follow these steps:

1. **Enter Start BitRange:** First, input an integer for the starting bit range.
2. **Enter End BitRange:** Then, input an integer for the ending bit range.
3. **Enter Key:** Finally, enter a passphrase (key) that will be used to generate the hexadecimal values.

For example:

```
Enter Start BitRange : 65
Enter End BitRange : 70
Enter Phrase pass : satoshi

```

## Sample Output

The program will generate a table of hexadecimal values based on the valid input:

```
BitRng  Hex Value                 Start Range                    End Range
------------------------------------------------------------------------------------------------
65      1fce64699293df698         10000000000000000              20000000000000000
66      2436855addf38335a         20000000000000000              40000000000000000
67      5b683f7a104779363         40000000000000000              80000000000000000
68      8085ff390a3cddf0f         80000000000000000              100000000000000000
69      1a411b232a131fdbb0        100000000000000000             200000000000000000
70      33d1ddd42fcfc0fa29        200000000000000000             400000000000000000      
```

## Troubleshooting

- **Error:** If you encounter any issues, make sure your input values are valid and logical.
- The program may show errors for invalid inputs.

## Help and Support

For any questions or assistance, feel free to contact me:

### Developer Information
- **Name:** Amin Solhi
- **Email:** [amin.solhi@gmail.com](mailto:amin.solhi@gmail.com)
- **Phone:** +989111842779
---

