FLEXDEBUG [BETA]
DLL:
DLLs are MS's implementation of shared libraries. DLLs are so much like an EXE that the file format itself is the same
ThereFore they are more flexible to use 
advantage:
DLL can be Attached with any WindowsProgram or language
reference:
[python](https://docs.python.org/3/library/ctypes.html) [C++](https://msdn.microsoft.com/en-us/library/ms235636.aspx) 
[java](https://www.chilkatsoft.com/java-loadlibrary-windows.asp)

usage:

DbgStub("directory")
note : in directory string "\\" double back-slashes are mandatory along with valid path of executable

Results:
it will restart process after crash 
3 text files will be created for infomation on crash:
Exception_info.txt
Process_Creation.txt
ExitProcess.txt

Media:
It can be used with serverl projects such as fuzzers 

