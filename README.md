# SEB-Bypass
Allows you to run Safe Exam Browser in ANY virtual machine, essentially defeating their anti client tampering and anti Virtual machine detection.

## Warning
This bypass is not guarenteed to be functional on all versions of SEB and on all proctoring setups. To get the fully updated, working bypass join our discord at: https://discord.gg/nZwExHwPgw 

### How it works
I edited the source code of Safe Exam Browser to always return false for virtual machine detection, and always return success when it attempts to verify it's integrity.

### Setup
You can either download the project or git clone it, download, then compile it yourself(requires C# runtimes and visual studio). Then navigate to SafeExamBrowser.Runtime\bin\x64\debug. Finally copy all the files from there into your existing SEB installation (typically at 'C:\Program Files\SafeExamBrowser\Application\').

Or, download the release which contains everything you need, already compiled. After the download has completed navigate to your SEB installation(typically at 'C:\Program Files\SafeExamBrowser\Application\'). Then drag and drop all everything from the folder you downloaded into there. On the popup click 'replace the files in this destination'. 

### Common Issues
A big red screen/SEB crashess: make sure you compiled in debug x64, I honestly have no clue why release functions that way.

### Showcase
<img width="1919" height="1079" alt="SEB" src="https://github.com/user-attachments/assets/d6abcb2e-9f83-48e7-9b2e-d7a3b18de7fd" />

