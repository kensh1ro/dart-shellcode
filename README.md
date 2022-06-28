# dart-shellcode
A PoC executing shellcode in Dart.
This project shows that Dart can be used in Red teaming and Implant development (e.g. a C2 framework can be written 100% in dart)

Security products are not good at analyzing Dart, and they won't be anytime soon, so this will probably stay FUD for a long time.

## Installation
Make sure dart is installed in inside PATH environment variable

`git clone https://github.com/kensh1ro/dart-shellcode.git`

`cd dart-shellcode`

`dart pub get`

`dart compile exe .\shellcode_exec.dart`



#### Note: this was a painful experience to get this to work (Dart really sucks in FFI).
