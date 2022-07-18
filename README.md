# Python for Beginners

Clayton Mercer

## Installation

- Windows

  Download directly from [python.org](https://www.python.org/downloads/)

  Check installation with

  ```
  python3 --version
  ```

- MacOS/Linux

  ```
  brew install python3
  ```

  Check installation with

  ```
  python3 --version
  ```

## Setting up Environment

- Windows

  ```
  py -3 -m venv .venv

  .venv\scripts\activate
  ```

  If the activate command generates the message "Activate.ps1 is not digitally signed. You cannot run this script on the current system.",
  then you need to temporarily change the PowerShell execution policy to allow scripts to run.

  ```
  Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
  ```

- MacOS/Linux

  ```
  python3 -m venv .venv

  source .venv/bin/activate
  ```

## Setting up the package installer

- Install `pip`

        ```
        python3 -m pip install --upgrade pip
        ```

## Downloading packages: `matplotlib`

- Windows (may require elevation)

  ```
  python -m pip install matplotlib
  ```

- macOS

  ```
  python3 -m pip install matplotlib
  ```
