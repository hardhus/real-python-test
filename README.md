Hello, world! This is my first PUSH to Github.

If you encounter the error message "_File cannot be loaded because running scripts is disabled on this system_".

### Temporary Solution (Geçici Çözüm)

To bypass the script execution policy temporarily, open PowerShell as an administrator and run the following command:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

### Permanent Solution (Kalıcı Çözüm)

To permanently bypass the script execution policy, open PowerShell as an administrator and run the following command.

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned
```
