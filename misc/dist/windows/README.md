# Windows installer doesnt work yet. focus on portable version for now

`omidot.iss` is an [Inno Setup](https://jrsoftware.org/isinfo.php) installer file
that can be used to build a Windows installer. The generated installer is able
to run without Administrator privileges and can optionally add Godot to the
user's `PATH` environment variable.

To use Inno Setup on Linux, use [innoextract](https://constexpr.org/innoextract/)
to extract the Inno Setup installer then run `ISCC.exe` using
[WINE](https://www.winehq.org/).

## Building

- Place a omidot editor executable in this folder and rename it to `omidot.exe`. doesnt work yet
- Run the Inno Setup Compiler (part of the Inno Setup suite) on the `omidot.iss` file.

If everything succeeds  , an installer will be generated in this folder. the compiling is not done yet so ignore this page. will be implemented in future 
