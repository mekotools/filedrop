# filedrop (MekoTools-Abbild)

**Spiegel-Repository des MekoTools-Katalogs.** Hier liegt ausschließlich das fertige
Abbild des Werkzeugs *Filedrop* — nicht der Quelltext der Anwendung.

Verwendet wird es unter **https://filedrop.mekotools.de** (Werkzeugkatalog
[MekoTools](https://mekotools.de)).

- Paket: `ghcr.io/mekotools/filedrop` — anonym ziehbar, festgenagelt auf die
  Fassung `257b00a8` (Quelltext-Stand der Anwendung)
- Quelltext der Anwendung: [mat-sz/filedrop](https://github.com/mat-sz/filedrop),
  Stand `257b00a842c5a0b6579dee06780f0ca47e8ee0ca`, Lizenz BSD-3-Clause-Clear
- Gebaut wird das Abbild in der CI des Bau-Repositories (GitLab, MekoTools);
  der Arbeitsablauf `spiegel.yml` in diesem Repository zieht das Ergebnis
  digest-genagelt aus der Hauptablage und schiebt es nach GHCR. Nur so ist das
  Paket mit einem öffentlichen Repository verknüpft und ohne Anmeldung ziehbar.

## Anpassungen unserer Instanz

Die Anwendung wird unverändert verwendet; beim Bauen legt die CI die deutsche
Oberfläche (Sprachdatei, deutsche Rechtsseiten, Kopfzeile ohne fremden
Twitter-Verweis) über den festgeschriebenen Quelltext-Stand. Details stehen im
Bau-Repository.
