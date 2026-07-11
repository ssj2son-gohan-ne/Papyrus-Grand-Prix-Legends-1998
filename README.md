# Papyrus-Grand-Prix-Legends-1998 with dxWrapper

## Version 1.7 (dxwrapper-crash-20260626-193551-081.dmp / 7z)
- In Game Picture and config see: https://github.com/elishacloud/dxwrapper/issues/353#issuecomment-3938482613
- Dump for Error:
  "Error occurred in the application: code=0xC0000005 flags=0x00000000 addr=797625AF rw=0 bad=00000000 module=C:\Sierra\GPL\dxwrapper.dll Registers: EIP=0x797625AF ECX=0x00000000 EAX=0x0C326BB0"
- "https://github.com/elishacloud/dxwrapper/issues/353#issuecomment-4701785067"

## Version 1.7 (dxwrapper-crash-20260711-084717-640.dmp / 7z)
- Testing Release Binaries: https://github.com/elishacloud/dxwrapper/issues/353#issuecomment-4850027184
- Enabled Options: 
  ```shell
    DDrawCompat32              = 1
    DdrawOverrideBitMode       = 16
    DdrawUseDirect3D9Caps      = 1
    ```
    and
    ```shell
    DdrawFillSurfaceColor      = 1
    ```
  
