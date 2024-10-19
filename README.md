# IT-troubleshooting
IT troubleshooting

1. Creating Windows installation media
   
3. Renaming domain join computer without affecting to domain
   - Make sure it is connected to domain and then could run:
   
   ```powershell
   Rename-Computer -NewName "pc_new_name" -DomainCredential Domain\Admin -Restart
   ```
   ```powershell
   netdom renamecomputer WIN-I4568s.aviation.inc /newname MG56-01 /userd:aviation\DomainUserName /passwordd:P@ssw0rd
   ```
   ```powershell
   netdom renamecomputer WIN-I4568s.aviation.inc /newname MG56-01 /userd:aviation\DomainUserName /passwordd:P@ssw0rd /reboot
   ```
5. 
