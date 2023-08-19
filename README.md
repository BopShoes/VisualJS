# VisualJS Library
## Run C# Code (beta)
VisualJS lets you run C# code in real-time!<br>Say goodbye to compiling web browser C#, when you can use VisualJS!<br><i>Warning: Not all functions of C# are supported. Only a few.</i>
## Visual Studio Console
You can run VSConsole/BAT files with VisualJS! (quite limited...)<br>For example:
```js
open_terminal_session(); // no longer able to do run_exec_console or open_terminal_session.
run_exec_console("ECHO off"); // wont say "echo hello!"
run_exec_console("echo hello!"); // "hello!"
close_terminal_session(); // No longer be able to do run_exec_console.
```
## WinForms Support Notice
If I ever add WinForms into VisualJS, it will be strictly limtied.<br>Example: Placing button/panel would be able to use a HTML element. Not magic like Visual Studio.
