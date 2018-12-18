# clear-temp.bat


@echo off<br>
@break off<br>
@title Cleaner<br>
@color 0a<br>
@cls<br>
%SystemRoot%\explorer.exe "C:\Documents and Settings\"%USERNAME%"\Recent"<br>
%SystemRoot%\explorer.exe "C:\Documents and Settings\"%USERNAME%"\Local Settings\Temp<br>
%SystemRoot%\explorer.exe %SystemRoot%\Prefetch<br>
%SystemRoot%\explorer.exe %SystemRoot%\Temp<br>
echo "All Directory Opened Successfully!"<br>
exit<br>
C:\$Recycle.Bin<br>
