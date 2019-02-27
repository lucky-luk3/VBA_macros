# Prueba completa
1. Bypass de AMSI
2. Bypass de UAC
3. Kill AV

## Contraseñas
### Windows Vault
https://github.com/PowerShellMafia/PowerSploit/blob/master/Exfiltration/Get-VaultCredential.ps1
### Navegadores

### Mimikatz
https://raw.githubusercontent.com/xorrior/RandomPS-Scripts/master/Invoke-RemoteMimikatz.ps1
### Kelogger
https://github.com/PowerShellMafia/PowerSploit/blob/master/Exfiltration/Get-Keystrokes.ps1

## Datos
### Sistema
https://github.com/xorrior/RandomPS-Scripts/blob/master/Invoke-WindowsEnum.ps1
### IP Real
https://stackoverflow.com/questions/3303545/can-i-try-to-ping-a-website-through-a-specific-adapter
### Micrófono
https://github.com/PowerShellMafia/PowerSploit/blob/master/Exfiltration/Get-MicrophoneAudio.ps1
### Navegadores
https://github.com/EmpireProject/Empire/blob/master/data/module_source/collection/Get-BrowserData.ps1
### Captura de pantalla
https://github.com/PowerShellMafia/PowerSploit/blob/master/Exfiltration/Get-TimedScreenshot.ps1 --> Intervalo de tiempo
https://github.com/Mr-Un1k0d3r/RedTeamPowershellScripts/blob/master/scripts/Take-Screenshot.ps1
### Portapapeles
https://github.com/EmpireProject/Empire/blob/master/data/module_source/collection/Get-ClipboardContents.ps1
### Certificados

### MiniDump Procesos
https://github.com/EmpireProject/Empire/blob/master/data/module_source/collection/Out-Minidump.ps1

### Metadatos ficheros Office

## Persistencia
https://github.com/EmpireProject/Empire/blob/master/data/module_source/persistence/Invoke-BackdoorLNK.ps1
https://github.com/xorrior/RandomPS-Scripts/blob/master/WMIBackdoor.ps1



## C#
https://github.com/xorrior/Random-CSharpTools


# Contenido
``` VBA
Private Sub Document_Open()

    ActiveDocument.ActiveWindow.View.ShowHiddenText = True
    ActiveDocument.ActiveWindow.View.ShowPicturePlaceHolders = False
    Word.Selection.Range.Sections.First.Range.Select
    Selection.Font.Hidden = True

End Sub
```

https://drive.google.com/open?id=1RCCEeMwa6npBFYcOFLwOc9LKjVfmTWs-
