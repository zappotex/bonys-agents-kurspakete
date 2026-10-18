# Kurspakete für Bony's Agents

Fertige **Kurspakete** (`.bonyspaket`) für [Bony's Agents](https://github.com/zappotex/BonysAgents) – von
Anfänger bis Experte. Ein Kurspaket ist der *Inhalt* einer Schulung (Lektionen, Ablaufplan, Handout, Prüfaufgaben,
Quiz); durcharbeiten lässt es sich allein (Selbstlern-Modus) oder in einem Kurs.

In Bony's Agents: **„Kurse“ → „Kurspakete“ → „Aus dem Internet …“**. Die App lädt die Liste aus
[`index.json`](index.json), lädt ein Paket nur über HTTPS und prüft Größe, SHA-256 und Inhalt, bevor es in die
Bibliothek kommt.

## Aufbau

```
index.json      Liste der Kurspakete (Name, Version, Stufe, Datei, SHA-256, Größe)
pakete/         die .bonyspaket-Dateien
```

Das Format ist beschrieben in
[docs/kurspaket-format.md](https://github.com/zappotex/BonysAgents/blob/main/docs/kurspaket-format.md).

## Regeln für Beiträge

- **Keine API-Schlüssel, Tokens, Passwörter oder Zugangsdaten** in Kurspaketen. Teilnehmer nutzen kostenlose
  Modelle mit eigenem Konto oder ihren eigenen Schlüssel.
- Keine persönlichen Daten.
- Prüfskripte laufen nur im Agent-PC, geben nichts aus und lesen nie Schlüssel aus.

## Lizenz

Die Inhalte der Kurspakete stehen, sofern im Paket nicht anders angegeben, unter
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.de). Name und Logo von Bony's Agents sind davon
ausgenommen.
