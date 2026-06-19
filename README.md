The program is written in the powerful Python language and its main task is perspective cutting.<br><br>
### How to use:
- To use the required module and libraries, including Tkinter, numpy, PIL, install using the following command
```BASH
pip install tkinter numpy pil
```

- Then run or debug the script through programming editors such as VSCode.

- For use in the Windows environment, the [exe] output is also taken through [pyinstaller].

### Steps to get exe output through pyinstaller:
1. Install [pyinstaller] using the following command 
```BASH
pip install pyinstaller
```

2. Go to the project folder and by pressing the [Shift] key and then [right-clicking] from the opened menu, click the [Open PowerShell window here] option to open the Powershell window and execute the following command.
```BASH
pyinstaller --onefile --noconsole -i "icon.ico" app.py
```

3. The exe output is created in the [dist] folder

**Note**: If an error "pyinstaller : The term 'pyinstaller' is not recognized..." is displayed when executing the above command, Add the folder path [Scripts] to [Path].<br>
Default path: C:\Users\[UserName]\AppData\Local\Packages\[PythonSoftwareFoundation...]\LocalCache\local-packages\Python310\Scripts

### Thank you
