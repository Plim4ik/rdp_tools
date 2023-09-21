# rdp_tools

This directory contains the following files:

- `Firefox Installer.exe` - Firefox web browser installer.
- `Git-2.42.0.2-64-bit.exe` - Git version control system installer.
- `README.md` - This README file providing information about the contents of the directory.
- `VSCodeUserSetup-x64-1.82.2.exe` - Visual Studio Code editor installer.
- `geckodriver-v0.33.0-win64.zip` - Geckodriver, which is needed to work with Firefox in automated tests. Please extract the contents of this archive and place it in the Python installation directory. By default, the Python installation directory is `C:\Users\<your_username>\AppData\Local\Programs\Python\<Python_version>\`.
- `python-3.11.5-amd64.exe` - Python programming language installer.
- `putty-64bit-0.79-installer.msi` - PuTTY SSH and Telnet client installer.

## Additional Recommendations

To enhance your programming experience, you may consider installing the following useful programs and extensions:

- **Visual Studio Code Extensions:**
  - [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python): Provides support for Python development, including linting, debugging, and code formatting.
  - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): Enhances Git integration in Visual Studio Code, showing blame annotations and other Git information.
  - [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner): Allows you to run code snippets directly from VS Code.
  - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Automatically formats code to adhere to a consistent style.
  - [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer): Helps visually distinguish matching sets of parentheses, brackets, and braces.
  
- **Other Useful Tools:**
  - [Git](https://git-scm.com/): A distributed version control system.
  - [Firefox](https://www.mozilla.org/firefox/): A fast and secure web browser.
  - [Geckodriver](https://github.com/mozilla/geckodriver): A WebDriver for Firefox, useful for automating browser testing.
  
Feel free to explore and utilize these tools and extensions to enhance your productivity and development experience.

## Installation Notes

- To use Geckodriver, please follow these steps:
  1. Open the `geckodriver-v0.33.0-win64.zip` archive.
  2. Select all files inside the archive.
  3. Right-click on the selected files and choose "Extract All".
  4. Specify the path where you want to extract the files (e.g., ``C:\Users\<your_username>\AppData\Local\Programs\Python\<Python_version>\geckodriver.exe`).
  
- Adding the path to Geckodriver to the `PATH` environment variable on Windows allows you to run it from any directory in the command prompt or from other programs without specifying the full path.

  1. Open "System Properties" through the Start menu or by searching in the Start menu.
  2. In the "System Properties" window, select the "Advanced" tab.
  3. Click on the "Environment Variables..." button.
  4. In the "User variables" section, find the `PATH` environment variable and select it.
  5. Click on the "Edit..." button.
  6. Click on the "New" button and enter the path to the extracted Geckodriver (e.g., ``C:\Users\<your_username>\AppData\Local\Programs\Python\<Python_version>\geckodriver.exe`).
  7. Click "OK" in all open windows to save the changes.

Now you will be able to use Geckodriver from any directory without specifying the full path to it.