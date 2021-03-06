# gdbgui release history

## dev

## 0.7.8.3
* Remove optimization for fetching registers due to potential bug

## 0.7.8.2
* bugfix in logic when jumping to source code line
* bugfix for when variable goes from`empty -> 1 element`
* add CODE OF CONDUCT, CONTRIBUTING, and CHANGELOG files

## 0.7.8.1
* correctly display `<` and `>` in console widget

## 0.7.8.0
* show disassembly when file is unknown or missing
* show new children in expressions widget when they are dynamically added by application (@wuyihao)
* suppress nuisance errors when hover variable or fflush command is not found
* improve logic when source code line should be jumped to
* escape brackets in disassembly, and gracefully hide missing opcodes
* update socketio version for more reliable websocket connection

## 0.7.7.0
* Show variable values when hovering in source code
* gracefully handle hostname not being present in /etc/hosts when running with remote flag
* Use external state management library (`stator.js`) for client ui
