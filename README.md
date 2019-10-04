# Icinga language for VS Code
This extension adds support for the Icinga 2 configuration language to Visual Studio Code.

## **IMPORTANT - PLEASE READ**
Unfortunately the Icinga developers of have chosen to use the `.conf` file exension for
their language, and given that this extension is extremely common for many different
types of files, I cannot assume all `.conf` files are Icinga 2 configuration files.

I recommend using another extension like [modelines](https://marketplace.visualstudio.com/items?itemName=chrislajoie.vscode-modelines)
and adding a modeline like this to the bottom of all of your configuration files.

```
// -*- mode: icinga -*-
```

