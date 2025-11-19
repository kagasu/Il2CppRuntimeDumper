# Il2CppRuntimeDumper
Il2CppRuntimeDumper is a tool designed to extract metadata, method information, and type data
from a running Unity (IL2CPP) application.
It is based on Zygisk-Il2CppDumper and restructured to work in Windows.

### How to Use
1. Clone this repository.
2. Build the project.
3. Rename `Il2CppRuntimeDumper.dll` to `version.dll`.
4. Place `version.dll` in the same folder as `GAME.exe`.
5. Run game.
6. Check `C:\dump.cs`

### Original Code
- [Perfare/Zygisk-Il2CppDumper](https://github.com/Perfare/Zygisk-Il2CppDumper)

