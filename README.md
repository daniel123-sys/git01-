# Prvni Linux server ve vagrantu

## Moje řešení

**Distribuce a verze:** Debian GNU/Linux 13 (trixie)

**Použitý Vagrant box:** bento/debian-13

**Adresář serveru:** srv01

**Výsledek spuštění a přihlášení:** Server se úspěšně spustil příkazem `vagrant up`, přihlášení pomocí `vagrant ssh` fungovalo. Distribuce ověřena příkazem `cat /etc/os-release` – Debian GNU/Linux 13 (trixie).

**Případné problémy a jejich řešení:** První spuštění trvalo déle kvůli stažení boxu `bento/debian-13` – to je normální. Žádné jiné problémy nenastaly.

**Kontrolní kód a záznam ze serveru:**

**Kontrolní kód:** `SPOS-3I-5f5ea579b0417c3087e2fce7445d1e15b0a87cf7749d5dfbbc238b44d8ed8848`

```text
Úloha: git-vagrant / SPOŠ / 3. I / v1
Distribuce: Debian GNU/Linux 13 (trixie)
Hostname: MujDebianServer
Kernel: 6.12.48+deb13-amd64
Virtualizace: oracle
Čas UTC: 2026-09-25T07:11:13Z
Náhodné ID: accab505-c2f9-4e13-be66-27585aaa5a5e
```

**Bonus – AI obrázek a použitý prompt:**
- Obrázek: `./Images/linux-server.png`
- AI nástroj: perchance.org
- Prompt: "Vytvoř tematický obrázek na téma Linux, Git, Vagrant a virtuální servery"

![Moje virtuální Linuxová laboratoř](./Images/linux-server.png)

## Nápověda a odkazy
- Vagrant – příklady VM v ročníkovém projektu
- Jak probíhá výuka operačních systémů na SPOŠ
- Dokumentace Vagrantu
- Dokumentace .gitignore

## Použití AI

Při tvorbě tohoto řešení byly využity nástroje umělé inteligence (Kimi) pro:
- vygenerování tematického obrázku (`Images/linux-server.png`),
- Při úpravách README.