# Minimum Operations

![Project Badge](https://img.shields.io/badge/Minimum%20Operations-Novice-brightgreen)

**By**: Carrie Ybay, Software Engineer at Holberton School  
**Weight**: 1  
**Your score will be updated as you progress.**  
**Project Start**: Sep 1, 2024 1:00 AM  
**Project End**: Sep 15, 2024 12:59 AM  

## Requirements

### General
- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 14.04 LTS using python3 (version 3.4.3)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should be documented
- Your code should use the PEP 8 style (version 1.7.x)
- All your files must be executable

## Tasks

### 0. Minimum Operations

**Mandatory**

In a text file, there is a single character `H`. Your text editor can execute only two operations in this file: Copy All and Paste. Given a number `n`, write a method that calculates the fewest number of operations needed to result in exactly `n` `H` characters in the file.

**Prototype**: `def minOperations(n):`  
**Returns**: an integer  
If `n` is impossible to achieve, return `0`.

**Example**:

```python
n = 9

H => Copy All => Paste => HH => Paste => HHH => Copy All => Paste => HHHHHH => Paste => HHHHHHHHH

Number of operations: 6
```

**Testing Script**: `0-main.py`

```python
#!/usr/bin/python3
"""
Main file for testing
"""

minOperations = __import__('0-minoperations').minOperations

n = 4
print("Min # of operations to reach {} char: {}".format(n, minOperations(n)))

n = 12
print("Min # of operations to reach {} char: {}".format(n, minOperations(n)))
```

**Output**:

```sh
Min number of operations to reach 4 characters: 4
Min number of operations to reach 12 characters: 7
```

## Repository

- **GitHub repository**: [alu-interview](https://github.com/obure1always/alu-interview)
- **Directory**: `minimum_operations`
- **File**: `0-minoperations.py`
