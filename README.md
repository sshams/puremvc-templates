puremvc-templates
=================

File Templates for PureMVC Actors

Based on IDE's and ports to speed up development time. 

WebStorm
============

Installation
=============
Mac: ~/Library/Preferences/WebStorm9/templates
Windows/Unix/Linux: https://intellij-support.jetbrains.com/entries/23358108 

Usage: 
========
1. Create any .js file Press Cmd/Ctrl+J
2. Scroll through template list to choose any or choose the Shortcut keys for their corresponding templates.

Shortcut Keys:
==============
1. f for Facade
2. sc for SimpleCommand
3. mc for MacroCommand
4. p for Proxy
4. ac for AsyncCommand
5. amc for AsyncMacroCommand
6. ap for AsyncProxy
7. c for Component (viewComponent)
8. md for Module
9. jm for JunctionMediator
10. pam for PipeAwareModule

Two dynamic variables have been defined for each template. $NAMESPACE$.$MODULE$

$NAMESPACE - Active on load, start typing to change the namespace. 

$MODULE$ - Prepoulated with the filename without extension

The NAME property for each actor is data-bind to $NAMESPACE$.$MODULE$
