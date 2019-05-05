# Python PIP

## What is PIP?

PIP is a package manager for Python packages, or modules if you like.
```*Note:* If you have Python version 3.4 or later, PIP is included by default```

## What is a Package?
A package contains all the files you need for a module.

Modules are Python code libraries you can include in your project.

## Check if PIP is Installed
Navigate your command line (Windows, Linux or MacOS) to the location of Python's script directory, and type the following:

Check PIP version:
```C:\Users\Your Name\AppData\Local\Programs\Python\Python36-32\Scripts>pip --version```

### Example:
Type:
```pip --version```

Returns:
```pip 19.0.3 from c:\users\jaquiel\appdata\local\programs\python\python37-32\lib\site-packages\pip (python 3.7)```

## Install PIP
If you do not have PIP installed, you can download and install it from this page: https://pypi.org/project/pip/ .

## Download a Package

Downloading a package is very easy.

Open the command line interface and tell PIP to download the package you want.

Navigate your command line to the location of Python's script directory, and type the following:

### Examples:
Type:
```C:\Users\Your Name\AppData\Local\Programs\Python\Python36-32\Scripts>pip install camelcase```

Result:
```pip install camelcase
Collecting camelcase
  Downloading https://files.pythonhosted.org/packages/24/54/6bc20bf371c1c78193e2e4179097a7b779e56f420d0da41222a3b7d87890/camelcase-0.2.tar.gz
Installing collected packages: camelcase
  Running setup.py install for camelcase ... done
Successfully installed camelcase-0.2
You are using pip version 19.0.3, however version 19.1 is available.
You should consider upgrading via the 'python -m pip install --upgrade pip' command.
```

## Using a Package

Once the package is installed, it is ready to use.

Import the "camelcase" package into your project.

### Examples
Import and use "camelcase":
```
import camelcase

c = camelcase.CamelCase()

txt = "hello world"

print(c.hump(txt))
```

## Finding Packages
Find more packages at https://pypi.org/. [Click here](https://pypi.org/)

## Remove a Package
Use the *uninstall* command to remove a package:

###Examples: 
Uninstall the package named "camelcase"

example 1
```C:\Users\Your Name\AppData\Local\Programs\Python\Python36-32\Scripts>pip uninstall camelcase```

The PIP Package Manager will ask you to confirm that you want to remove the camelcase package:
```
Uninstalling camelcase-02.1:
  Would remove:
    c:\users\Your Name\appdata\local\programs\python\python36-32\lib\site-packages\camecase-0.2-py3.6.egg-info
    c:\users\Your Name\appdata\local\programs\python\python36-32\lib\site-packages\camecase\*
Proceed (y/n)?```
Press y and the package will be removed.
```

example 2
```pip uninstall camelcase```

The PIP Package Manager will ask you to confirm that you want to remove the camelcase package:

```
Uninstalling camelcase-0.2:
  Would remove:
    c:\users\jaquiel\appdata\local\programs\python\python37-32\lib\site-packages\camelcase-0.2-py3.7.egg-info
    c:\users\jaquiel\appdata\local\programs\python\python37-32\lib\site-packages\camelcase\*
Proceed (y/n)? y
  Successfully uninstalled camelcase-0.2
```

## List Packages

Use the list command to *list* all the packages installed on your system:

### Example
List installed packages:
```pip list```

Result:
```Package         Version
-----------------------
camelcase       0.2
mysql-connector 2.1.6
pip             18.1
pymongo         3.6.1
setuptools      39.0.1
```


