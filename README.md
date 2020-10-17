<h4 align="center">
  <img src="https://img.shields.io/github/languages/top/LinArcX/nfm.svg"/>  <img src="https://img.shields.io/github/repo-size/LinArcX/nfm.svg"/>  <img src="https://img.shields.io/github/tag/LinArcX/nfm.svg?colorB=green"/>
</h4>

# nfm
Neo file manager written by PDCurses library.

# Build
You have two options:
1. Open solution file that resides here: `.\vs\nfm.sln` and build the project through IDE.
2. Build from command-line via `nmake`.

    2.1. Open visual studio command prompt.

    2.3. Change to root directory of the project.

    2.4. `nmake.exe .\Makefile.win`

        It will create __nfm.exe__ in _release_ directory.

    Tip: If you don't have visual-studio command prompt or prefer to stay in your current pwsh, you can prepare `cl.exe` via this command:

    `Invoke-CmdScript "C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools\VC\Auxiliary\Build\vcvars64.bat"`

## License
![License](https://img.shields.io/github/license/LinArcX/nfm.svg)
