# Mitwirken an Kernwerk

## Grundregeln

- Änderungen erfolgen über einen eigenen Branch und einen Pull Request.
- Jeder Commit muss einen klaren, sachlichen Zweck haben.
- Bootkritische Änderungen benötigen serielle Diagnosemarken.
- Neue Funktionen dürfen erst nach nachvollziehbarem Build und Test als produktiv bezeichnet werden.
- Schutzvermerk in Projektdateien: Wilfried A.

## Mindestprüfung vor einem Pull Request

1. Quellcode baut ohne neue Warnungen.
2. EFI-Datei wird erzeugt.
3. QEMU/OVMF-Smoke-Test läuft ohne Panic oder Timeout.
4. README oder technische Dokumentation wird bei Verhaltensänderungen aktualisiert.
5. Binärdateien und lokale Build-Ausgaben werden nicht eingecheckt.

## Branch-Namen

- `feature/<thema>`
- `fix/<thema>`
- `docs/<thema>`
- `setup/<thema>`

## Commit-Nachrichten

Verwende kurze, eindeutige Nachrichten, zum Beispiel:

- `Füge GOP-Framebuffer-Prüfung hinzu`
- `Behebe Überlauf in Mauskoordinaten`
- `Dokumentiere QEMU-Smoke-Test`
