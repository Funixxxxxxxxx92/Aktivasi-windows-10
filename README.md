# Aktivasi Windows 10 Pro dan Microsoft Office

## Aktivasi Windows 10 Pro
Untuk mengaktifkan Windows 10 Pro, buka Command Prompt (CMD) sebagai Administrator, lalu salin dan jalankan perintah di bawah ini:

```cmd
slmgr /upk && timeout /t 15 && slmgr /cpky && timeout /t 15 && slmgr /ipk W269n-WFGWX-YVC9B-4J6C9-T83GX && timeout /t 15 && slmgr /skms kms8.guides.com && timeout /t 15 && slmgr /ato
