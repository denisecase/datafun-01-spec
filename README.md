# Specification for Project 1 Python Module

## Overview

This is the first in a series of modules focusing on developing Python skills for data analysis. 
This module is designed to introduce basic Python data types and concepts.

## Deliverable Names

- GitHub Repository:  datafun-01-attr
- Documentation:      README.md
- Script:             yourname_attr.py

Create a new GitHub repository with a default README.md. 
In your GitHub repository, create new file with the name listed above.
You are always welcome to use a pseudonym or brand name instead of your actual name.
It should be pretty unique and consistent across all projects.

## Module Specification

### Objective

Create a Python module to encapsulate general information attributes that demonstrate basic programming concepts and data types. 
The module should be designed for easy import and reuse in future projects.

### Requirements

#### 1. Analyst and Course Information

Include private variables for the analyst's name (str), total number of courses taken (int), experience status (boolean), and hours invested in learning (float). 
Follow Python convention to indicate private variables with a leading underscore.
For example:

```python
_name
_course_count
_is_experienced
_hours_invested
```

#### 2. String Formatting

Use f-strings strings to create useful output strings containing the variables above. For example:

```python
my_name_string
course_count_string
is_experienced_string
hours_invested_string
```

#### 3. Math and Statistics

Provide a list of numbers to demonstrate statistical functions. 
Include examples of basic mathematical operations and integrate basic statistical calculations using Python's built-in math and statistics libraries. 
For example:

```python
_numbers
_radius_area
_my_stats
```

Create corresponding f-strings for outputs. 
For example:

```python
numbers_string
radius_area_string
my_stats_string
```

#### 4. Main Function

Implement a `main()` function to display all  required information and calculations.
Include a docstring describing its purpose. For example:

```python
def main():
    ''' Display all output'''
    print(my_name_string)
    print(course_count_string)
    print(is_experienced_string)
    print(hours_invested_string)
    print(numbers_string)
    print(radius_area_string)
    print(my_stats_string)
```

### Conditional Script Execution

Ensure the main function only executes when the script is run directly,
not when imported as a module by using standard boilerplate code.
For example:

```python
if __name__ == '__main__':
    main()
```

### Module Design

Keep the code simple and understandable, focusing on basic Python features.
Add additional notes and experiments as you like.
Include a docstring at the top of the file describing its purpose. For example:

```python
''' This module demonstrates basic Python data types and features. '''
```

### Evaluation Criteria

- Functionality: The project should be functional and meet all requirements.
- Documentation: The project should be well-written and well-documented.
- Presentation: The project should be presented in a clear and organized manner.
- Professionalism: The project should be submitted on-time and reflect an original, creative effort.

See rubric for additional information.
