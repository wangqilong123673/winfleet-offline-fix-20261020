# WinFleet 离线假告警修复包（2026-10-20）

中控二进制：`winfleet-server.exe`（假离线修复：offline floor + resolved_no_gap）

## 下载用法（推荐）

1. 打开本仓库，把 **所有** `part_00.b64` … `part_12.b64` 和 `assemble.ps1` 下到同一文件夹  
2. 在该文件夹打开 PowerShell，运行：

```powershell
powershell -ExecutionPolicy Bypass -File .\assemble.ps1
```

3. 得到 `winfleet-server.exe` 后拷到 `D:\jiankong\bin\`（建议同时留一份 `winfleet-server-20261020off.exe`）  
4. **双击** `D:\jiankong\一键启动.cmd` 重启中控（不要任务管理器强杀）

## 校验

- exe MD5：`E499CE2F960F6CCD27773AAB326D14AE`
- 大小：22248448 字节
