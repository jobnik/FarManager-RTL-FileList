## FarManager RTL FileList
filelist.cpp file with support for RTL (Hebrew/Arabic) file names

Tested on Far Manager, version 3.0 (build 5342) x86

## Functions added
```
bool IsRTL(string str)
{
  // checks if a string is RTL
}

string StrReverseEx(string str, bool revDigits = false, DWORD Attributes = 0)
{
  /*
    reverse a string, but keep digits and latin chars intact
    this adds some support for RTL languages to show filenames correctly and in correct order
    it is far from perfect, but better than nothing :)
    Set Console Font to "Courier New" to have a unicode support in Far Manager
  */
}

void SetConsoleFont(const wchar_t *fontname, int fontsizeY)
{
  // set console font, not in use (but you can't use if you want)
}
```

## What is FarManager?
https://farmanager.com/

https://github.com/FarGroup/FarManager
