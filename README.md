# AxisVM Modellgenerator

Der AxisVM Modellgenerator erzeugt aus Bauplänen (PDF) ein AxisVM-Modell. Er läuft als eigene App neben AxisVM und
verbindet sich von selbst mit der offenen AxisVM. Es gibt zwei Wege:

- **KI-Assistent:** Eine KI liest die Pläne und macht einen Entwurf des Modells. Der Ingenieur prüft ihn im Gespräch
  mit ihr und korrigiert, bevor das Modell geschrieben wird. Die KI braucht ein Plansatzpaket.
- **EasyModeler:** Der Ingenieur zeichnet das Modell selbst auf dem Plan, ohne KI.

Ein geschriebenes Modell lässt sich später nachführen: Die App ändert nur, was sich seit dem letzten Export geändert
hat, und lässt Änderungen von Hand in AxisVM stehen.

Die App gibt es auf Deutsch, Französisch, Italienisch und Englisch.

## Herunterladen

Die neueste Version liegt unter [Releases](../../releases/latest):
`AxisVMModellgenerator_Setup_<Version>.exe`.

## Voraussetzungen

- Windows 10 oder 11, 64 Bit
- AxisVM 27 oder AxisVM X8
- Administratorrechte für das Setup
- Internetverbindung: Projekte, Pläne und die KI laufen über den Server `ki.loca-software.com`
- Eine Lizenz für den Modellgenerator; für den KI-Assistenten zusätzlich ein Plansatzpaket

## Installieren

1. AxisVM schliessen.
2. Das Setup ausführen. Es installiert die App nach `C:\Program Files\AxisVM Modellgenerator` und legt Verknüpfungen
   im Startmenü und auf dem Desktop an. Für AxisVM X8 legt es zusätzlich das Plugin nach
   `<AxisVM>\Plugins\Modellgenerator`; AxisVM 27 braucht kein Plugin.
3. AxisVM starten, dann den Modellgenerator über das Startmenü oder den Desktop. Die App verbindet sich von selbst
   mit der laufenden AxisVM.

War AxisVM während der Installation offen, AxisVM einmal neu starten.

## Aktualisieren

Die App prüft bei jedem Start, ob es hier eine neuere Version gibt, und bietet sie an. Mit „Jetzt aktualisieren“
lädt sie das Setup, prüft seine Signatur und installiert es über die bisherige Version. Einstellungen und Projekte
bleiben erhalten.

- AxisVM vorher schliessen. Läuft AxisVM X8, wird die App ersetzt, das Plugin aber erst beim nächsten Setup.
- Die App startet nur ein Setup mit gültiger Signatur. Neben jedem Setup liegt dafür eine Datei `.sig`.

Wer lieber von Hand aktualisiert, lädt das neueste Setup hier herunter und führt es aus.

## Daten

Projekte und Pläne liegen auf dem Server `ki.loca-software.com` in Deutschland, auch beim EasyModeler ohne KI. Für
den KI-Assistenten gehen Planinhalte, Chat und Ergebnisse der Werkzeuge zusätzlich an Anthropic. Fehler und
Abstürze meldet die App mit ihren Protokollen automatisch; „Hilfe › Problem melden…“ schickt einen eigenen Bericht.
Die Einzelheiten regeln die AGB und der Datenschutzhinweis von Ingware.

## Kontakt

Fragen, Lizenzen und Fehler: Ingware AG
