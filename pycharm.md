# Using Pycharm with WSL
## Adding a package in edit mode

1. Activate the venv
2. Install the package using pip with the -e option

```
pip install -e  <folder/to/your/library>
```
3. In Pycharm go to File>Settings> Project Interpreter. In the selection window above scroll down and click on "Show all". All the available venv should appear
4. Click on the venv were the library is istalled. Then click on the small icon with the folders above "Show interpreter paths"
5. Make sure that the folder `<folder/to/your/library>` is in the intepreter path. Add it if not and click on the "Reload List paths" icon above.
Now, the changes in the files of `<folder/to/your/library>` will be reflected every time the environment is used.

