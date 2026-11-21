#Python-IDE-Projects-for-Acode
**Title:** A modified version of Acode’s Python plugin, adding support for running multi-file projects and importing local modules and nested packages with Pyodide,
 download The plugin "plugin.zip"     


**How to use**

1. Open your Python project folder in Acode.
2. Open the Python file you want to run and save your changes.
3. Tap the **Run** button.
4. The plugin synchronizes the project’s Python files, so the running file can import sibling modules and nested packages using normal Python imports.

For example, use `import package.module` for a module inside a package. The project files must be inside the active folder.