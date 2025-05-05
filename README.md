# File Renaming Tool

## Introduction

The **File Renaming Tool** is a tool to conveniently edit single or multiple filenames in a given directory. It uses PyQt5 a graphical user interface to provide users with a simplistic and intuitive user experience.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [License](#license)

## Installation

1. Clone the repository:

```powershell
git clone https://github.com/klaus-001/file-renaming-tool.git
```

2. Install dependencies:

```powershell
pip install PyQt5
```

## Usage

To run the program, execute the following command in your terminal:

```powershell
python main.py
```

## Features
- Unstaged Area
- Staged Area
- Filter Option
- Edit Option
- Single or Multiple Filenames Edit

#### Unstaged Area

The unstaged area is where all the files are listed after loading the selected directory.

#### Staged Area

The staged area is where the selected files that is to be edited by user is listed.

#### Filter Option

The user is able to filter only the required files and place directly into the staged area using regular expression or by doing a direct search of the filename.

#### Edit Option

The user has the ability to choose from `Add Prefix`, `Remove Prefix`, `Add Suffix`, `Remove Suffix`, and `Rename` option to edit the files.

#### Single or Multiple Filenames Edit

The user has the option to edit a single file or multiple files simultaneously.

## License

This project is distributed under the MIT License. See [LICENSE](LICENSE.md) for more details.
