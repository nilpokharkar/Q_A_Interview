1. What is a list comprehension?
- List comprehension in Python is a concise and expressive way to create lists from existing iterables, such as lists, tuples, sets, or even strings. It provides a shorthand way to generate a new list by applying an expression or transformation to each element of an existing iterable.
- Here is a basic syntax for a list comprehension:
- new_list = [expression for item in iterable if condition]
- eg: # Create a list of squares of even numbers from 0 to 9
        original_list = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
        new_list = [x**2 for x in original_list if x % 2 == 0]

        print(new_list) # Output: [0, 4, 16, 36, 64]

2. Package Managers:
- Package managers in Python are tools that simplify the installation, upgrading, and removal of software packages or libraries for the Python programming language. 
- There are several package managers available for Python, including the following: pip, conda, easy_install, Anaconda.

3. What is pyenv?
- pyenv is a popular open-source tool for managing multiple Python versions on a single machine. 
- It allows developers to easily install and switch between different versions of Python, and it can be especially useful for testing applications on different Python versions or working on projects that require specific Python versions.
- Here are some common commands used with pyenv:
  pyenv install <version> - installs a specific version of Python
  pyenv uninstall <version> - uninstalls a specific version of Python
  pyenv versions - lists all installed Python versions
  pyenv global <version> - sets the global Python version for your system
  pyenv local <version> - sets the Python version for a specific project directory
  
 4. 


  

