# vscode-settings.json
A simple repo to share my favorite settings for Visual Studio Code

To change settings in Visual Studio Code, follow these steps:

1. Open Visual Studio Code.
2. Go to the File menu and select Preferences, or use the keyboard shortcut Ctrl + , (comma).
3. In the Preferences window, select the Settings tab on the left side.
4. You can search for specific settings using the search bar at the top, or you can click on the various categories on the left to browse through the available options.
5. To change a setting, simply click on its toggle switch or value field and make the desired changes.

Alternatively, you can also access the Settings editor directly by using the keyboard shortcut Ctrl + Shift + P to open the Command Palette, then typing "Settings" and selecting the "Preferences: Open User Settings" option. This will open the Settings editor in a new tab, where you can make changes in the same way as described above.

It's also worth noting that you can customize settings on a per-project basis by creating a `.vscode` directory in your project and adding a `settings.json` file to it. This allows you to specify settings that will only apply to that specific project.

## What is settings.json ?
The `settings.json` file in Visual Studio Code allows users to customize various aspects of the editor, such as keybindings, color themes, and font sizes. This file is stored in the user's local workspace, which means that the settings are specific to each user and each workspace. For example, you can use the settings.json file to customize the editor's appearance and behavior to better suit your personal preferences or the specific needs of a project.

## Disclaimer
There is no "best" set of settings for the `settings.json` file in Visual Studio Code, as the ideal settings will depend on the individual user's preferences and the specific needs of their projects. However, here are some settings that many users find useful:

- "editor.fontSize": 14 // This sets the default font size for the editor windows. You can adjust this value to suit your personal preferences.
- "editor.fontFamily": "Monaco" // This sets the default font family for the editor windows. You can choose any font that is installed on your system.
- "editor.lineNumbers": true // This enables line numbers in the editor, which can be helpful for navigating and debugging your code.
"editor.tabSize": 4 // This sets the default tab size to 4 spaces, which is a common convention in many programming languages.
- "workbench.colorTheme": "One Dark Pro" // This sets the color theme for the editor to "One Dark Pro", which is a popular choice among many developers.
- "editor.wordWrap": "on" // This enables word wrapping in the editor, which can make it easier to read long lines of text.
- "editor.autoClosingBrackets": "always" // This enables automatic closing of brackets and quotes, which can save you time and reduce the chance of syntax errors in your code.

Again, these are just some examples of settings that you may find useful. You can customize the settings.json file in Visual Studio Code to suit your personal preferences and the needs of your projects.

## Contribution
If you have any ideas for how we could improve the `settings.json` file in Visual Studio Code, please don't hesitate to send us a message. We're always looking for ways to make the editor more customizable and user-friendly.