# Navne på moduler/kommandoer

* Undgå at brug noget at andre kunne finde på at bruge

F.eks.:
* `Capa.PowerShell.Module.PowerPack.Service` er langt men unikt navn
* `Exit-PpCommandNotRecognized` burde være unikt nok til at undgå konflikter
  * Pp står for PowerPack
  * Den følger en standard for navngivning af funktioner (Verb-Noun)
  * GitHub Copilot kan også drille og især hvis ens komandoer og parametre ikke følger samme standard (f.eks. i reg delen af PowerPack hvor man skifter i parameter noget forskelligt)
* `Get-CapaUnitFolder` burde være unikt nok til at undgå konflikter
  * Capa står for det er en komando fra SDK'et
* `Add-PSDll` & `Start-PSDownloadPackage` er ikke særlig unikke navne

---

## Man behøver ikke at følge Verb-Noun standarden

Det giver dog følgen udfordringer:

* Når du importerer et modul brokker PowerShell sig over at du ikke følger standarden
* I VS Code vil den af og til ikke give kommandoen farve og blot hold den hvid
* GitHub Copilot heller ikke helt finde ud af det
