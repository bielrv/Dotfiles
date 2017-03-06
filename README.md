# My dotfiles

Install the fonts for the vim configs to work well: tm
https://github.com/powerline/fonts

Install Terminator

Then configure Terminator to use Liberation Mono for Powerline. Use Regular style and Size 10.

To unset <Super>+t shortcut that pops the trash in ubuntu on Mac
sudo apt-get install compizconfig-settings-manager
Run CompizConfig, go to ubuntu Unity Plugin and change the Key to show the Dash, Launcher and Help Overlay from <Super>
to something like <Alt><Super>

# For sublime settings geared towards python development:
(Reference [here](https://github.com/mjhea0/sublime-setup-for-python))

1. Install package control: copy the Python code for Sublime Text 3 found [here](https://sublime.wbond.net/installation#st3). Click **View > Show** Console to open the ST3 console. Paste the code into the console. Press enter. Reboot ST3.

2. You can now install packages by using the keyboard shortcut **cmd+shift+P**. Start typing install until Package Control: Install Package appears. Press enter and search for available packages.

3. For language specific settings click **Sublime Text > Preferences > Settings – More > Syntax Specific – User**. Then save the file using the following format: **LANGUAGE.sublime-settings**. So, for Python-specific settings, save the file as Python.sublime-settings.

