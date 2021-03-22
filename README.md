# ROOT On VS Code

This repository is an example to illustrate how to run ROOT Macros directly in VS Code making use of the [C/C++ extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools). This brings features such as IntelliSense and debugging to ROOT Macros!

## Overview

The repository contains the `hsimple.C` macro from ROOT Tutorials, the resulting `hsimple.root` file, and a `.vscode` folder with the bare minimum configuration necessary for everything to work. Inside said `.vscode` folder we can find:

- `launch.json`: this file provides the debugging configuration -- just edit the path to ROOT's `root.exe` and it's ready!
- `root-on-vscode.code-workspace`: this file contains the workspace configuration -- just edit the path to ROOT's `include` directory and it's ready!

To run the macro:

1. Open the workspace
2. Install the recommended extensions if you haven't done it yet (a toast notification will show up)
3. Press `F5`
