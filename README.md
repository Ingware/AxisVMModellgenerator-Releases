# AxisVM Modellgenerator

Der AxisVM Modellgenerator erzeugt aus Bauplänen (PDF) ein AxisVM-Modell. Er läuft als eigene App neben AxisVM und
verbindet sich von selbst mit der offenen AxisVM. Die Pläne liest eine KI; den Plan und das Modell prüft der Ingenieur
im Gespräch mit ihr, bevor das Modell geschrieben wird.

## Herunterladen

Die neueste Version liegt unter [Releases](../../releases/latest):
`AxisVMModellgenerator_Setup_<Version>.exe`.

## Voraussetzungen

- Windows 10 oder 11, 64 Bit
- AxisVM X8, installiert unter `C:\AXISVM X8` oder `C:\Program Files\INTER-CAD\AxisVM X8`
- Administratorrechte für das Setup
- Internetverbindung: die Planerkennung und die KI laufen auf dem Server `ki.loca-software.com`
- Eine Lizenz für den Modellgenerator

## Installieren

1. AxisVM schliessen.
2. Das Setup ausführen. Es installiert die App nach `C:\Program Files\AxisVM Modellgenerator`, legt Verknüpfungen
   im Startmenü und auf dem Desktop an und das Plugin nach `<AxisVM>\Plugins\Modellgenerator`.
3. AxisVM starten, dann den Modellgenerator über das Startmenü oder den Desktop. Die App verbindet sich von selbst
   mit der laufenden AxisVM.

War AxisVM während der Installation offen, AxisVM einmal neu starten.

## Aktualisieren

Die App prüft bei jedem Start, ob es hier eine neuere Version gibt, und bietet sie an. Mit „Jetzt aktualisieren“
lädt sie das Setup, prüft seine Signatur und installiert es über die bisherige Version. Einstellungen und Projekte
bleiben erhalten.

- AxisVM vorher schliessen. Läuft AxisVM, wird die App ersetzt, das Plugin aber erst beim nächsten Setup.
- Die App startet nur ein Setup mit gültiger Signatur. Neben jedem Setup liegt dafür eine Datei `.sig`.

Wer lieber von Hand aktualisiert, lädt das neueste Setup hier herunter und führt es aus.

## Daten

Zur Erkennung gehen die Pläne eines Projekts an den KI-Server `ki.loca-software.com`, ebenso der Chat mit der KI.

## Kontakt

Fragen, Lizenzen und Fehler: Ingware AG
