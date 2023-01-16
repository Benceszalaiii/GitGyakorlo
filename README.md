# Verziókezelés alapjai
## 1. git letöltése
- [git for windows][gitdownload]
- [git scm][git scm]

[gitdownload]: https://gitforwindows.org/
[git scm]: https://git-scm.com/
## 2. Konfigurációs parancsok
- git config --global user.name Benceszalaiii
- git config --global user.email szalai.bence.bendeguz@students.jedlik.eu
- git config --global credential.helper wincred
## 3. Repository létrehozása
- git init
## 4.Állomány hozzáadása a stagehez
  A stagen lévő állományokról tudunk állapotfelvétel készíteni (commit-ot)
  Üres mappa nem kerül a stagere
- git add állomány_neve
- git add . (összes állomány és mappa hozzáadása)
 ## 5. Állapotfelvétel (commit) készítése
 - git commit -m "commit message"
## 6. Git állapot és log lekérdezése
- git status
- git log
## 7. Lokális változások szinkronizálása a távoli repóba
- git push
## 8. Távoli repó másolása (klónozása) a lokális repóba
- git clone "távoli repó url címe"
## 9. Ágak (branches) kezelése
> Lokális ágak listázása
- git branch
> Lokális és távoli ágak listázása
- git branch -av
> Ág létrehozása
- git branch új_ág_neve
- git checkout -b új_ág_neve
> Váltás egy másik ágra
- git checkout másik_ág_neve
> Ág törlése
- git branch -d törlendő_ág_neve