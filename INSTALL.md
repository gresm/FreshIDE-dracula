### [Fresh IDE](https://fresh.flatassembler.net/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/freshide.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/freshide/archive/main.zip) option and unzip them.

#### Activating theme

1. Open Fresh IDE
2. Navigate ``Options -> IDE Options -> Editor Options``;
   ![image](https://github.com/user-attachments/assets/9682cd4a-5ce5-4e49-a601-9a49ec633476)

4. Press ``Load`` and move the ``Dracula.theme`` to the opened directory and ``Inconsolata.ttf`` to ``fonts/`` subdirectory (dragging a file to the file dialog might not work - if that's the case, navigate to that folder using a system file explorer).
   ![image](https://github.com/user-attachments/assets/a8432f59-1c54-490b-9ccb-7fc79c327f81)
6. Select ``Dracula.theme`` from the dialog and press ``Open``.
7. Boom! It's working ✨

   ![image](https://github.com/user-attachments/assets/c30c7a94-e713-482d-8fbb-4c5cd610c158)


#### More than syntax higlighting?
Creating a drak Dracula theme for the whole program would require extensive paching of the source code, as currently FreshIDE doesn't use the new GUI library (``freshlib``), but rather win32 API calls, which doesn't support theming, but if someone succesfully does it, please let me know. Otherwise, you need to wait for Fresh IDE v3 to be released.
