# Dawaj Dawaj

Auto-Installer für das WoW-Addon **Dawaj Dawaj**. Eine kleine `.exe`, die den richtigen
AddOns-Ordner selbst findet, das Addon installiert und bei jedem Start auf Updates prüft.

> Dieses Repo enthält nur die fertigen Pakete. Der Quellcode ist privat.

## Installation (einmalig)

1. **Launcher herunterladen:** Unter [**Releases**](../../releases/latest) bei „Assets" die
   Datei **`dawaj-launcher-….exe`** (die `.exe` mit der Versionsnummer) herunterladen.
2. **Doppelklick** auf die Datei.
3. Beim ersten Start zeigt Windows evtl. **„Der Computer wurde durch Windows geschützt"**.
   Das ist normal bei kleinen Programmen ohne teures Zertifikat — die Datei ist sauber.
   → Auf **„Weitere Informationen"** klicken → **„Trotzdem ausführen"**.
4. Im Fenster auf **„Installieren"** klicken. Fertig.
5. In WoW einmal `/reload` eingeben (oder das Spiel neu starten).

## Updates

Einfach **die `.exe` ab und zu starten** und auf **„Aktualisieren"** klicken, wenn eine neue
Addon-Version angezeigt wird. Danach in WoW `/reload`.

Der Launcher **aktualisiert sich auch selbst**: Gibt es eine neuere Launcher-Version, erscheint
oben ein Hinweis mit dem Knopf **„Launcher aktualisieren"** — einmal klicken, danach den
Launcher neu starten.

## Häufige Fragen

- **„WoW-Ordner nicht gefunden":** Auf **„WoW-Ordner wählen …"** klicken und den Ordner
  auswählen, in dem WoW installiert ist (der Ordner mit `_retail_` darin, meist
  `C:\Program Files (x86)\World of Warcraft`).
- **Wird mein Spielstand/meine Einstellungen überschrieben?** Nein. Der Launcher legt nur
  die Addon-Dateien ab und löscht nichts von deinen persönlichen Daten.
- **Muss WoW geschlossen sein?** Nicht zwingend — aber nach dem Update einmal `/reload`
  machen, damit WoW die neue Version lädt. Bei ganz neuen Modulen: WoW komplett neu starten.

---

*Dawaj Dawaj ist ein privates Hobby-Projekt. Keine offizielle Blizzard-Software.*
