[![Actions Status](https://github.com/zluuba/python-project-50/workflows/hexlet-check/badge.svg)](https://github.com/zluuba/python-project-50/actions) 
[![Python CI](https://github.com/zluuba/python-project-50/actions/workflows/pyci.yml/badge.svg)](https://github.com/zluuba/python-project-50/actions/workflows/pyci.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/83963175416f052072a8/maintainability)](https://codeclimate.com/github/zluuba/python-project-50/maintainability) 
[![Test Coverage](https://api.codeclimate.com/v1/badges/83963175416f052072a8/test_coverage)](https://codeclimate.com/github/zluuba/python-project-50/test_coverage)


## Difference generator
Compares two files and outputs the result of the comparison. **Json** and **yaml** formats are supported. </br>
You can also output comparison result in three different views: stylish, plain and json. </br>
Used with the terminal. </br>


### Requirements
- [python](https://www.python.org/), version 3.9 or higher
- [poetry](https://python-poetry.org/), version 1.0.0 or higher
- [pyyaml](https://pyyaml.org/), version 6.0 or higher


### Installation 

Clone this repo or download it with pip:
```ch
pip install --user git+https://github.com/zluuba/python-project-50.git
```

Use these commands to install the package:
```ch
make install
make build
make package-install
```

### Commands
#### Options

```ch
gendiff -h                # print help text
gendiff --help

gendiff -f                # set the gendiff format
gendiff --format          # stylish (default), plain or json
```

### Sample commands
*Compare only .json or .yaml (.yml) files.* </br>

Show the differences between two files with default style **stylish**
([demo](https://github.com/zluuba/python-project-50#nested-files-stylish-format))
```ch
gendiff file1.json file2.json
```

**Plain** style
([demo](https://github.com/zluuba/python-project-50#plain-format))
```ch
gendiff --format plain file1.json file2.json
```

**Json** style
([demo](https://github.com/zluuba/python-project-50#json-format))
```ch
gendiff --format json file1.yml file2.yml
```


### Package examples

#### Flat files (stylish format):
[![asciicast](https://asciinema.org/a/V8EMBZ8dyIeVdGrgz5yOiY7tk.svg)](https://asciinema.org/a/V8EMBZ8dyIeVdGrgz5yOiY7tk)


#### Nested files (stylish format):
[![asciicast](https://asciinema.org/a/arUl8ZVGSi4hzsnaNf0nKwjZL.svg)](https://asciinema.org/a/arUl8ZVGSi4hzsnaNf0nKwjZL)


#### Plain format:
[![asciicast](https://asciinema.org/a/0V1KMW2AuUasLxNQ9ty6E11GO.svg)](https://asciinema.org/a/0V1KMW2AuUasLxNQ9ty6E11GO)


#### Json format:
[![asciicast](https://asciinema.org/a/0kOAC6MbuY8MNGMzFb32oR8bI.svg)](https://asciinema.org/a/0kOAC6MbuY8MNGMzFb32oR8bI)
