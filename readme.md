
# Vs code  profile 

vs code  profile suted for node js development and custom css and script for with round cornor and cented commant palllet 

inspired by https://github.com/nursandiid/vscode-customizations

## prerequisite

## Windows users

**In Windows, make sure you run your Visual Studio Code in Administrator mode before enabling or disabling your custom style!**

## Mac and Linux users
**The extension would NOT work if Visual Studio Code cannot modify itself.** The cases include:

- Code files being read-only, like on a read-only file system or,
- Code is not started with the permissions to modify itself.

**You need to claim ownership on Visual Studio Code's installation directory, by running this command**:

```sh
sudo chown -R $(whoami) "$(which code)"
sudo chown -R $(whoami) /usr/share/code
```

### Instructions:

1. **Imports profile**
   - Imports profile use it.

2. **Modify `settings.json`**
   - Add the configuration below to your VS Code `settings.json` file. **Make sure to back up your current settings** as this may overwrite them.

3. **Add the following configuration**:

    ```jsonc
    "vscode_custom_css.imports": [
        // Absolute file paths for your custom CSS/JS files
        // For Mac or Linux:
        // "file:///Users/[your-username]/[path-of-custom-css]/vscode-custom/style.css",
        // "file:///Users/[your-username]/[path-of-custom-css]/vscode-custom/script.js"

        // For Windows:
        // "file:///C:/[path-of-custom-css]/vscode-custom/style.css",
        // "file:///C:/[path-of-custom-css]/vscode-custom/script.js"
    ]
    ```

4. **Enable "Custom CSS and JS Loader"**
   - Open the command palette (`Ctrl+Shift+P` or `Cmd+Shift+P`) and type **"Enable Custom CSS and JS"** to activate the customizations.

5. **Customize Your CSS or JS**
   - Modify the CSS or JS files to change the appearance of Visual Studio Code to your liking. Explore different areas of VS Code that you want to customize.

6. **Reload the Extension**
   - After making any changes to your CSS or JS files, reload the extension from the command palette by selecting **"Reload Custom CSS and JS"**.




