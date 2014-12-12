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
2. Scroll through template list to choose any or press the Shortcut keys for corresponding templates.

Shortcut Keys:
==============
1. f for Facade
2. sc for SimpleCommand
3. mc for MacroCommand
4. p for Proxy
5. ac for AsyncCommand
6. amc for AsyncMacroCommand
7. ap for AsyncProxy
8. c for Component (viewComponent)
9. md for Module
10. jm for JunctionMediator
11. pam for PipeAwareModule
12. msg for Message

Two dynamic variables have been defined for each template. $NAMESPACE$.$MODULE$

$NAMESPACE - Active on load, start typing to change the namespace. 

$MODULE$ - Prepoulated with the filename without extension

The NAME property for each actor is data-bind to $NAMESPACE$.$MODULE$ as well to save retyping.
