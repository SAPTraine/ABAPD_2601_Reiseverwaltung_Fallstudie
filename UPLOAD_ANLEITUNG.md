# Upload-Anleitung für GitHub

## Ziel

Diese Dateien gehören in das Repository:

```text
https://github.com/SAPTraine/ABAPD_2601_Reiseverwaltung_Fallstudie
```

## Variante 1: Im GitHub-Browser hochladen

1. ZIP-Datei lokal entpacken.
2. Repository in GitHub öffnen.
3. Auf **Add file → Upload files** klicken.
4. Den Inhalt des entpackten Ordners hochladen.
5. Unten als Commit-Nachricht eintragen:

```text
Projektstruktur und Teilnehmerauftrag ergänzt
```

6. Auf **Commit changes** klicken.

## Variante 2: Per Git auf der Kommandozeile

```bash
git clone https://github.com/SAPTraine/ABAPD_2601_Reiseverwaltung_Fallstudie.git
cd ABAPD_2601_Reiseverwaltung_Fallstudie
```

Dann die Dateien aus diesem Paket in den geklonten Ordner kopieren.

Anschließend:

```bash
git add .
git commit -m "Projektstruktur und Teilnehmerauftrag ergänzt"
git push
```

## Hinweis

Git speichert keine leeren Ordner. Deshalb enthalten die vorbereiteten Ordner jeweils eine `.gitkeep`-Datei.
