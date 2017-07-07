Idea and project goals
======================

Idea is to simplify GUI development by defining minimalistic API and enabling
procedural, declarative and visual tools for GUI software development.

Procedural style of GUI design, as done with tkinter, is tedious and
hard to follow.  Declarative style is already used by Kivy and Enamel, as Kv
language or declarative extension to the Python language grammar, respectively.
IMHO, declarative style should be reserved for style configuration and GUI tree
description in terms of yaml syntax.

Widget is a basic concept in all of the GUI libraries.  Big number of derived
widgets and responsibility to map different data types to widgets complicates
GUI development.  Reducing the number of derived widgets to minimum and
introducing automatic mapping of basic data types to GUI widgets, results in
easy GUI development and more consistent GUIs.

Geometry management is another important concept in GUI development.  GUI
libraries have number of different layouts, with specific logic behind them.
In practise, almost every layout can be derived from a grid.  Simplification of
geometry management is done by offering only grid layout and introducing new
visual grid management by widget dragging and widget configuration through
context menus.

