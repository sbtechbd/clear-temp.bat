# clear-temp.bat


@echo off
@break off
@title Cleaner
@color 0a
@cls
%SystemRoot%\explorer.exe "C:\Documents and Settings\"%USERNAME%"\Recent"
%SystemRoot%\explorer.exe "C:\Documents and Settings\"%USERNAME%"\Local Settings\Temp
%SystemRoot%\explorer.exe %SystemRoot%\Prefetch
%SystemRoot%\explorer.exe %SystemRoot%\Temp
echo "All Directory Opened Successfully!"
exit
C:\$Recycle.Bin
